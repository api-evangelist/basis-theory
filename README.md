# Basis Theory (basis-theory)

Basis Theory is a PCI Level 1 compliant tokenization and data vault platform. Its API-first product lets developers tokenize, store, and use sensitive data - cardholder data, PII, PHI, and bank account numbers - without that data ever touching their own systems, using tokens, a detokenizing Proxy, serverless Reactors, and 3D Secure authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/basis-theory/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/basis-theory/refs/heads/main/apis.yml)

## Tags

- Tokenization
- Data Vault
- PCI Compliance
- Payments
- Security

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Basis Theory Tokens API

Create, retrieve, search, update, and delete tokens that securely vault sensitive data with masking, metadata, search indexes, fingerprinting, and token intents.

- **Human URL:** [https://developers.basistheory.com/docs/api/tokens](https://developers.basistheory.com/docs/api/tokens)
- **Base URL:** `https://api.basistheory.com`

#### Tags

- Tokens
- Tokenization
- Data Vault

#### Properties

- [Documentation](https://developers.basistheory.com/docs/api/tokens)
- [API Reference](https://developers.basistheory.com/docs/api/tokens/token-object)
- [OpenAPI](openapi/basis-theory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basis-theory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basis-theory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basis Theory Tokenize / Detokenize API

Batch tokenization and detokenization endpoints that vault arbitrary object graphs into tokens and resolve token identifiers back to plaintext for authorized applications.

- **Human URL:** [https://developers.basistheory.com/docs/api/tokens/tokenize](https://developers.basistheory.com/docs/api/tokens/tokenize)
- **Base URL:** `https://api.basistheory.com`

#### Tags

- Tokenize
- Detokenize
- Batch

#### Properties

- [Documentation](https://developers.basistheory.com/docs/api/tokens/tokenize)
- [API Reference](https://developers.basistheory.com/docs/api/tokens/detokenize)
- [OpenAPI](openapi/basis-theory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basis-theory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basis-theory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basis Theory Applications API

Manage Applications (API credentials) with fine-grained permissions and access rules - the public, private, management, and expiring application types that authenticate every call to the platform.

- **Human URL:** [https://developers.basistheory.com/docs/api/applications](https://developers.basistheory.com/docs/api/applications)
- **Base URL:** `https://api.basistheory.com`

#### Tags

- Applications
- API Keys
- Permissions

#### Properties

- [Documentation](https://developers.basistheory.com/docs/api/applications)
- [API Reference](https://developers.basistheory.com/docs/api/applications/application-object)
- [OpenAPI](openapi/basis-theory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basis-theory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basis-theory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basis Theory Proxy API

Manage pre-configured proxies and invoke the Proxy (pre-configured or ephemeral) to detokenize data inline and forward plaintext to a trusted third-party destination over HTTP without storing it on your servers.

- **Human URL:** [https://developers.basistheory.com/docs/api/proxies](https://developers.basistheory.com/docs/api/proxies)
- **Base URL:** `https://api.basistheory.com`

#### Tags

- Proxy
- Detokenize
- Outbound

#### Properties

- [Documentation](https://developers.basistheory.com/docs/api/proxies)
- [API Reference](https://developers.basistheory.com/docs/api/proxies/pre-configured-proxies)
- [OpenAPI](openapi/basis-theory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basis-theory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basis-theory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basis Theory Reactors API

Create and manage serverless Reactors - sandboxed JavaScript functions that detokenize tokens and run custom logic against third-party services - and invoke them synchronously or asynchronously.

- **Human URL:** [https://developers.basistheory.com/docs/api/reactors](https://developers.basistheory.com/docs/api/reactors)
- **Base URL:** `https://api.basistheory.com`

#### Tags

- Reactors
- Serverless
- Detokenize

#### Properties

- [Documentation](https://developers.basistheory.com/docs/api/reactors)
- [API Reference](https://developers.basistheory.com/docs/api/reactors/reactor-object)
- [OpenAPI](openapi/basis-theory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basis-theory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basis-theory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basis Theory 3D Secure API

Create 3D Secure sessions against tokenized cards, run frictionless or challenge authentication, and retrieve authentication values, ECI, and liability-shift results for payment flows.

- **Human URL:** [https://developers.basistheory.com/docs/api/3ds](https://developers.basistheory.com/docs/api/3ds)
- **Base URL:** `https://api.basistheory.com`

#### Tags

- 3DS
- Authentication
- Payments

#### Properties

- [Documentation](https://developers.basistheory.com/docs/api/3ds)
- [API Reference](https://developers.basistheory.com/docs/api/3ds/sessions)
- [OpenAPI](openapi/basis-theory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basis-theory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basis-theory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basis Theory Tenants API

Read and manage the current tenant, retrieve monthly active token usage reports, manage the security contact, and list audit logs of platform activity.

- **Human URL:** [https://developers.basistheory.com/docs/api/tenants](https://developers.basistheory.com/docs/api/tenants)
- **Base URL:** `https://api.basistheory.com`

#### Tags

- Tenants
- Usage
- Logs

#### Properties

- [Documentation](https://developers.basistheory.com/docs/api/tenants)
- [API Reference](https://developers.basistheory.com/docs/api/logs)
- [OpenAPI](openapi/basis-theory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basis-theory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basis-theory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Basis Theory Webhooks API

Register webhook URLs, subscribe to platform event types, and manage event subscriptions so downstream systems are notified of token, reactor, and other lifecycle events.

- **Human URL:** [https://developers.basistheory.com/docs/api/webhooks](https://developers.basistheory.com/docs/api/webhooks)
- **Base URL:** `https://api.basistheory.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.basistheory.com/docs/api/webhooks)
- [API Reference](https://developers.basistheory.com/docs/api/webhooks/api)
- [OpenAPI](openapi/basis-theory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/basis-theory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/basis-theory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Basis-Theory)
- [LinkedIn](https://www.linkedin.com/company/basis-theory)
- [Website](https://basistheory.com/)
- [Documentation](https://developers.basistheory.com/docs)
- [Plans](plans/basis-theory-plans-pricing.yml)
- [Rate Limits](rate-limits/basis-theory-rate-limits.yml)
- [Fin Ops](finops/basis-theory-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
