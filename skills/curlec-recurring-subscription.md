---
name: Set up a recurring subscription
description: Create a plan, a customer, and a subscription for recurring Razorpay Curlec billing.
api: openapi/curlec-razorpay-openapi.json
operations: [createPlan, createCustomer, createSubscription, fetchSubscription]
---

# Set up a recurring subscription

Authenticate with HTTP Basic Auth (`key_id:key_secret`) against `https://api.razorpay.com/v1`. Curlec's recurring billing is the product it was founded on (direct debit / DuitNow / FPX).

## Steps

1. **Create a plan** — `POST /plans` (`createPlan`) with `period` (e.g. `monthly`), `interval`, and an `item` (name, `amount` in smallest subunit, `currency`).
2. **Create a customer** *(optional)* — `POST /customers` (`createCustomer`) with `name`, `email`, `contact`.
3. **Create the subscription** — `POST /subscriptions` (`createSubscription`) referencing `plan_id`, `total_count` (number of billing cycles), and optional `customer_id`. Share the returned `short_url` for customer authorization.
4. **Track** — `GET /subscriptions/{id}` (`fetchSubscription`) and subscribe to the `subscription.charged`, `subscription.activated`, `subscription.halted` webhooks.

## Rules

- The customer must authorize the mandate before charges begin; `subscription.charged` fires per successful cycle.
- `amount` is an integer in the smallest currency subunit.
- Use `notes` for your own subscription/customer correlation ids.
