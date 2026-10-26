# Dagster (dagster)

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

Dagster is a data orchestration platform centered on software-defined assets with strong observability and testing support. It exposes a GraphQL API for programmatic interaction with Dagster instances and a REST API for reporting external asset materializations, checks, and observations from outside pipelines.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Data Engineering
- Data Orchestration
- Data Pipelines
- ETL
- Workflows
- Assets
- GraphQL

## Timestamps

- **Created:** 2026-03-03
- **Modified:** 2026-05-19

## APIs

### Dagster GraphQL API

The Dagster GraphQL API allows clients to interact with Dagster programmatically. It can be used to query information about Dagster runs, retrieve metadata about repositories, jobs, and ops, and launch runs. The GraphQL endpoint is served by the webserver at the /graphql route.

- **Human URL:** [https://docs.dagster.io/api/graphql](https://docs.dagster.io/api/graphql)

#### Tags

- Data Orchestration
- GraphQL
- Jobs
- Runs
- Workflows

#### Properties

- [Documentation](https://docs.dagster.io/api/graphql)
- [Graph Q L  Playground](https://docs.dagster.io/api/graphql)
- [Postman Collection](collections/dagster-external-assets-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dagster-external-assets-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dagster External Assets REST API

The Dagster External Assets REST API provides endpoints to report asset materializations, asset check evaluations, and asset observations for external assets back to Dagster. This allows you to notify Dagster that an external asset has been updated and include metadata about the event.

- **Human URL:** [https://docs.dagster.io/api/rest-apis/external-assets-rest-api](https://docs.dagster.io/api/rest-apis/external-assets-rest-api)

#### Tags

- Assets
- Data Orchestration
- Materializations
- Observations
- REST API

#### Properties

- [Documentation](https://docs.dagster.io/api/rest-apis/external-assets-rest-api)
- [OpenAPI](openapi/dagster-external-assets-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dagster-external-assets-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dagster-external-assets-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/asset-materialization.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/asset-check.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/asset-observation.json) — [JSON Schema](https://json-schema.org/specification)
- [Rules](rules/dagster-external-assets-rest-api-rules.yml)
- [Capabilities](capabilities/dagster-external-assets-rest-api-capabilities.yml)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/dagsterlabs)
- [Portal](https://dagster.cloud/)
- [Sign Up](https://dagster.cloud/signup)
- [Documentation](https://docs.dagster.io/)
- [API Reference](https://docs.dagster.io/api)
- [Getting Started](https://docs.dagster.io/getting-started/quickstart)
- [Blog](https://dagster.io/blog)
- [Changelog](https://docs.dagster.io/about/changelog)
- [Pricing](https://dagster.io/pricing)
- [Support](https://dagster.io/support)
- [Community](https://dagster.io/community)
- [Slack](https://dagster.io/slack)
- [GitHub Organization](https://github.com/dagster-io)
- [GitHub Repository](https://github.com/dagster-io/dagster)
- [Integrations](https://docs.dagster.io/integrations/libraries)
- [Python  S D K](https://pypi.org/project/dagster/)
- [Privacy Policy](https://dagster.io/privacy)
- [Terms of Service](https://dagster.io/terms)
- [Security](https://dagster.io/security)
- [About](https://dagster.io/company/about-us)
- [Contact](https://dagster.io/contact)
- [JSON-LD](json-ld/dagster-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/dagster-vocabulary.yml)
- [L L Ms Txt](https://docs.dagster.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
