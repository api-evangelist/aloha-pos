# Aloha POS (aloha-pos)
Aloha POS is a restaurant point-of-sale platform from NCR Voyix. The NCR Voyix Developer Experience exposes APIs for Aloha (cloud and on-premise) covering site, store, menu, order, payment, and reporting integrations as part of the broader NCR Voyix Commerce Platform.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/aloha-pos/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - POS, Restaurant, Hospitality, NCR

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-06-02

## APIs

### NCR Voyix Commerce Platform APIs (Aloha)
REST APIs for Aloha POS (Aloha Cloud, Aloha Essentials) via the NCR Voyix Developer Experience (Business Services Platform). Covers Site provisioning, Catalog item and item-price management, Menu details, Order creation/lookup, Security, and Provisioning services. Requests are signed with HMAC (SHA-512) AccessKey authentication and scoped with nep-organization and nep-enterprise-unit headers against api.ncr.com (production) / gateway-staging.ncrcloud.com (staging).

**Human URL:** [https://developer.ncrvoyix.com/](https://developer.ncrvoyix.com/)

**Base URL:** `https://api.ncr.com`

#### Tags:

 - REST, Restaurant, POS, Catalog, Order, Menu, Site

#### Properties

- [Documentation](https://developer.ncrvoyix.com/)
- [OpenAPI](openapi/ncr-voyix-platform-openapi.yml)
- [GettingStarted](https://developer.ncrvoyix.com/portals/dev-portal/help-center/documentation/getting-started-with-ncr-apis)
- [CodeExamples — Hospitality Sample App (Python)](https://github.com/NCRVoyix-Corporation/sample-app-burgers)
- [CodeExamples — Retail Demo App](https://github.com/NCRVoyix-Corporation/ncr-retail-demo)
- [CodeExamples — BSP HMAC Authentication Examples](https://github.com/NCRVoyix-Corporation/ncr-bsp-hmac)
- [NaftikoCapability](capabilities/ncr-voyix-platform-catalog.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-platform-menu.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-platform-order.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-platform-site.yaml)

### Aloha Cloud APIs
Aloha Cloud-specific endpoints including the In-Store API server (gRPC, default port 50051, 127.0.0.1) for local POS connectivity and the Business Services Layer (BSL) Order Service for routing online/third-party orders into a store's local instance. Used for menu, orders, employees, and payments.

**Human URL:** [https://developer.ncrvoyix.com/portals/dev-portal/api-explorer/details/2021/how-to](https://developer.ncrvoyix.com/portals/dev-portal/api-explorer/details/2021/how-to)

#### Tags:

 - REST, Restaurant, Cloud, InStore

#### Properties

- [Documentation](https://developer.ncrvoyix.com/portals/dev-portal/api-explorer/details/2021/how-to)

## Common Properties

- [Website](https://www.ncrvoyix.com/restaurants/aloha-cloud)
- [Developer](https://developer.ncrvoyix.com/)
- [Documentation](https://docs.ncrvoyix.com/restaurant/aloha-pos)
- [GitHubOrganization](https://github.com/NCRVoyix-Corporation)
- [APIExplorer](https://developer.ncrvoyix.com/portals/dev-portal/api-explorer)
- [Authentication — HMAC (AccessKey) Authentication](https://github.com/NCRVoyix-Corporation/ncr-bsp-hmac)
- [Rules](rules/ncr-voyix-platform-rules.yml)
- [JSONSchema](json-schema/)
- [JSONLD](json-ld/aloha-pos-ncr-voyix-platform-context.jsonld)
- [Vocabulary](vocabulary/aloha-pos-vocabulary.yml)
- [Plans](plans/aloha-pos-plans-pricing.yml)
- [RateLimits](rate-limits/aloha-pos-rate-limits.yml)
- [FinOps](finops/aloha-pos-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [NCR Voyix Commerce Platform APIs (Aloha)](openapi/ncr-voyix-platform-openapi.yml) — 14 operations across Catalog, Menu, Order, and Site

### JSON Schema

- [Item](json-schema/ncr-voyix-platform-item-schema.json)
- [Item Price](json-schema/ncr-voyix-platform-item-price-schema.json)
- [Site](json-schema/ncr-voyix-platform-site-schema.json)
- [Order](json-schema/ncr-voyix-platform-order-schema.json)

### JSON Structure

- [Item](json-structure/ncr-voyix-platform-item-structure.json)
- [Item Price](json-structure/ncr-voyix-platform-item-price-structure.json)
- [Site](json-structure/ncr-voyix-platform-site-structure.json)
- [Order](json-structure/ncr-voyix-platform-order-structure.json)

### JSON-LD

- [NCR Voyix Platform Context](json-ld/aloha-pos-ncr-voyix-platform-context.jsonld)

### Examples

- [Create Order](examples/ncr-voyix-platform-create-order-example.json)
- [Create Or Update Catalog Item](examples/ncr-voyix-platform-put-catalog-item-example.json)
- [Create Or Update Item Price](examples/ncr-voyix-platform-put-item-price-example.json)
- [Create Site](examples/ncr-voyix-platform-create-site-example.json)

## Capabilities

Naftiko capabilities organized as self-contained per-tag definitions, each exposing both a REST and an MCP adapter.

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Catalog](capabilities/ncr-voyix-platform-catalog.yaml) | NCR Voyix Commerce Platform APIs (Aloha) | 6 | Menu Manager / Integrator |
| [Menu](capabilities/ncr-voyix-platform-menu.yaml) | NCR Voyix Commerce Platform APIs (Aloha) | 1 | Online Ordering Partner |
| [Order](capabilities/ncr-voyix-platform-order.yaml) | NCR Voyix Commerce Platform APIs (Aloha) | 3 | Online Ordering Partner / Integrator |
| [Site](capabilities/ncr-voyix-platform-site.yaml) | NCR Voyix Commerce Platform APIs (Aloha) | 4 | Operations Manager / Integrator |

## Vocabulary

- [Aloha POS (NCR Voyix) Vocabulary](vocabulary/aloha-pos-vocabulary.yml) — Unified taxonomy mapping 5 resources, 7 actions, 4 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [NCR Voyix Platform Rules](rules/ncr-voyix-platform-rules.yml) — 29 rules across 13 categories enforcing NCR Voyix API conventions

## Commercial

- [Plans](plans/aloha-pos-plans-pricing.yml) — per-location SaaS via NCR Voyix (reconciled: false)
- [RateLimits](rate-limits/aloha-pos-rate-limits.yml) — limits not publicly documented (reconciled: false)
- [FinOps](finops/aloha-pos-finops.yml) — FOCUS-aligned per-location SaaS (reconciled: false)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
