# University of Bern (university-of-bern)

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
