# University of Chicago (university-of-chicago)

The University of Chicago is a private research university in Chicago, Illinois, founded in 1890 and ranked #14 in the QS World University Rankings 2025. Its public developer footprint centers on research data infrastructure — the Center for Translational Data Science (CTDS) maintains the open-source Gen3 data platform — alongside CNetID identity (Shibboleth/OpenID Connect) integrations and Library IIIF endpoints. There is no single central, self-service public developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-chicago/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-chicago-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Source, IIIF, Identity, United States

## APIs

- **Gen3 Data Commons APIs (CTDS)** — Open-source FAIR APIs for biomedical data commons, maintained by the UChicago Center for Translational Data Science. Docs: https://uc-cdis.github.io/gen3-user-doc/appendices/api-gen3/ — GitHub: https://github.com/uc-cdis
- **CNetID OpenID Connect / Shibboleth Identity** — Shibboleth IdP extensions and OIDC examples for authenticating CNetID applications. Docs/GitHub: https://github.com/uchicago
- **University of Chicago Library IIIF** — IIIF image and presentation endpoints for digital collections. Docs: https://github.com/uchicago-library/iiif — Base: https://iiif-manifest.lib.uchicago.edu/

## Plans

- plans/university-of-chicago-plans-pricing.yml

## Rate Limits

- rate-limits/university-of-chicago-rate-limits.yml

## FinOps

- finops/university-of-chicago-finops.yml

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uchicago.edu/
- GitHub: https://github.com/uchicago
- LinkedIn: https://www.linkedin.com/school/uchicago/
- Twitter: https://twitter.com/UChicago
- SourceCode: https://github.com/uc-cdis
- Authentication: https://github.com/uchicago

## Notes

Verification caveats: All listed GitHub orgs, Gen3 docs, Library IIIF host, and the VuFind catalog resolved 200 on 2026-06-03. The official www.uchicago.edu returns 403 to unauthenticated automated requests but is live in a browser. The AI API developer portal (ai-api-portal-dev.uchicago.edu) is a gated, faculty/staff-only Azure OpenAI portal that does not resolve externally (certificate mismatch / no response) and is therefore not cataloged as a public API. No endpoints, base URLs, or docs were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
