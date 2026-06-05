# Aloha POS (aloha-pos)

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
