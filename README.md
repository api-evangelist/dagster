# Dagster (dagster)

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
