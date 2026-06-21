# Paddle (paddle)

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
