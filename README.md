# Curlec

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Curlec (Razorpay Curlec) is a Malaysian online payment solution and part of Razorpay, the RBI-authorised full-stack payment platform. Curlec lets businesses in Malaysia accept one-time and recurring payments through a Payment Gateway, Payment Links, Payment Pages, Payment Buttons, hosted Checkout, DuitNow real-time payments, FPX online banking, cards and e-wallets, plus Subscriptions and direct-debit recurring billing. It runs on the shared Razorpay REST API (https://api.razorpay.com/v1) — a RESTful, JSON, Basic-Auth API covering Orders, Payments, Refunds, Settlements, Disputes, Customers, Invoices, Plans, Subscriptions, Payment Links, QR Codes, Virtual Accounts, Transfers/Route, and the RazorpayX business-banking and payouts suite. Curlec exposes official server SDKs, webhooks, a sandbox test mode, a public Postman workspace, and an official hosted MCP server for AI-agent access.

**Areas:** Company · Payments · Payment Gateway · Recurring Payments · Subscription · Direct Debit · Fintech · Malaysia · DuitNow · FPX · Webhook · Razorpay

## Curlec on APIs.io

Everything profiled for Curlec is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/curlec/](https://apis.io/providers/curlec/)** — or go straight to one of the APIs or properties below.

### APIs (30)

- [Curlec Bills API](https://apis.io/apis/curlec/curlec-bills-api/) — Razorpay Billme digital receipts and bills for retail, food & beverage, events, and ecommerce.
- [Curlec Customers API](https://apis.io/apis/curlec/curlec-customers-api/) — Customer profiles store contact information for recurring billing, saved cards, and personalised checkout. Each email+contact combination must be unique.
- [Curlec Disputes API](https://apis.io/apis/curlec/curlec-disputes-api/) — Disputes (chargebacks) are raised by customers via their bank. You can accept (lose) or contest (challenge with evidence) each dispute. Monitor respond_by…
- [Curlec Documents API](https://apis.io/apis/curlec/curlec-documents-api/) — Document uploads for dispute evidence. Upload JPEG, PNG, or PDF files and receive a document ID to reference in dispute contest submissions.
- [Curlec Instant Settlements API](https://apis.io/apis/curlec/curlec-instant-settlements-api/) — On-demand settlements let you transfer your available Razorpay balance to your bank account immediately, outside the normal settlement cycle. Fees apply.…
- [Curlec Invoices API](https://apis.io/apis/curlec/curlec-invoices-api/) — Invoices and payment pages for one-time or partial-payment collection. Create in draft, issue to the customer, and track payment status. Cannot be used for…
- [Curlec Items API](https://apis.io/apis/curlec/curlec-items-api/) — Reusable catalog items that can be referenced in invoice line items. Defining items once avoids repeating price and description on each invoice.
- [Curlec Linked Accounts API](https://apis.io/apis/curlec/curlec-linked-accounts-api/) — Sub-merchant accounts (Linked Accounts) created under a Route marketplace. Includes account creation, stakeholder KYC, and Route product activation. Uses…
- [Curlec Orders API](https://apis.io/apis/curlec/curlec-orders-api/) — Orders are the starting point for accepting a payment. Create an order with the amount and currency, pass the order_id to Razorpay Checkout, then verify the…
- [Curlec Partner Accounts API](https://apis.io/apis/curlec/curlec-partner-accounts-api/) — Sub-merchant account lifecycle management via Partners API (Aggregator/Platform model). Uses OAuth access_token authentication.
- [Curlec Partner Documents API](https://apis.io/apis/curlec/curlec-partner-documents-api/) — Upload and fetch KYC documents for sub-merchant accounts and their stakeholders.
- [Curlec Partner Stakeholders API](https://apis.io/apis/curlec/curlec-partner-stakeholders-api/) — Manage stakeholders (directors/executives) for sub-merchant accounts. Multiple stakeholders allowed per account.
- [Curlec Partner Webhooks API](https://apis.io/apis/curlec/curlec-partner-webhooks-api/) — Configure webhooks for sub-merchant accounts to receive payment events. Maximum 30 per account.
- [Curlec Payment Downtimes API](https://apis.io/apis/curlec/curlec-payment-downtimes-api/) — Scheduled and live downtime information for card, netbanking, and UPI. Poll or subscribe to payment.downtime webhooks to detect degraded methods and adjust…
- [Curlec Payment Links API](https://apis.io/apis/curlec/curlec-payment-links-api/) — Payment Links are shareable URLs to collect payments without a website. Share via SMS, email, or any channel. Supports partial payments, expiry, reminders,…
- [Curlec Payments API](https://apis.io/apis/curlec/curlec-payments-api/) — A payment is created when a customer completes checkout. Payments can be auto-captured or manually captured. Fetch payment details to reconcile and diagnose…
- [Curlec Plans API](https://apis.io/apis/curlec/curlec-plans-api/) — Billing plan definitions for recurring subscriptions. A plan sets the billing period, interval, and per-cycle charge. Plans are reusable across multiple…
- [Curlec QR Codes API](https://apis.io/apis/curlec/curlec-qr-codes-api/) — QR Codes enable offline and digital payment collection. Customers scan with any UPI or card app. Supports fixed-amount and variable-amount codes, single-use…
- [Curlec Refunds API](https://apis.io/apis/curlec/curlec-refunds-api/) — Refunds return captured payment amounts to customers. Normal refunds take 5-7 business days. Instant (optimum) refunds settle immediately but may fall back…
- [Curlec Settlements API](https://apis.io/apis/curlec/curlec-settlements-api/) — Settlements represent batch transfers of collected payment funds to your bank account. Use the recon endpoint for transaction-level reconciliation reports…
- [Curlec Subscriptions API](https://apis.io/apis/curlec/curlec-subscriptions-api/) — Recurring billing subscriptions. Customers must authorize a payment mandate (UPI Autopay, NACH, or card-on-file) via the short_url before charges begin.…
- [Curlec Transfers API](https://apis.io/apis/curlec/curlec-transfers-api/) — Fund transfers from a merchant, payment, or order to a Linked Account (Route). Supports payment-based splits, direct on-demand transfers, settlement hold…
- [Curlec Virtual Accounts API](https://apis.io/apis/curlec/curlec-virtual-accounts-api/) — Virtual bank accounts and UPI VPAs that accept NEFT/RTGS/IMPS/UPI payments (Smart Collect). Each incoming payment creates a BankTransfer entity. Supports…
- [Curlec X Account Validation API](https://apis.io/apis/curlec/curlec-x-account-validation-api/) — Penny drop and reverse penny drop bank/VPA validation
- [Curlec X Banking Balances API](https://apis.io/apis/curlec/curlec-x-banking-balances-api/) — Fetch RazorpayX account balances
- [Curlec X Contacts API](https://apis.io/apis/curlec/curlec-x-contacts-api/) — RazorpayX payout recipients — create, fetch, update contacts
- [Curlec X Fund Accounts API](https://apis.io/apis/curlec/curlec-x-fund-accounts-api/) — Payout destination accounts (bank, VPA, card) linked to contacts
- [Curlec X Payout Links API](https://apis.io/apis/curlec/curlec-x-payout-links-api/) — Payout links for recipients without saved fund accounts
- [Curlec X Payouts API](https://apis.io/apis/curlec/curlec-x-payouts-api/) — Disbursements via NEFT, RTGS, IMPS, UPI, card — includes composite and approval flows
- [Curlec X Transactions API](https://apis.io/apis/curlec/curlec-x-transactions-api/) — Fetch RazorpayX transaction records — credits (bank_transfer inflows) and debits (payout outflows)

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Curlec Webhooks](https://apis.io/asyncapis/curlec/curlec-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [razorpay](https://apis.io/servers/curlec/razorpay/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Curlec Agentic Access](https://apis.io/agentic-access/curlec/curlec-agentic-access/)

#### Collections (60)

Postman and Open Collection request collections.

- [Razorpay Bills API](https://apis.io/collections/curlec/open-curlec-bills-api/)
- [Razorpay Bills Customers API](https://apis.io/collections/curlec/open-curlec-customers-api/)
- [Razorpay Bills Disputes API](https://apis.io/collections/curlec/open-curlec-disputes-api/)
- [Razorpay Bills Documents API](https://apis.io/collections/curlec/open-curlec-documents-api/)
- [Razorpay Bills Instant Settlements API](https://apis.io/collections/curlec/open-curlec-instant-settlements-api/)
- [Razorpay Bills Invoices API](https://apis.io/collections/curlec/open-curlec-invoices-api/)
- [Razorpay Bills Items API](https://apis.io/collections/curlec/open-curlec-items-api/)
- [Razorpay Bills Linked Accounts API](https://apis.io/collections/curlec/open-curlec-linked-accounts-api/)
- [Razorpay Bills Orders API](https://apis.io/collections/curlec/open-curlec-orders-api/)
- [Razorpay Bills Partner Accounts API](https://apis.io/collections/curlec/open-curlec-partner-accounts-api/)
- [Razorpay Bills Partner Documents API](https://apis.io/collections/curlec/open-curlec-partner-documents-api/)
- [Razorpay Bills Partner Stakeholders API](https://apis.io/collections/curlec/open-curlec-partner-stakeholders-api/)
- [Razorpay Bills Partner Webhooks API](https://apis.io/collections/curlec/open-curlec-partner-webhooks-api/)
- [Razorpay Bills Payment Downtimes API](https://apis.io/collections/curlec/open-curlec-payment-downtimes-api/)
- [Razorpay Bills Payment Links API](https://apis.io/collections/curlec/open-curlec-payment-links-api/)
- [Razorpay Bills Payments API](https://apis.io/collections/curlec/open-curlec-payments-api/)
- [Razorpay Bills Plans API](https://apis.io/collections/curlec/open-curlec-plans-api/)
- [Razorpay Bills QR Codes API](https://apis.io/collections/curlec/open-curlec-qr-codes-api/)
- [Razorpay Bills Refunds API](https://apis.io/collections/curlec/open-curlec-refunds-api/)
- [Razorpay Bills Settlements API](https://apis.io/collections/curlec/open-curlec-settlements-api/)
- [Razorpay Bills Subscriptions API](https://apis.io/collections/curlec/open-curlec-subscriptions-api/)
- [Razorpay Bills Transfers API](https://apis.io/collections/curlec/open-curlec-transfers-api/)
- [Razorpay Bills Virtual Accounts API](https://apis.io/collections/curlec/open-curlec-virtual-accounts-api/)
- [Razorpay Bills X Account Validation API](https://apis.io/collections/curlec/open-curlec-x-account-validation-api/)
- [Razorpay Bills X Banking Balances API](https://apis.io/collections/curlec/open-curlec-x-banking-balances-api/)
- …and 35 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Curlec Razorpay Overlay](https://apis.io/overlays/curlec/curlec-razorpay-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Curlec Authentication](https://apis.io/security/curlec/curlec-authentication/)
- [Curlec Domain Security](https://apis.io/security/curlec/curlec-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Curlec Scopes](https://apis.io/scopes/curlec/curlec-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://curlec.com)
- [Documentation](https://curlec.com/docs/)
- [Getting started](https://curlec.com/docs/payments/)
- [API reference](https://curlec.com/docs/api/)
- [Pricing](https://curlec.com/pricing/)
- [Sign up](https://dashboard.curlec.com/)
- [Support](https://curlec.com/blog/knowledge-base/)
- [Changelog](https://curlec.com/docs/api/changelog/)
- [Blog](https://curlec.com/blog/)
- [Terms of service](https://curlec.com/blog/s/terms-of-use/)
- [Privacy policy](https://curlec.com/blog/s/privacy/)
- [GitHub](https://github.com/razorpay)
- [Status](https://status.razorpay.com/)

## API Evangelist rating

**Kin Score 58.4** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 60.3 |
| Contract governance | 18.2 |
| Operational transparency | 50.0 |
| Developer ergonomics | 75.6 |
| Access clarity | 46.1 |

**Agent readiness 58.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | verified |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | verified |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | flavored (partial credit) |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 42.9** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/curlec/](https://apis.io/providers/curlec/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Curlec: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/curlec/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
