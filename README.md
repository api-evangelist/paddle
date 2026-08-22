# Paddle (paddle)

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

Paddle is a merchant-of-record billing platform for SaaS and digital products. The Paddle Billing API manages the full revenue lifecycle - products, prices, customers, subscriptions, transactions, invoices, adjustments, and discounts - while Paddle handles global sales tax, payment processing, fraud, and compliance on the seller's behalf.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/paddle/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/paddle/refs/heads/main/apis.yml)

## Tags

- Billing
- Payments
- Subscriptions
- Merchant of Record
- SaaS

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Paddle Products API

Create, read, and update the products in your Paddle catalog, including names, descriptions, tax categories, custom data, and product images.

- **Human URL:** [https://developer.paddle.com/api-reference/products/overview](https://developer.paddle.com/api-reference/products/overview)
- **Base URL:** `https://api.paddle.com`

#### Tags

- Products
- Catalog
- Prices

#### Properties

- [Documentation](https://developer.paddle.com/api-reference/products/overview)
- [API Reference](https://developer.paddle.com/api-reference/products/list-products)
- [OpenAPI](openapi/paddle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paddle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paddle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paddle Prices API

Manage one-time and recurring prices for products, including billing cycles, trial periods, unit and tiered pricing, country overrides, and a pricing-preview endpoint that calculates localized prices and taxes.

- **Human URL:** [https://developer.paddle.com/api-reference/prices/overview](https://developer.paddle.com/api-reference/prices/overview)
- **Base URL:** `https://api.paddle.com`

#### Tags

- Prices
- Pricing
- Catalog

#### Properties

- [Documentation](https://developer.paddle.com/api-reference/prices/overview)
- [API Reference](https://developer.paddle.com/api-reference/prices/list-prices)
- [OpenAPI](openapi/paddle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paddle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paddle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paddle Customers API

Manage customers and their related addresses and businesses, credit balances, customer portal sessions, and authentication tokens used by Paddle.js and the customer portal.

- **Human URL:** [https://developer.paddle.com/api-reference/customers/overview](https://developer.paddle.com/api-reference/customers/overview)
- **Base URL:** `https://api.paddle.com`

#### Tags

- Customers
- Addresses
- Businesses

#### Properties

- [Documentation](https://developer.paddle.com/api-reference/customers/overview)
- [API Reference](https://developer.paddle.com/api-reference/customers/list-customers)
- [OpenAPI](openapi/paddle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paddle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paddle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paddle Subscriptions API

Manage the full subscription lifecycle - list, get, and update subscriptions, activate trials, pause, resume, cancel, apply one-time charges, preview updates and charges, and retrieve payment-method-update transactions.

- **Human URL:** [https://developer.paddle.com/api-reference/subscriptions/overview](https://developer.paddle.com/api-reference/subscriptions/overview)
- **Base URL:** `https://api.paddle.com`

#### Tags

- Subscriptions
- Recurring Billing
- Lifecycle

#### Properties

- [Documentation](https://developer.paddle.com/api-reference/subscriptions/overview)
- [API Reference](https://developer.paddle.com/api-reference/subscriptions/list-subscriptions)
- [OpenAPI](openapi/paddle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paddle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paddle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paddle Transactions API

Create, read, update, and preview transactions - the core billing object that ties customers, prices, and payments together - and retrieve a PDF invoice or revise customer details for billed transactions.

- **Human URL:** [https://developer.paddle.com/api-reference/transactions/overview](https://developer.paddle.com/api-reference/transactions/overview)
- **Base URL:** `https://api.paddle.com`

#### Tags

- Transactions
- Checkout
- Invoices

#### Properties

- [Documentation](https://developer.paddle.com/api-reference/transactions/overview)
- [API Reference](https://developer.paddle.com/api-reference/transactions/list-transactions)
- [OpenAPI](openapi/paddle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paddle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paddle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paddle Adjustments API

Issue and list adjustments - refunds, credits, and chargebacks against transactions - and download a PDF credit note for an adjustment.

- **Human URL:** [https://developer.paddle.com/api-reference/adjustments/overview](https://developer.paddle.com/api-reference/adjustments/overview)
- **Base URL:** `https://api.paddle.com`

#### Tags

- Adjustments
- Refunds
- Credit Notes

#### Properties

- [Documentation](https://developer.paddle.com/api-reference/adjustments/overview)
- [API Reference](https://developer.paddle.com/api-reference/adjustments/list-adjustments)
- [OpenAPI](openapi/paddle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paddle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paddle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paddle Discounts API

Create, read, and update discounts - percentage, flat, and flat-per-seat coupon codes with usage limits, expiry, and product or price restrictions - applied to checkouts, transactions, and subscriptions.

- **Human URL:** [https://developer.paddle.com/api-reference/discounts/overview](https://developer.paddle.com/api-reference/discounts/overview)
- **Base URL:** `https://api.paddle.com`

#### Tags

- Discounts
- Coupons
- Promotions

#### Properties

- [Documentation](https://developer.paddle.com/api-reference/discounts/overview)
- [API Reference](https://developer.paddle.com/api-reference/discounts/list-discounts)
- [OpenAPI](openapi/paddle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paddle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paddle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Paddle Notifications API

Configure notification destinations (webhook and email), list and inspect delivered notifications, replay failed deliveries, and browse the events and event-type catalog that power Paddle's webhook system.

- **Human URL:** [https://developer.paddle.com/api-reference/notifications/overview](https://developer.paddle.com/api-reference/notifications/overview)
- **Base URL:** `https://api.paddle.com`

#### Tags

- Notifications
- Webhooks
- Events

#### Properties

- [Documentation](https://developer.paddle.com/api-reference/notifications/overview)
- [API Reference](https://developer.paddle.com/api-reference/notification-settings/overview)
- [OpenAPI](openapi/paddle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paddle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paddle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/PaddleHQ)
- [LinkedIn](https://www.linkedin.com/company/paddle)
- [Website](https://www.paddle.com)
- [Documentation](https://developer.paddle.com)
- [Plans](plans/paddle-plans-pricing.yml)
- [Rate Limits](rate-limits/paddle-rate-limits.yml)
- [Fin Ops](finops/paddle-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
