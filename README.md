# Aloha POS (aloha-pos)

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

Aloha POS is a restaurant point-of-sale platform from NCR Voyix. The NCR Voyix Developer Experience exposes APIs for Aloha (cloud and on-premise) covering site, store, menu, order, payment, and reporting integrations as part of the broader NCR Voyix Commerce Platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aloha-pos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aloha-pos/refs/heads/main/apis.yml)

## Tags

- POS
- Restaurant
- Hospitality
- NCR

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-06-02

## APIs

### NCR Voyix Commerce Platform APIs (Aloha)

REST APIs for Aloha POS (Aloha Cloud, Aloha Essentials) via the NCR Voyix Developer Experience (Business Services Platform). Covers Site provisioning, Catalog item and item-price management, Menu details, Order creation/lookup, Security, and Provisioning services. Requests are signed with HMAC (SHA-512) AccessKey authentication and scoped with nep-organization and nep-enterprise-unit headers against api.ncr.com (production) / gateway-staging.ncrcloud.com (staging).

- **Human URL:** [https://developer.ncrvoyix.com/](https://developer.ncrvoyix.com/)
- **Base URL:** `https://api.ncr.com`

#### Tags

- REST
- Restaurant
- POS
- Catalog
- Order
- Menu
- Site

#### Properties

- [Documentation](https://developer.ncrvoyix.com/)
- [OpenAPI](openapi/ncr-voyix-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ncr-voyix-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncr-voyix-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://developer.ncrvoyix.com/portals/dev-portal/help-center/documentation/getting-started-with-ncr-apis)
- [Code Examples](https://github.com/NCRVoyix-Corporation/sample-app-burgers)
- [Code Examples](https://github.com/NCRVoyix-Corporation/ncr-retail-demo)
- [Code Examples](https://github.com/NCRVoyix-Corporation/ncr-bsp-hmac)

### Aloha Cloud APIs

Aloha Cloud-specific endpoints including the In-Store API server (gRPC, default port 50051, 127.0.0.1) for local POS connectivity and the Business Services Layer (BSL) Order Service for routing online/third-party orders into a store's local instance. Used for menu, orders, employees, and payments.

- **Human URL:** [https://developer.ncrvoyix.com/portals/dev-portal/api-explorer/details/2021/how-to](https://developer.ncrvoyix.com/portals/dev-portal/api-explorer/details/2021/how-to)

#### Tags

- REST
- Restaurant
- Cloud
- InStore

#### Properties

- [Documentation](https://developer.ncrvoyix.com/portals/dev-portal/api-explorer/details/2021/how-to)
- [Postman Collection](collections/ncr-voyix-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncr-voyix-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.ncrvoyix.com/restaurants/aloha-cloud)
- [Developer](https://developer.ncrvoyix.com/)
- [Documentation](https://docs.ncrvoyix.com/restaurant/aloha-pos)
- [GitHub Organization](https://github.com/NCRVoyix-Corporation)
- [A P I Explorer](https://developer.ncrvoyix.com/portals/dev-portal/api-explorer)
- [Authentication](https://github.com/NCRVoyix-Corporation/ncr-bsp-hmac)
- [Rules](rules/ncr-voyix-platform-rules.yml)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/aloha-pos-ncr-voyix-platform-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/aloha-pos-vocabulary.yml)
- [Plans](plans/aloha-pos-plans-pricing.yml)
- [Rate Limits](rate-limits/aloha-pos-rate-limits.yml)
- [Fin Ops](finops/aloha-pos-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
