# Consumer Financial Protection Bureau (consumer-financial-protection-bureau)

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
