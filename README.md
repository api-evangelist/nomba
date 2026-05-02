# Nomba (nomba)
Nomba is a Nigerian fintech platform that provides payment infrastructure for businesses, offering APIs for payment acceptance, transfers, virtual accounts, and cross-border payouts. Their developer platform enables merchants and platforms to integrate card payments, bank transfers, USSD, and QR code payments into applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Payments, Fintech, Banking, Transfers, Virtual Accounts, Checkout, Cross-Border Payments, Cards

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-04-28

## APIs

### Nomba Authentication API
The Nomba Authentication API provides OAuth2-based authentication for accessing all Nomba API endpoints. It supports two authentication methods: Client-Credentials for server-to-server integrations and PKCE (Proof Key for Code Exchange) for client-side applications. Developers obtain HTTP bearer tokens that are used to authorize subsequent API calls across the Nomba platform.

**Human URL:** [https://developer.nomba.com/nomba-api-reference/authenticate/obtain-access-token](https://developer.nomba.com/nomba-api-reference/authenticate/obtain-access-token)


#### Tags:

 - Authentication, OAuth2, Security

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/authenticate/obtain-access-token)
- [OpenAPI](openapi/nomba-authentication-openapi.yml)

### Nomba Accounts API
The Nomba Accounts API enables developers to manage business accounts on the Nomba platform. It provides endpoints for retrieving account details, fetching terminals assigned to an account, and managing account-level configurations. This API serves as the foundation for account management operations within the Nomba ecosystem.

**Human URL:** [https://developer.nomba.com/nomba-api-reference/accounts/fetch-terminals-assigned-to-an-account](https://developer.nomba.com/nomba-api-reference/accounts/fetch-terminals-assigned-to-an-account)


#### Tags:

 - Accounts, Financial Services, Terminals

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/accounts/fetch-terminals-assigned-to-an-account)
- [OpenAPI](openapi/nomba-accounts-openapi.yml)

### Nomba Virtual Accounts API
The Nomba Virtual Accounts API allows developers to create and manage virtual bank accounts for receiving payments. There is no fixed limit to the number of virtual accounts that can be created for customers. The API supports creating, expiring, and managing virtual accounts, enabling businesses to collect payments via bank transfers with unique account numbers assigned to individual customers or transactions.

**Human URL:** [https://developer.nomba.com/nomba-api-reference/virtual-accounts/create-virtual-account](https://developer.nomba.com/nomba-api-reference/virtual-accounts/create-virtual-account)


#### Tags:

 - Virtual Accounts, Payments, Collections

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/virtual-accounts/create-virtual-account)
- [OpenAPI](openapi/nomba-virtual-accounts-openapi.yml)

### Nomba Transfers API
The Nomba Transfers API provides endpoints for initiating and managing fund transfers. Developers can look up bank codes and names, verify account details, and initiate transfers to Nigerian bank accounts. The API supports domestic money transfers and provides the necessary bank metadata for building payment flows within applications.

**Human URL:** [https://developer.nomba.com/nomba-api-reference/transfers/fetch-bank-codes-and-names](https://developer.nomba.com/nomba-api-reference/transfers/fetch-bank-codes-and-names)


#### Tags:

 - Transfers, Payments, Banking

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/transfers/fetch-bank-codes-and-names)
- [OpenAPI](openapi/nomba-transfers-openapi.yml)

### Nomba Online Checkout API
The Nomba Online Checkout API enables developers to create checkout orders and process payments through multiple channels. It supports Visa, Verve, and Mastercard payments, as well as USSD, bank transfers, and Nomba QR payments. The API includes tokenized card payment capabilities, allowing merchants to charge returning customers without requiring them to re-enter card details.

**Human URL:** [https://developer.nomba.com/nomba-api-reference/online-checkout/create-an-online-checkout-order](https://developer.nomba.com/nomba-api-reference/online-checkout/create-an-online-checkout-order)


#### Tags:

 - Checkout, Payments, E-Commerce, Cards

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/online-checkout/create-an-online-checkout-order)
- [OpenAPI](openapi/nomba-online-checkout-openapi.yml)

### Nomba Charge API
The Nomba Charge API provides direct card charging capabilities for developers building payment solutions. It supports OTP submission for card transactions, retrieval of user saved cards, and tokenized card charging. This API is designed for merchants and platforms that need programmatic control over the card payment flow, including handling 3D Secure authentication steps.

**Human URL:** [https://developer.nomba.com/nomba-api-reference/charge/submit-customer-card-otp](https://developer.nomba.com/nomba-api-reference/charge/submit-customer-card-otp)


#### Tags:

 - Payments, Cards, Tokenization

#### Properties

- [Documentation](https://developer.nomba.com/nomba-api-reference/charge/submit-customer-card-otp)
- [OpenAPI](openapi/nomba-charge-openapi.yml)

### Nomba Transactions API
The Nomba Transactions API allows developers to retrieve and manage transaction records. It provides endpoints for fetching account transaction history, querying transaction details, and processing refunds. This API is essential for building reporting dashboards, reconciliation tools, and transaction monitoring systems on top of the Nomba platform.

**Human URL:** [https://developer.nomba.com/products/transactions/fetch-account-transactions](https://developer.nomba.com/products/transactions/fetch-account-transactions)


#### Tags:

 - Transactions, Reporting, Financial Data

#### Properties

- [Documentation](https://developer.nomba.com/products/transactions/fetch-account-transactions)
- [OpenAPI](openapi/nomba-transactions-openapi.yml)

### Nomba Global Payout API
The Nomba Global Payout API is a single integration point that enables cross-border payment operators, remittance platforms, and fintechs to collect funds in Nigerian Naira or stablecoins (USDT/USDC) and trigger instant disbursements to the United Kingdom via Faster Payments, Europe via SEPA, Canada via Interac and bank transfer, and the Democratic Republic of Congo via Mobile Money. The API embeds FX sourcing and compliance directly into the technical layer, eliminating the need for operators to manage foreign exchange processes.

**Human URL:** [https://developer.nomba.com/docs/products/global-payout/introduction](https://developer.nomba.com/docs/products/global-payout/introduction)


#### Tags:

 - Cross-Border Payments, Payouts, Foreign Exchange, Stablecoins, Remittance

#### Properties

- [Documentation](https://developer.nomba.com/docs/products/global-payout/introduction)
- [OpenAPI](openapi/nomba-global-payout-openapi.yml)

### Nomba Checkout SDK
The Nomba Checkout SDK provides pre-built plugins and client libraries for integrating Nomba payment acceptance into websites and mobile applications. It includes an iOS SDK and e-commerce plugins such as a WooCommerce gateway for WordPress. The SDK supports Visa, Verve, and Mastercard payments along with USSD, bank transfers, and Nomba QR, enabling merchants to quickly add payment capabilities without building a custom checkout flow.

**Human URL:** [https://developer.nomba.com/plugins-and-sdk/overview](https://developer.nomba.com/plugins-and-sdk/overview)


#### Tags:

 - SDK, Checkout, Plugins, E-Commerce

#### Properties

- [Documentation](https://developer.nomba.com/plugins-and-sdk/overview)

## Common Properties

- [Website](https://nomba.com)
- [Developer Portal](https://developer.nomba.com)
- [Blog](https://nomba-developers.hashnode.dev)
- [AsyncAPI](asyncapi/nomba-webhooks-asyncapi.yml)
- [JSONSchema](json-schema/nomba-webhook-event-schema.json)
- [JSONSchema](json-schema/nomba-virtual-account-schema.json)
- [JSONSchema](json-schema/nomba-transaction-schema.json)
- [JSONSchema](json-schema/nomba-checkout-order-schema.json)
- [JSON-LD](json-ld/nomba-context.jsonld)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
