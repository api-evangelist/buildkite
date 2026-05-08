# Buildkite (buildkite)

Buildkite is a CI/CD platform that pairs a hosted control plane with self-hosted (or hosted) agents. The platform exposes a REST API, GraphQL API and Agent API. Resource families include organizations, pipelines, pipeline templates, builds, jobs, agents, clusters, queues, teams, rules, artifacts, annotations and access tokens. Test Engine adds test-execution endpoints.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **REST** — `https://api.buildkite.com/v2` — JSON over HTTPS, Bearer token auth. [Docs](https://buildkite.com/docs/apis/rest-api).
- **GraphQL** — `https://graphql.buildkite.com/v1` — Relay-compliant; introspection supported. [Docs](https://buildkite.com/docs/apis/graphql-api).
- **Agent API** — `https://agent.buildkite.com/v3` — used by `buildkite-agent`. [Docs](https://buildkite.com/docs/apis/agent-api).

## OpenAPI
Buildkite does not publish a public OpenAPI/Swagger spec for the REST API as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`. (GraphQL schema is available via introspection.)

## Tags
DevOps, CI/CD, Pipelines, Agents, Self-Hosted, GraphQL, Test Engine

## Common Properties
- [Website](https://buildkite.com/) · [Docs](https://buildkite.com/docs) · [Pricing](https://buildkite.com/pricing)
- [GitHub](https://github.com/buildkite) · [Status](https://buildkitestatus.com/)
- [Plans](plans/buildkite-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/buildkite-rate-limits.yml) — partial (429/Retry-After contract; numeric quotas private)
- [FinOps](finops/buildkite-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Personal (Free)** — 1 user, 3 concurrent jobs, 90-day retention, 500 hosted Linux min/mo, 50K test executions/mo.
- **Pro** — $30/active user/mo; 10 self-hosted agents included, $2.50/agent/mo above; 2,000 hosted Linux vCPU min + 250 test executions/mo included; 1-year retention.
- **Enterprise** — 30-user min, custom pricing, advanced governance.
- **All Access Trial** — 30 days, no card.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
