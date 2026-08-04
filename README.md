# RWTH Aachen University (rwth-aachen-university)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
