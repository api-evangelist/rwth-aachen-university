# RWTH Aachen University (rwth-aachen-university)

RWTH Aachen University is a leading German technical university, ranked #83 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an [APIs.json](http://apisjson.org) profile. The institution's confirmed public API surface centers on research-data and scholarly infrastructure operated by the IT Center and University Library.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/rwth-aachen-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=rwth-aachen-university-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Access, Germany

## APIs

- **Coscine Research Data API** — FAIR research data management platform with a public Swagger/OpenAPI REST API (token auth). Docs: https://docs.coscine.de/en/api/api/ · Swagger: https://coscine.rwth-aachen.de/coscine/api/swagger/index.html · OpenAPI: https://coscine.rwth-aachen.de/coscine/api/swagger/v2/swagger.json
- **RWTH Publications OAI-PMH** — Institutional repository metadata harvesting endpoint at https://publications.rwth-aachen.de/oai2d (re3data/OpenAIRE indexed). Docs: https://publications.rwth-aachen.de/
- **RWTH Single Sign-On (OAuth2 / OpenID Connect / Shibboleth)** — IT Center central identity service for application authorization. Docs: https://help.itc.rwth-aachen.de/en/service/rhb2fhkpjhb7/

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/rwth-aachen-university-plans-pricing.yml](plans/rwth-aachen-university-plans-pricing.yml)
- Rate Limits: [rate-limits/rwth-aachen-university-rate-limits.yml](rate-limits/rwth-aachen-university-rate-limits.yml)
- FinOps: [finops/rwth-aachen-university-finops.yml](finops/rwth-aachen-university-finops.yml)

## Timestamps

- **Created:** 2026-06-03
- **Modified:** 2026-06-03

## Common Properties

- Website: https://www.rwth-aachen.de/
- Source Code (GitLab): https://git.rwth-aachen.de/
- LinkedIn: https://www.linkedin.com/school/rwth-aachen-university/
- Developer / IT Center: https://www.itc.rwth-aachen.de/
- Review: [review.yml](review.yml)

## Notes

This profile is based on publicly verifiable documentation only; no endpoints were fabricated. The Coscine API docs, Swagger UI, and OpenAPI definition were confirmed live (HTTP 200). The RWTH Publications OAI-PMH endpoint and the OAuth2 Management Interface are documented but did not resolve to automated probes during review (likely bot filtering) and are therefore cataloged from documentation rather than a live response. There is no single unified RWTH developer portal; many institutes publish independently on the self-hosted GitLab and on various GitHub organizations. The RWTHapp mobile backend is SSO-gated with no public API and was not cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
