# Consumer Financial Protection Bureau (consumer-financial-protection-bureau)

The Consumer Financial Protection Bureau (CFPB) is the U.S. federal agency that supervises banks, lenders, and other financial companies, enforces federal consumer financial laws, and publishes large public datasets via open APIs. The CFPB Open Tech program publishes the Consumer Complaint Database (CCDB) search API and the HMDA Platform's Data Browser and Institutions APIs at ffiec.cfpb.gov, all unauthenticated and CC0-licensed for public use.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Banking
- Complaints
- Consumer Protection
- Federal Government
- Financial Services
- HMDA
- Mortgages
- Open Data

## Timestamps

- **Created:** 2024-11-25
- **Modified:** 2026-05-19

## APIs

### Consumer Complaint Database API

Public REST + JSON search API for the Consumer Complaint Database, a daily-updated record of complaints submitted by U.S. consumers about financial products and services. Supports full-text search, complaint detail lookups, faceted aggregations, autocomplete, geo breakdowns by state, and CSV export. No API key required.

- **Human URL:** [https://www.consumerfinance.gov/data-research/consumer-complaints/](https://www.consumerfinance.gov/data-research/consumer-complaints/)
- **Base URL:** `https://www.consumerfinance.gov/data-research/consumer-complaints/search/api/v1`

#### Tags

- Complaints
- Consumer Protection
- Open Data
- Search

#### Properties

- [Documentation](https://cfpb.github.io/api/ccdb/)
- [GitHub Repository](https://github.com/cfpb/ccdb5-api)
- [OpenAPI](openapi/cfpb-ccdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cfpb-ccdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cfpb-ccdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HMDA Data Browser API

The HMDA Data Browser API exposes Home Mortgage Disclosure Act submission data with both nationwide and filtered (LEI, state, county, MSA/MD) aggregation reports as JSON, plus raw CSV streams and an HMDA filer lookup. Used by researchers, fair-lending analysts, and journalists.

- **Human URL:** [https://ffiec.cfpb.gov/documentation/api/data-browser/](https://ffiec.cfpb.gov/documentation/api/data-browser/)
- **Base URL:** `https://ffiec.cfpb.gov/v2/data-browser-api`

#### Tags

- HMDA
- Mortgages
- Open Data

#### Properties

- [Documentation](https://ffiec.cfpb.gov/documentation/api/data-browser/)
- [OpenAPI](openapi/cfpb-hmda-data-browser-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cfpb-hmda-data-browser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cfpb-hmda-data-browser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HMDA Institutions API

Returns the financial institutions registered to file HMDA data with the CFPB, keyed by year and Legal Entity Identifier (LEI). Used by filers and researchers to confirm filer identifiers, registration status, and contact info.

- **Human URL:** [https://ffiec.cfpb.gov/documentation/api/institutions-api/](https://ffiec.cfpb.gov/documentation/api/institutions-api/)
- **Base URL:** `https://ffiec.cfpb.gov/v2`

#### Tags

- HMDA
- Institutions
- Open Data

#### Properties

- [Documentation](https://ffiec.cfpb.gov/documentation/api/institutions-api/)
- [OpenAPI](openapi/cfpb-hmda-institutions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cfpb-hmda-institutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cfpb-hmda-institutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/consumer-financial-protection-bureau)
- [Website](https://www.consumerfinance.gov/)
- [Open  Tech](https://cfpb.github.io/)
- [GitHub Organization](https://github.com/cfpb)
- [Data and  Research](https://www.consumerfinance.gov/data-research/)
- [Consumer  Complaints](https://www.consumerfinance.gov/data-research/consumer-complaints/)
- [H M D A  Platform](https://ffiec.cfpb.gov/)
- [Privacy Policy](https://www.consumerfinance.gov/privacy/)
- [Terms of Service](https://www.consumerfinance.gov/privacy/website-privacy-policy/)
- [JSON-LD](json-ld/consumer-financial-protection-bureau-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/cfpb-complaint-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cfpb-hmda-institution-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/consumer-financial-protection-bureau-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
