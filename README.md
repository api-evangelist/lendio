# Lendio

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

Lendio is a small business lending marketplace founded in 2011 that connects businesses with funding through a network of 75+ lenders. The platform has facilitated over $17B in SMB funding for 520,000+ small businesses. Lendio offers three core product lines: a direct marketplace for small business borrowers, Embedded Financing for service providers, and Intelligent Lending software for banks and lenders.

## APIs

### Loan Marketplace API (Embedded Financing)

Lendio provides an API-first embedded financing platform that allows service providers to integrate the full Lendio loan marketplace within their ecosystem. The integration uses a single JavaScript snippet plus an authentication API endpoint for secure customer data sharing and application pre-fill. Partners also configure a CNAME DNS record pointing to Lendio's production servers.

- **Integration**: Single-line JavaScript widget + authentication API endpoint
- **Auth**: Token-based secure customer data transfer
- **Implementation**: 3-12 weeks with dedicated engineering support
- **Customization**: White-label UI with configurable fonts, colors, and branding

### Loan Performance Tracking API

Available for high-volume lenders integrated with the Intelligent Lending platform. Supports bulk submission of up to 10,000 records per request for loan performance data. Access is enabled through a custom code request process managed by a dedicated Customer Success Manager.

### Intelligent Lending Data API

Supports transaction data ingestion via real-time API connection or batched data import for credit decisioning analytics. Integrates with existing Loan Origination Systems (LOS) and third-party data providers including Finicity.

## Resources

- **Website**: https://www.lendio.com
- **Blog**: https://www.lendio.com/blog
- **Embedded Financing**: https://www.lendio.com/embedded-financing
- **Intelligent Lending**: https://www.lendio.com/intelligent-lending
- **Product Updates**: https://www.lendio.com/product-updates
- **Security**: https://www.lendio.com/security
- **GitHub**: https://github.com/LendioDevs
- **LinkedIn**: https://www.linkedin.com/company/lendio
- **X**: https://x.com/lendio
- **Support**: https://support.lendio.com
- **Contact**: https://www.lendio.com/contact

## Catalog Files

- `apis.yml` - APIs.json 0.19 provider profile
- `plans/lendio-plans-pricing.yml` - Pricing plans and tiers
- `rate-limits/lendio-rate-limits.yml` - API rate limit documentation
- `finops/lendio-finops.yml` - Financial operations and cost model
