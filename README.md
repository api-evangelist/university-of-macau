# University of Macau (university-of-macau)

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
