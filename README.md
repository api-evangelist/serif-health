# Serif Health (serif-health)

Serif Health turns federal hospital and payer price-transparency disclosures (machine-readable files) into normalized, decision-ready negotiated-rate data. Its REST APIs let teams query negotiated reimbursement rates and rate distributions by CPT/DRG code, payer, provider, and geography, search for in-network providers, and pull custom datasets and extracts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/serif-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/serif-health/refs/heads/main/apis.yml)

## Tags

- Healthcare
- Price Transparency
- Negotiated Rates
- Payer
- Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Serif Health Negotiated Rates API

Query payer-negotiated reimbursement rates for an individual procedure code (CPT/DRG), filtered by region, tier, site of service, and payer. Returns per-payer rates derived from machine-readable files (MRFs).

- **Human URL:** [https://www.serifhealth.com/platform/products/apis](https://www.serifhealth.com/platform/products/apis)
- **Base URL:** `https://pricing-api.serifhealth.com`

#### Tags

- Negotiated Rates
- Pricing
- Price Transparency

#### Properties

- [Documentation](https://docs.serifhealth.com)
- [API Reference](https://www.serifhealth.com/blog/announcing-our-payer-price-transparency-analytics-portal-api)
- [OpenAPI](openapi/serif-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/serif-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/serif-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Serif Health Rate Distributions API

Return percentile rate distributions (5th-95th) for a procedure code, filtered by region, tier, site, payer, and weighting (NPI or EIN) for benchmarking against the market.

- **Human URL:** [https://www.serifhealth.com/platform/products/apis](https://www.serifhealth.com/platform/products/apis)
- **Base URL:** `https://pricing-api.serifhealth.com`

#### Tags

- Rate Search
- Distributions
- Benchmarks

#### Properties

- [Documentation](https://docs.serifhealth.com)
- [API Reference](https://www.serifhealth.com/blog/announcing-our-payer-price-transparency-analytics-portal-api)
- [OpenAPI](openapi/serif-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/serif-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/serif-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Serif Health Find Care API

Find the right provider by procedure, geography, and payer network - surfacing cost-aware, in-network provider options to power care-navigation tools.

- **Human URL:** [https://www.serifhealth.com/platform/products/apis](https://www.serifhealth.com/platform/products/apis)
- **Base URL:** `https://pricing-api.serifhealth.com`

#### Tags

- Find Care
- Provider Search
- Care Navigation

#### Properties

- [Documentation](https://docs.serifhealth.com)
- [Documentation](https://www.serifhealth.com/blog/announcing-the-serif-health-find-care-api-seamless-provider-search-via-price-transparency)
- [OpenAPI](openapi/serif-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Serif Health Provider Directory API

Determine in- vs out-of-network status across payers and perform NPI/EIN relationship crosswalks to understand network structure and decode MRF postings.

- **Human URL:** [https://www.serifhealth.com/platform/products/apis](https://www.serifhealth.com/platform/products/apis)
- **Base URL:** `https://pricing-api.serifhealth.com`

#### Tags

- Provider Directory
- Network Status
- NPI EIN Crosswalk

#### Properties

- [Documentation](https://docs.serifhealth.com)
- [OpenAPI](openapi/serif-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Serif Health Datasets & Extracts

Custom data pulls and extracts for specific EINs, NPIs, or taxonomy codes, delivered in common formats and optionally indexed back into the API by request.

- **Human URL:** [https://www.serifhealth.com/platform/products/data-delivery](https://www.serifhealth.com/platform/products/data-delivery)
- **Base URL:** `https://pricing-api.serifhealth.com`

#### Tags

- Datasets
- Extracts
- Data Delivery

#### Properties

- [Documentation](https://www.serifhealth.com/platform/products/data-delivery)

### Serif Health Payer Inventory

Live public inventory of 200+ payers with network-quality scoring, updated monthly, exposing data coverage and freshness across payer machine-readable files.

- **Human URL:** [https://www.serifhealth.com/blog/announcing-our-live-payer-inventory-real-time-transparency-from-serif-health](https://www.serifhealth.com/blog/announcing-our-live-payer-inventory-real-time-transparency-from-serif-health)
- **Base URL:** `https://www.serifhealth.com`

#### Tags

- Payer Inventory
- Coverage
- Benchmarks

#### Properties

- [Documentation](https://www.serifhealth.com/blog/announcing-our-live-payer-inventory-real-time-transparency-from-serif-health)

## Common Properties

- [GitHub Organization](https://github.com/serif-health)
- [LinkedIn](https://www.linkedin.com/company/serif-health)
- [Website](https://www.serifhealth.com)
- [Documentation](https://docs.serifhealth.com)
- [Plans](plans/serif-health-plans-pricing.yml)
- [Rate Limits](rate-limits/serif-health-rate-limits.yml)
- [Fin Ops](finops/serif-health-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
