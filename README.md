# Lockton (lockton)

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
