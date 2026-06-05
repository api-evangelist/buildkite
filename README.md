# Buildkite (buildkite)

Buildkite is a CI/CD platform with self-hosted agents and a hosted control plane. The platform exposes a REST API, a GraphQL API and an Agent API used by buildkite-agent. Resources include organizations, pipelines, pipeline templates, builds, jobs, agents, clusters, queues, teams, rules, artifacts, annotations, and access tokens. Test Engine adds test execution and analytics endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/buildkite/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/buildkite/refs/heads/main/apis.yml)

## Tags

- DevOps
- CI/CD
- Pipelines
- Agents
- Self-Hosted
- GraphQL
- Test Engine

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Buildkite REST API

JSON over HTTPS REST API for the Buildkite control plane. Bearer-token auth with API access tokens.

- **Human URL:** [https://buildkite.com/docs/apis/rest-api](https://buildkite.com/docs/apis/rest-api)
- **Base URL:** `https://api.buildkite.com/v2`

#### Tags

- REST
- Pipelines
- Builds
- Agents
- Clusters

#### Properties

- [Documentation](https://buildkite.com/docs/apis/rest-api)
- [Authentication](https://buildkite.com/docs/apis/managing-api-tokens)
- [Postman Collection](collections/buildkite.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/buildkite.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Buildkite GraphQL API

Relay-compliant GraphQL API. Single endpoint for nested queries across organizations, pipelines, builds, jobs, agents, teams. Introspection supported. Bearer auth with the "Enable GraphQL API Access" scope.

- **Human URL:** [https://buildkite.com/docs/apis/graphql-api](https://buildkite.com/docs/apis/graphql-api)
- **Base URL:** `https://graphql.buildkite.com/v1`

#### Tags

- GraphQL
- Relay

#### Properties

- [Documentation](https://buildkite.com/docs/apis/graphql-api)
- [Console](https://buildkite.com/user/graphql/console)
- [Postman Collection](collections/buildkite.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/buildkite.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Buildkite Agent API

API consumed by buildkite-agent — register, retrieve work, send job events and upload artifacts/annotations. Used by self-hosted and hosted agents.

- **Human URL:** [https://buildkite.com/docs/apis/agent-api](https://buildkite.com/docs/apis/agent-api)
- **Base URL:** `https://agent.buildkite.com/v3`

#### Tags

- REST
- Agent
- Internal

#### Properties

- [Documentation](https://buildkite.com/docs/apis/agent-api)
- [Postman Collection](collections/buildkite.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/buildkite.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/buildkite)
- [Website](https://buildkite.com/)
- [Documentation](https://buildkite.com/docs)
- [Pricing](https://buildkite.com/pricing)
- [Git Hub](https://github.com/buildkite)
- [Status Page](https://buildkitestatus.com/)
- [Plans](plans/buildkite-plans-pricing.yml)
- [Rate Limits](rate-limits/buildkite-rate-limits.yml)
- [Fin Ops](finops/buildkite-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
