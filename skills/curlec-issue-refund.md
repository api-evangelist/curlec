---
name: Issue and track a refund
description: Refund a captured Razorpay Curlec payment (full or partial) and confirm the outcome.
api: openapi/curlec-razorpay-openapi.json
operations: [fetchPayment, createRefund, fetchPaymentRefunds, fetchRefund]
---

# Issue and track a refund

Authenticate with HTTP Basic Auth (`key_id:key_secret`) against `https://api.razorpay.com/v1`.

## Steps

1. **Confirm the payment is refundable** — `GET /payments/{id}` (`fetchPayment`); the payment must be `captured`.
2. **Create the refund** — `POST /payments/{id}/refund` (`createRefund`). Omit `amount` for a full refund, or send a partial `amount` (integer, smallest subunit, ≤ captured amount). Add a `notes` object for reconciliation metadata.
3. **List / verify** — `GET /payments/{payment_id}/refunds` (`fetchPaymentRefunds`) or `GET /refunds/{id}` (`fetchRefund`) to read `status` (`pending` → `processed`).
4. **React to the outcome** — subscribe to `refund.processed` / `refund.failed` webhooks instead of polling in production.

## Rules

- Partial refund amount must not exceed the captured amount.
- Refunds are asynchronous — treat `pending` as normal and wait for the terminal webhook.
- Retry-safe: a duplicate `createRefund` with the same intent should be guarded by your own reference tracking.
