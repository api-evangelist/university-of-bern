# University of Bern (university-of-bern)

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

The University of Bern (Universität Bern), founded in 1834, is a comprehensive public research university in the Swiss capital with around 16,000 students across eight faculties, ranked #91 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer/API footprint as an APIs.json profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-bern/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-bern-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Switzerland, Research, Open Access, Institutional Repository, Library

## APIs

- **BORIS Portal DSpace REST API** — Institutional repository and research information system on DSpace 7.6.1; HAL/JSON REST API exposing communities, collections, items, and CRIS research entities. Docs: https://www.ub.unibe.ch/services/open_science/boris_portal/index_eng.html — Base URL: https://boris-portal.unibe.ch/server/api
- **BORIS Portal OAI-PMH Endpoint** — OAI-PMH 2.0 metadata harvesting for the University of Bern's research outputs. Docs: https://www.ub.unibe.ch/services/open_science/boris_portal/index_eng.html — Base URL: https://boris-portal.unibe.ch/server/oai/request
- **University Library Data-Mining APIs Guide** — Curated library guidance on text-and-data-mining APIs (covers freely accessible and licensed third-party services). Docs: https://www.ub.unibe.ch/services/digital_scholarship/apis/index_eng.html

## Plans

See [plans/university-of-bern-plans-pricing.yml](plans/university-of-bern-plans-pricing.yml).

## Rate Limits

See [rate-limits/university-of-bern-rate-limits.yml](rate-limits/university-of-bern-rate-limits.yml).

## FinOps

See [finops/university-of-bern-finops.yml](finops/university-of-bern-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.unibe.ch/index_eng.html
- GitHub (IT-Services): https://github.com/id-unibe-ch
- Source Code (University Library): https://github.com/ub-unibe-ch
- LinkedIn: https://www.linkedin.com/school/university-of-bern/
- Plans: plans/university-of-bern-plans-pricing.yml
- Rate Limits: rate-limits/university-of-bern-rate-limits.yml
- FinOps: finops/university-of-bern-finops.yml
- Review: review.yml

## Notes

All entries were verified live on 2026-06-03 with no fabrication. The University of Bern does not operate a single unified self-service developer portal. The strongest confirmed machine-readable surface is BORIS Portal (DSpace 7.6.1): both its REST API (`/server/api`) and OAI-PMH endpoint (`/server/oai/request`) returned HTTP 200. The University Library APIs page documents third-party data-mining services rather than University-of-Bern-operated APIs. Course/SIS (KSL) and identity systems are gated behind institutional affiliation and Swiss federated identity (SWITCH edu-ID / Shibboleth) and are not cataloged as public APIs. The IWI Open Data Show Room (opendata.iwi.unibe.ch) did not resolve at review time.

## Maintainers

- Kin Lane — kin@apievangelist.com
