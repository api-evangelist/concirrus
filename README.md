# Concirrus (concirrus)

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

Concirrus Ltd is a London-headquartered insurtech founded in 2012 that builds AI-driven underwriting software for the specialty and commercial insurance market — marine (hull, cargo, P&I), aviation, construction, property, and political violence and terrorism. Its platform (Quest, Marine One, the Underwriting Workbench, Exposure Management, Loss Run Intelligence, and an "Enterprise Model" universal submission-ingestion layer) ingests broker submissions, structures the risk data, scores behavioural risk, and returns rating and exposure decisions to carriers, MGAs and brokers — much of it aimed at the Lloyd's and London subscription market.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/concirrus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/concirrus/refs/heads/main/apis.yml)

## Tags

- Insurance
- United Kingdom
- Insurtech
- Specialty Insurance
- Marine Insurance
- Aviation Insurance
- Underwriting
- Risk Data
- London Market
- Lloyd's of London
- Exposure Management
- Artificial Intelligence
- Partner Gated

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

None listed — and that is the finding.

Concirrus publishes **no public developer portal and no machine-readable API definition**. As of 2026-07-25:

- `developer.`, `developers.`, `docs.` and `api.` do not resolve on either `concirrus.com` or `concirrus.ai` (NXDOMAIN).
- `/developers`, `/developer`, `/api`, `/partners` and `/integrations` on `concirrus.ai` all return **404**.
- `/openapi.json`, `/swagger.json` and `/api-docs` return **404**; `/.well-known/openid-configuration` and `/.well-known/oauth-authorization-server` return **404**.
- The apex `concirrus.com` fails TLS negotiation; `www.concirrus.com` returns **200** and redirects to `https://concirrus.ai/`, which is the live property.
- There is no GitHub organization, no public Postman collection, no GraphQL endpoint, no published `.proto`, and no webhook or AsyncAPI event catalog.

The only public API language is marketing copy on the partner programme page (**200**):

> "Concirrus provides a modular, API first platform, joint go to market alignment, and partner enablement."

and on the marine product page:

> "Seamlessly integrate with London Market platforms to streamline data flow and ensure compliance across all risk classes."

Neither names a platform, protocol, base URL or endpoint. Integration is obtained through a commercial engagement or the partner ecosystem programme — **partner-gated, not self-serve**.

### ACORD posture

**No ACORD reference found.** Site searches for ACORD, AL3, NGDS and ACORD XML return zero results across `concirrus.ai`, and no ACORD solution-provider listing was located.

### Quote / bind / issue / FNOL

Concirrus is a software vendor, not a carrier or an MGA of record. Rating and quote decisioning exist inside the Underwriting Workbench and the Enterprise Model ingestion layer but are not publicly documented as APIs. Bind, issue and FNOL are not exposed. Loss data is consumed through Loss Run Intelligence rather than published as an FNOL API.

### Market context

The UK has the FCA and PRA but no open-insurance obligation, and the FCA's Open Finance work is still consultation rather than rule. The only market-wide data and API infrastructure effort is the London Market modernization programme (Blueprint Two, PPL, Whitespace, Ki), aimed at brokers and syndicates rather than developers. Concirrus sits squarely in that seam — it markets London Market connectivity while publishing nothing a developer can read.

## Links

- [Website](https://concirrus.ai/)
- [About](https://concirrus.ai/about/)
- [Blog](https://concirrus.ai/blog/)
- [Blog RSS](https://concirrus.ai/feed/)
- [Partner Ecosystem](https://concirrus.ai/partner-ecosystem/)
- [Clients](https://concirrus.ai/clients/)
- [Book a Demo](https://concirrus.ai/book-a-demo/)
- [Careers](https://concirrus.ai/careers/)
- [Privacy Policy](https://concirrus.ai/privacy-policy/)
- [LinkedIn](https://www.linkedin.com/company/concirrus)

## Maintainers

- Kin Lane — kin@apievangelist.com
