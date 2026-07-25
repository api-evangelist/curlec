---
name: Accept a payment with Razorpay Curlec
description: Create an order, let the customer pay, then verify and (if needed) capture the payment.
api: openapi/curlec-razorpay-openapi.json
operations: [createOrder, fetchOrder, fetchPayment, capturePayment]
---

# Accept a payment with Razorpay Curlec

Use HTTP Basic Auth: username = `key_id`, password = `key_secret`, against `https://api.razorpay.com/v1`. Use `rzp_test_` keys while integrating.

## Steps

1. **Create an order** — `POST /orders` (`createOrder`). Send `amount` as an integer in the smallest currency subunit (sen for MYR), `currency` (e.g. `MYR`), and a unique `receipt`. The `receipt` is your de-duplication key — reuse it on retries.
2. **Collect payment** — pass the returned `order.id` to Standard Checkout (`checkout.razorpay.com/v1/checkout.js`) or a Payment Link. The customer authorizes the payment.
3. **Verify** — on the webhook `order.paid` / `payment.captured` (verify the `X-Razorpay-Signature` HMAC-SHA256 over the raw body), or poll `GET /orders/{id}` (`fetchOrder`) and `GET /payments/{id}` (`fetchPayment`) to confirm `status`.
4. **Capture if manual** — if you use manual capture, call `POST /payments/{id}/capture` (`capturePayment`) with the exact `amount` and `currency`. Auto-capture skips this step.

## Rules

- Amounts are integers in the smallest subunit — never send decimals.
- Handle `429` with exponential backoff + jitter; `5xx` is safe to retry.
- Errors come back as `{ "error": { code, description, source, step, reason } }` — see `errors/curlec-problem-types.yml`.
