# Consumer Financial Protection Bureau (consumer-financial-protection-bureau)

The Consumer Financial Protection Bureau (CFPB) is the U.S. federal agency that supervises banks, lenders, and other financial companies, enforces federal consumer financial laws, and publishes large public datasets via open APIs. The CFPB Open Tech program publishes the Consumer Complaint Database (CCDB) search API and the HMDA Platform's Data Browser and Institutions APIs at ffiec.cfpb.gov, all unauthenticated and CC0-licensed for public use.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/apis.yml)

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
- **Modified:** 2026-04-29

## APIs

### Consumer Complaint Database API
Public REST + JSON search API for the Consumer Complaint Database, a daily-updated record of complaints submitted by U.S. consumers about financial products and services. Supports full-text search, complaint detail lookups, faceted aggregations, autocomplete, geo breakdowns by state, and CSV export. No API key required.

**Human URL:** [https://www.consumerfinance.gov/data-research/consumer-complaints/](https://www.consumerfinance.gov/data-research/consumer-complaints/)

**Base URL:** `https://www.consumerfinance.gov/data-research/consumer-complaints/search/api/v1`

#### Properties

- [Documentation](https://cfpb.github.io/api/ccdb/)
- [GitHub Repository](https://github.com/cfpb/ccdb5-api)
- [OpenAPI](openapi/cfpb-ccdb-openapi.yml)

### HMDA Data Browser API
The HMDA Data Browser API exposes Home Mortgage Disclosure Act submission data with both nationwide and filtered (LEI, state, county, MSA/MD) aggregation reports as JSON, plus raw CSV streams and an HMDA filer lookup. Used by researchers, fair-lending analysts, and journalists.

**Human URL:** [https://ffiec.cfpb.gov/documentation/api/data-browser/](https://ffiec.cfpb.gov/documentation/api/data-browser/)

**Base URL:** `https://ffiec.cfpb.gov/v2/data-browser-api`

#### Properties

- [Documentation](https://ffiec.cfpb.gov/documentation/api/data-browser/)
- [OpenAPI](openapi/cfpb-hmda-data-browser-openapi.yml)

### HMDA Institutions API
Returns the financial institutions registered to file HMDA data with the CFPB, keyed by year and Legal Entity Identifier (LEI). Used by filers and researchers to confirm filer identifiers, registration status, and contact info.

**Human URL:** [https://ffiec.cfpb.gov/documentation/api/institutions-api/](https://ffiec.cfpb.gov/documentation/api/institutions-api/)

**Base URL:** `https://ffiec.cfpb.gov/v2`

#### Properties

- [Documentation](https://ffiec.cfpb.gov/documentation/api/institutions-api/)
- [OpenAPI](openapi/cfpb-hmda-institutions-openapi.yml)

## Common Properties

- [Website](https://www.consumerfinance.gov/)
- [Open Tech](https://cfpb.github.io/)
- [GitHub Organization](https://github.com/cfpb)
- [Data and Research](https://www.consumerfinance.gov/data-research/)
- [Consumer Complaints](https://www.consumerfinance.gov/data-research/consumer-complaints/)
- [HMDA Platform](https://ffiec.cfpb.gov/)
- [Privacy Policy](https://www.consumerfinance.gov/privacy/)
- [Terms of Service](https://www.consumerfinance.gov/privacy/website-privacy-policy/)
- [JSON-LD Context](json-ld/consumer-financial-protection-bureau-context.jsonld)
- [Complaint JSON Schema](json-schema/cfpb-complaint-schema.json)
- [HMDA Institution JSON Schema](json-schema/cfpb-hmda-institution-schema.json)
- [Spectral Ruleset](rules/consumer-financial-protection-bureau-rules.yml)
- [Naftiko Capabilities](capabilities/consumer-financial-protection-bureau-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
