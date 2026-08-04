# University of Macau (university-of-macau)

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

The University of Macau (UM), founded in 1981, is the leading public comprehensive research university of the Macao Special Administrative Region, ranked #245 in the QS World University Rankings 2025. UM operates a public-facing Data and Open Data API Platform at [data.um.edu.mo](https://data.um.edu.mo/), managed by its Information and Communication Technology Office (ICTO), exposing JSON APIs across About UM, Academic, Facilities, Media, and Student data categories. Access requires registration and an API key via UMPASS.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-macau/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-macau-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Open Data
- Macau
- China

## APIs

- **UM Data and Open Data API Platform** — JSON APIs to UM-published data (About UM, Academic, Facilities, Media, Student) with pagination, filtering, sorting, and standard HTTP response codes. Access requires an API key via UMPASS.
  - Docs: https://data.um.edu.mo/api-documents/api-operations
  - Call examples: https://data.um.edu.mo/documentation/api-call-examples
  - Sign up: https://data.um.edu.mo/quickstart

## Plans

- [plans/university-of-macau-plans-pricing.yml](plans/university-of-macau-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-macau-rate-limits.yml](rate-limits/university-of-macau-rate-limits.yml)

## FinOps

- [finops/university-of-macau-finops.yml](finops/university-of-macau-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.um.edu.mo/
- Developer Portal: https://data.um.edu.mo/
- Authentication: https://data.um.edu.mo/quickstart
- Terms of Service: https://data.um.edu.mo/terms-and-conditions-of-use
- LinkedIn: https://www.linkedin.com/school/universityofmacau/

## Notes

- All URLs were probed live on 2026-06-03. The data platform home, API operations docs, call examples, dataset listing, quickstart, and terms pages returned HTTP 200.
- The platform is gated behind UMPASS registration and an API key; no anonymous public API base URL is documented (`api.data.um.edu.mo` returns HTTP 404), so no `baseURL` is asserted in apis.yml.
- No official University of Macau GitHub organization was found; `github.com/UM` belongs to University of Malaya, not Macau. No endpoints, keys, or base URLs were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
