# Nomba (nomba)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Nomba is a Nigerian fintech platform that provides payment infrastructure for businesses, offering APIs for payment acceptance, transfers, virtual accounts, and cross-border payouts. Their developer platform enables merchants and platforms to integrate card payments, bank transfers, USSD, and QR code payments into applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/apis.yml)

## Tags

- Payments
- Fintech
- Banking
- Transfers
- Virtual Accounts
- Checkout
- Cross-Border Payments
- Cards

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### Nomba Authentication API

The Nomba Authentication API provides OAuth2-based authentication for accessing all Nomba API endpoints. It supports two authentication methods: Client-Credentials for server-to-server integrations and PKCE (Proof Key for Code Exchange) for client-side applications. Developers obtain HTTP bearer tokens that are used to authorize subsequent API calls across the Nomba platform.

- **Human URL:** [https://developer.nomba.com/nomba-api-reference/authenticate/obtain-access-token](https://developer.nomba.com/nomba-api-reference/authenticate/obtain-access-token)
- **Base URL:** `https://api.nomba.com`

#### Tags

- Authentication
- OAuth2
- Security

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/authenticate/obtain-access-token)
- [OpenAPI](openapi/nomba-authentication-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomba-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomba Accounts API

The Nomba Accounts API enables developers to manage business accounts on the Nomba platform. It provides endpoints for retrieving account details, fetching terminals assigned to an account, and managing account-level configurations. This API serves as the foundation for account management operations within the Nomba ecosystem.

- **Human URL:** [https://developer.nomba.com/nomba-api-reference/accounts/fetch-terminals-assigned-to-an-account](https://developer.nomba.com/nomba-api-reference/accounts/fetch-terminals-assigned-to-an-account)
- **Base URL:** `https://api.nomba.com`

#### Tags

- Accounts
- Financial Services
- Terminals

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/accounts/fetch-terminals-assigned-to-an-account)
- [OpenAPI](openapi/nomba-accounts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomba-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomba Virtual Accounts API

The Nomba Virtual Accounts API allows developers to create and manage virtual bank accounts for receiving payments. There is no fixed limit to the number of virtual accounts that can be created for customers. The API supports creating, expiring, and managing virtual accounts, enabling businesses to collect payments via bank transfers with unique account numbers assigned to individual customers or transactions.

- **Human URL:** [https://developer.nomba.com/nomba-api-reference/virtual-accounts/create-virtual-account](https://developer.nomba.com/nomba-api-reference/virtual-accounts/create-virtual-account)
- **Base URL:** `https://api.nomba.com`

#### Tags

- Virtual Accounts
- Payments
- Collections

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/virtual-accounts/create-virtual-account)
- [OpenAPI](openapi/nomba-virtual-accounts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomba-virtual-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-virtual-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomba Transfers API

The Nomba Transfers API provides endpoints for initiating and managing fund transfers. Developers can look up bank codes and names, verify account details, and initiate transfers to Nigerian bank accounts. The API supports domestic money transfers and provides the necessary bank metadata for building payment flows within applications.

- **Human URL:** [https://developer.nomba.com/nomba-api-reference/transfers/fetch-bank-codes-and-names](https://developer.nomba.com/nomba-api-reference/transfers/fetch-bank-codes-and-names)
- **Base URL:** `https://api.nomba.com`

#### Tags

- Transfers
- Payments
- Banking

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/transfers/fetch-bank-codes-and-names)
- [OpenAPI](openapi/nomba-transfers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomba-transfers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-transfers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomba Online Checkout API

The Nomba Online Checkout API enables developers to create checkout orders and process payments through multiple channels. It supports Visa, Verve, and Mastercard payments, as well as USSD, bank transfers, and Nomba QR payments. The API includes tokenized card payment capabilities, allowing merchants to charge returning customers without requiring them to re-enter card details.

- **Human URL:** [https://developer.nomba.com/nomba-api-reference/online-checkout/create-an-online-checkout-order](https://developer.nomba.com/nomba-api-reference/online-checkout/create-an-online-checkout-order)
- **Base URL:** `https://api.nomba.com`

#### Tags

- Checkout
- Payments
- E-Commerce
- Cards

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/online-checkout/create-an-online-checkout-order)
- [OpenAPI](openapi/nomba-online-checkout-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomba-online-checkout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-online-checkout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomba Charge API

The Nomba Charge API provides direct card charging capabilities for developers building payment solutions. It supports OTP submission for card transactions, retrieval of user saved cards, and tokenized card charging. This API is designed for merchants and platforms that need programmatic control over the card payment flow, including handling 3D Secure authentication steps.

- **Human URL:** [https://developer.nomba.com/nomba-api-reference/charge/submit-customer-card-otp](https://developer.nomba.com/nomba-api-reference/charge/submit-customer-card-otp)
- **Base URL:** `https://api.nomba.com`

#### Tags

- Payments
- Cards
- Tokenization

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/charge/submit-customer-card-otp)
- [OpenAPI](openapi/nomba-charge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomba-charge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-charge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomba Transactions API

The Nomba Transactions API allows developers to retrieve and manage transaction records. It provides endpoints for fetching account transaction history, querying transaction details, and processing refunds. This API is essential for building reporting dashboards, reconciliation tools, and transaction monitoring systems on top of the Nomba platform.

- **Human URL:** [https://developer.nomba.com/products/transactions/fetch-account-transactions](https://developer.nomba.com/products/transactions/fetch-account-transactions)
- **Base URL:** `https://api.nomba.com`

#### Tags

- Transactions
- Reporting
- Financial Data

#### Properties

- [Documentation](https://developer.nomba.com/products/transactions/fetch-account-transactions)
- [OpenAPI](openapi/nomba-transactions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomba-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomba Global Payout API

The Nomba Global Payout API is a single integration point that enables cross-border payment operators, remittance platforms, and fintechs to collect funds in Nigerian Naira or stablecoins (USDT/USDC) and trigger instant disbursements to the United Kingdom via Faster Payments, Europe via SEPA, Canada via Interac and bank transfer, and the Democratic Republic of Congo via Mobile Money. The API embeds FX sourcing and compliance directly into the technical layer, eliminating the need for operators to manage foreign exchange processes. It solves capital lockups in cross-border trade by handling currency conversion automatically when funds land in a virtual account.

- **Human URL:** [https://developer.nomba.com/docs/products/global-payout/introduction](https://developer.nomba.com/docs/products/global-payout/introduction)
- **Base URL:** `https://api.nomba.com`

#### Tags

- Cross-Border Payments
- Payouts
- Foreign Exchange
- Stablecoins
- Remittance

#### Properties

- [Documentation](https://developer.nomba.com/docs/products/global-payout/introduction)
- [OpenAPI](openapi/nomba-global-payout-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nomba-global-payout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-global-payout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nomba Checkout SDK

The Nomba Checkout SDK provides pre-built plugins and client libraries for integrating Nomba payment acceptance into websites and mobile applications. It includes an iOS SDK and e-commerce plugins such as a WooCommerce gateway for WordPress. The SDK supports Visa, Verve, and Mastercard payments along with USSD, bank transfers, and Nomba QR, enabling merchants to quickly add payment capabilities without building a custom checkout flow.

- **Human URL:** [https://developer.nomba.com/plugins-and-sdk/overview](https://developer.nomba.com/plugins-and-sdk/overview)
- **Base URL:** `https://api.nomba.com`

#### Tags

- SDK
- Checkout
- Plugins
- E-Commerce

#### Properties

- [Documentation](https://developer.nomba.com/plugins-and-sdk/overview)
- [Postman Collection](collections/nomba-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nomba-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nomba-charge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-charge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nomba-global-payout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-global-payout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nomba-online-checkout.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-online-checkout.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nomba-transactions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-transactions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nomba-transfers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-transfers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nomba-virtual-accounts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nomba-virtual-accounts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/nombahq)
- [Website](https://nomba.com)
- [Developer  Portal](https://developer.nomba.com)
- [Blog](https://nomba-developers.hashnode.dev)
- [AsyncAPI](asyncapi/nomba-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/nomba-webhook-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/nomba-virtual-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/nomba-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/nomba-checkout-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/nomba-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [L L Ms Txt](https://developer.nomba.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
