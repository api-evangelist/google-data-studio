# Google Data Studio (google-data-studio)

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

Google Data Studio, now rebranded as Looker Studio, is a free data visualization and business intelligence tool from Google that transforms data into customizable, shareable dashboards and reports. It connects to a wide range of data sources and supports community connectors and visualizations for extensibility.

**APIs.json:** [https://lookerstudio.google.com](https://lookerstudio.google.com)

## Scope

- **Type:** Index

## Tags

- Analytics
- Business Intelligence
- Dashboards
- Data
- Reporting
- Visualization

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Google Data Studio API

The Looker Studio API enables programmatic management of Looker Studio assets, including searching for assets and managing permissions within Google Workspace or Cloud Identity organizations.

- **Human URL:** [https://developers.google.com/looker-studio/integrate/api](https://developers.google.com/looker-studio/integrate/api)
- **Base URL:** `https://datastudio.googleapis.com`

#### Tags

- Assets
- Data Sources
- Permissions
- Reports

#### Properties

- [Documentation](https://developers.google.com/looker-studio/integrate/api)
- [OpenAPI](openapi/google-data-studio-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/google-data-studio-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-data-studio-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://datastudio.googleapis.com/$discovery/rest?version=v1) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Reference](https://developers.google.com/looker-studio/integrate/api/reference)
- [Authentication](https://developers.google.com/looker-studio/integrate/api)
- [Changelog](https://developers.google.com/looker-studio/integrate/api/changelog)

### Looker Studio Linking API

The Linking API provides a reliable interface to configure and forward users directly to a pre-configured Looker Studio report via URL parameters, enabling one-click report creation experiences.

- **Human URL:** [https://developers.google.com/looker-studio/integrate/linking-api](https://developers.google.com/looker-studio/integrate/linking-api)

#### Tags

- Embedding
- Integration
- Linking
- Reports

#### Properties

- [Documentation](https://developers.google.com/looker-studio/integrate/linking-api)
- [OpenAPI](openapi/google-data-studio-linking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/google-data-studio-linking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-data-studio-linking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Looker Studio Community Connectors

Community Connectors enable direct connections from Looker Studio to any internet-accessible data source using Google Apps Script. Developers implement getAuthType, getConfig, getSchema, and getData functions to build custom connectors.

- **Human URL:** [https://developers.google.com/looker-studio/connector](https://developers.google.com/looker-studio/connector)

#### Tags

- Apps Script
- Connectors
- Data Sources
- Integration

#### Properties

- [Documentation](https://developers.google.com/looker-studio/connector)
- [Reference](https://developers.google.com/looker-studio/connector/reference)
- [Getting Started](https://developers.google.com/looker-studio/connector/build)
- [Changelog](https://developers.google.com/looker-studio/connector/changelog)
- [Codelabs](https://codelabs.developers.google.com/codelabs/community-connectors)
- [Postman Collection](collections/google-data-studio-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-data-studio-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/google-data-studio-linking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-data-studio-linking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Looker Studio Community Visualizations

Community Visualizations allow developers to build and share custom JavaScript visualizations in Looker Studio using the dscc helper library, extending the platform with custom chart types and visual components.

- **Human URL:** [https://developers.google.com/looker-studio/visualization](https://developers.google.com/looker-studio/visualization)

#### Tags

- Charts
- Custom Components
- JavaScript
- Visualizations

#### Properties

- [Documentation](https://developers.google.com/looker-studio/visualization)
- [Getting Started](https://developers.google.com/looker-studio/visualization/get-started)
- [Reference](https://developers.google.com/looker-studio/visualization/library-reference)
- [Libraries](https://developers.google.com/looker-studio/visualization/library)
- [Codelabs](https://codelabs.developers.google.com/codelabs/community-visualization)
- [Open  Source](https://developers.google.com/looker-studio/visualization/open-source)
- [Postman Collection](collections/google-data-studio-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-data-studio-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/google-data-studio-linking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-data-studio-linking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [OpenAPI](openapi/google-data-studio-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/google-data-studio-linking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N  Schema](json-schema/google-data-studio-asset-schema.json)
- [J S O N  Schema](json-schema/google-data-studio-permissions-schema.json)
- [J S O N  Schema](json-schema/google-data-studio-connector-schema.json)
- [J S O N  Schema](json-schema/google-data-studio-report-schema.json)
- [J S O N  Schema](json-schema/google-data-studio-datasource-schema.json)
- [JSON-LD](json-ld/google-data-studio-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Portal](https://lookerstudio.google.com)
- [Documentation](https://docs.cloud.google.com/looker/docs/studio)
- [Getting Started](https://support.google.com/looker-studio/answer/6283323)
- [Authentication](https://developers.google.com/looker-studio/integrate/api)
- [Blog](https://cloud.google.com/blog/products/data-analytics)
- [Status Page](https://status.cloud.google.com/)
- [Support](https://support.google.com/looker-studio)
- [Terms of Service](https://support.google.com/looker-studio/answer/7019158)
- [Privacy Policy](https://policies.google.com/privacy)
- [GitHub Organization](https://github.com/looker-open-source)
- [Community](https://www.googlecloudcommunity.com/gc/Looker-Studio/bd-p/looker-studio)
- [Gallery](https://lookerstudio.google.com/gallery)
- [Changelog](https://docs.cloud.google.com/looker-studio/docs/release-notes)
- [Pricing](https://cloud.google.com/looker/pricing)
- [Website](https://cloud.google.com/looker-studio)
- [Login](https://lookerstudio.google.com/?requirelogin=1)
- [Sign Up](https://lookerstudio.google.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
