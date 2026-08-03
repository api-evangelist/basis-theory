# Basis Theory (basis-theory)

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
