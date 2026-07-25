# Concirrus (concirrus)

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
