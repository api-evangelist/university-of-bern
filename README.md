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

The University of Bern (Universität Bern), founded in 1834, is a comprehensive public research university in the Swiss capital with around 16,000 students across eight faculties. This repository catalogs its public, machine-readable footprint as an APIs.json profile, with an explicit operator attribution on every surface.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-bern/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-bern-api-evangelist&utm_content=repo

## Type

University / Public Research University · Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, Switzerland, Public Research University, Research, Open Science, Open Access, Institutional Repository, Library, OAI-PMH, Identity Federation, Shibboleth, Research Computing, Scholarly Publishing

## Surfaces, by operator

A university is a federation of buyers, not an API producer. Every entry below carries an
`x-operator` saying **who runs the thing it describes** — which is not the same question as who
we fetched it from.

### Institution-operated (6)

- **BORIS Portal OAI-PMH Endpoint** — `https://boris-portal.unibe.ch/server/oai/request` — OAI-PMH 2.0, verified live 2026-09-01 (`repositoryName` "BORIS Portal", protocol 2.0, `adminEmail` borisportal@unibe.ch). The one path exempted from the access restriction on that host.
- **BORIS Portal DSpace REST API — public access suspended** — `https://boris-portal.unibe.ch/server/api` — **not publicly callable.** Every anonymous request to the host returns HTTP 200 carrying a "Temporary Access Restriction" page: access "is currently granted exclusively to" the University of Bern network, the Inselspital network and university VPN.
- **Bern Open Publishing (BOP Serials) OAI-PMH Endpoint** — `https://bop.unibe.ch/index.php/index/oai` — OJS 3.4.0.6, verified live, earliest datestamp 2015-08-25.
- **Bern Open Publishing OJS REST API** — returns `api.403.unauthorized` without a library-issued token.
- **University Library Public Services Status API** — Upptime, per-service JSON under `ub-unibe-ch/ub-public-services-status`. The only fully open machine-readable HTTP API in this profile.
- **University Library IIIF Image Server** — `https://iiif.ub.unibe.ch/` — live; IIIF API level and version deliberately not asserted (no manifest resolvable without an object id).

### Federation (1)

- **SWITCHaai — University of Bern IdP** — `entityID https://aai-idp.unibe.ch/idp/shibboleth`, scope `unibe.ch`. 53 unibe.ch entities in the SWITCHaai aggregate: 1 IdP and 52 service providers.

### Registry (2)

- **DataCite membership** — symbol `UNIBE`, `direct_member` since 2020-04-06, 5 registered repositories.
- **ROR record** — `https://ror.org/02k7v4d05`.

### Tenant (1)

- **swisscovery — University Library of Bern tenant view** — `https://ubbern.swisscovery.slsp.ch` (CNAME → `slsp-ube.primo.exlibrisgroup.com`). Ex Libris Primo VE via SLSP. The relationship is Bern's; the contract is Ex Libris's and is **not** saved here.

## Coverage

`gated` / `auth_required`. Bern's open surfaces are harvesting protocols and registry memberships;
every REST surface it operates is closed to anonymous callers. There is no developer portal, no
OpenAPI, and no `llms.txt` on any unibe.ch host. This is a correct thin profile, not a failed crawl.

## Conformance

See [conformance/university-of-bern-conformance.yml](conformance/university-of-bern-conformance.yml)
— `education`-regime standards probed live. Conforming: **oai-pmh**, **shibboleth**, **saml**,
**datacite**, plus RFC 9116 `security.txt`. Not conforming: orcid, crossref, scim, lti, oneroster,
ed-fi, caliper, qti, openapi, llms.txt.

## Plans / Rate Limits / FinOps

See [plans/](plans/university-of-bern-plans-pricing.yml), [rate-limits/](rate-limits/university-of-bern-rate-limits.yml), [finops/](finops/university-of-bern-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Notes

Re-profiled 2026-09-01 under the API Evangelist university pipeline, which settles operator
attribution before saving anything. No OpenAPI or other contract is saved in this repository,
because the University of Bern publishes none — nothing was fabricated or derived to fill the gap.

Two corrections to the 2026-06-03 profile:

1. The BORIS Portal DSpace REST API was recorded as "confirmed live returning HTTP 200". It is
   not: the host serves a 2,920-byte soft-200 "Access Restricted" page to the entire public. That
   was a soft-200 false credit and is corrected.
2. The "University Library Data-Mining APIs Guide" was listed as one of three APIs. It is a
   curated guide to **other organizations'** APIs (OpenAlex, Crossref, Scopus, Elsevier, IEEE,
   Springer Nature, Wiley) and describes nothing Bern operates. It has been demoted from `apis[]`
   to a `Documentation` pointer.

`opendata.iwi.unibe.ch` still does not resolve (DNS failure) and remains uncatalogued. Course and
identity systems (KSL, ILIAS, exam.unibe.ch) are behind SWITCH AAI and expose no public API.

## Maintainers

- Kin Lane — kin@apievangelist.com
