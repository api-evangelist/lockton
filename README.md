# Lockton (lockton)

Lockton Companies is the world's largest privately held, independent insurance brokerage, founded by Jack Lockton in 1966 and headquartered in Kansas City, Missouri, United States. Lockton is a broker and intermediary rather than a risk carrier: it places commercial property and casualty, specialty and financial lines, employee benefits and people solutions, private client coverage, and — through Lockton Re — treaty and facultative reinsurance, across a global network of associates and offices reaching more than 140 locations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lockton/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lockton/refs/heads/main/apis.yml)

## Tags

- Insurance
- United States
- Broker
- Insurance Brokerage
- Property and Casualty
- Employee Benefits
- Reinsurance
- Specialty Insurance
- Risk Management
- ACORD
- Partner Gated
- No Public API

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

**None.** Lockton publishes no public, self-serve API.

As of 25 July 2026 there is no developer portal, no API reference, no downloadable OpenAPI or Swagger definition, no GraphQL endpoint, no published `.proto`, no public Postman collection or workspace, and no webhook or event catalog anywhere on a Lockton-owned property.

- `developer.lockton.com`, `developers.lockton.com`, `docs.lockton.com`, `api.lockton.com` and `apis.lockton.com` do not resolve in DNS.
- `www.lockton.com` (200) redirects to [https://global.lockton.com/us/en](https://global.lockton.com/us/en); `/developers`, `/api` and `/partners` under `global.lockton.com/us/en` all return 404.
- `/openapi.json`, `/swagger.json`, `/api-docs`, `/graphql`, `/.well-known/openid-configuration` and `/.well-known/oauth-authorization-server` on `global.lockton.com` all return 404.
- The 6,953 URLs in [global.lockton.com/sitemap.xml](https://global.lockton.com/sitemap.xml) contain **zero** developer, API reference, ACORD, IVANS, OpenAPI or Swagger paths.

The only outward-facing integration surfaces are gated:

- **Lockton Client Portal** — authenticated regional client portals, e.g. [global.lockton.com/gb/en/client-login](https://global.lockton.com/gb/en/client-login) (200, login wall).
- **Lockton SAGE Intelligence Platform** — proprietary AI-enabled analytics ecosystem originating at Lockton Re, presented publicly at [global.lockton.com/us/en/lockton-sage-contact-us](https://global.lockton.com/us/en/lockton-sage-contact-us) (200) behind a contact form, with no technical documentation, data feed or self-serve access.

Recording that absence accurately is the point. This is the expected posture for a US broker-intermediary.

## ACORD Posture

**ACORD board seat via Lockton Re; no ACORD implementation documented.**

Lockton's ACORD signal is governance, not implementation. On 20 July 2026 Nidhi Howell, Chief Business Technology Officer of Lockton Re, was appointed to the ACORD Solutions Group Board of Directors, explicitly representing the reinsurance broking channel. Lockton Re also operates in the London and reinsurance orbit where Ruschlikon and ACORD ePlacing standards govern broker-to-carrier messaging.

No Lockton-owned public page documents an ACORD AL3, ACORD XML, NGDS, IVANS agency download, Applied Epic or Vertafore AMS360 integration.

## Insurance API Verbs

| Verb | Exposed |
| --- | --- |
| Quote | No |
| Bind | No |
| Issue | No |
| FNOL | No |

As a broker-intermediary Lockton does not underwrite. Placement, binding and claims advocacy run through its brokers, carrier markets and authenticated client portals — not through a documented API.

## Market Seam — United States

The United States has no federal insurance regulator and no open-insurance mandate. Insurance is regulated state by state under NAIC model laws (the McCarran-Ferguson settlement), so there is no national API surface and nothing compels a broker or carrier to expose anything. Data exchange has run since the 1970s on ACORD standards in an EDI and forms idiom, moved by agency-download plumbing (IVANS) between carriers and agency management systems. Value accrued to the software and risk-data layer sitting between carriers and distribution — Verisk, LexisNexis Risk, CCC, Guidewire, Duck Creek, Applied Systems, Vertafore — while brokers and carriers publish almost nothing public. Lockton is a textbook instance of that pattern.

## Links

- [Website](https://global.lockton.com/us/en)
- [News & Insights](https://global.lockton.com/us/en/news-insights)
- [LinkedIn](https://www.linkedin.com/company/lockton)
- [GitHub Organization](https://github.com/Lockton-Companies) — 3 public repos, all internal cloud/IT ops; no API artifacts
- [Client Login](https://global.lockton.com/gb/en/client-login)

## Review

See [review.yml](review.yml) for the full reviewer findings, every probed URL with its HTTP status, and the ACORD posture with sources.
