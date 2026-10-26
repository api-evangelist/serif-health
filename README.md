# Serif Health (serif-health)

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
