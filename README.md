# Laurentian Bank of Canada (laurentian-bank)

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

Laurentian Bank of Canada (Banque Laurentienne du Canada) is a Montreal-headquartered Schedule I chartered bank, founded in 1846 as the Montreal City and District Savings Bank and listed on the Toronto Stock Exchange as LB. With roughly CA$47 billion in assets, about 3,000 employees, and approximately 1.5 million clients, it serves personal, commercial, and capital-markets customers - concentrated in Quebec with commercial offices across Canada - through subsidiaries including B2B Bank, Laurentian Bank Securities, and LBC Capital.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/laurentian-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/laurentian-bank/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Laurentian Bank exposes **no public developer portal and no first-party API**. Probes of `developer.laurentianbank.ca`, `api.laurentianbank.ca`, `developer.blcbanque.ca`, and `developer.b2bbank.com` are all unreachable (no host); only the marketing/banking sites at `www.laurentianbank.ca` and `www.b2bbank.com` resolve (HTTP 200). Unlike RBC (developer.rbc.com) and other Big Six banks, Laurentian runs no API ecosystem or downloadable OpenAPI/Swagger.

Open-finance context, captured honestly:

- **First-party API:** None published. No OpenAPI/Swagger available to harvest.
- **Consumer data access:** Aggregator-mediated today - screen-scraping / credential-based access via Canadian and third-party aggregators (e.g. Flinks, Plaid), not a first-party data-access API.
- **Consumer-Driven Banking (CDB):** Canada's federal Consumer-Driven Banking framework (Budget 2024 / Fall Economic Statement 2024, overseen by the FCAC) is legislated but **not yet operational**; access remains voluntary and fragmented. Laurentian has published no CDB or FDX participation posture.
- **Canadian rails:** As a Schedule I bank and Payments Canada member, Laurentian participates in shared infrastructure (Interac e-Transfer for customers; Payments Canada clearing/settlement), but documents no public API around these rails.
- **Corporate development:** In December 2025 the bank announced a proposed sale to Fairstone Bank of Canada, with National Bank of Canada acquiring its retail operations.

## Tags

- Financial Services
- Banking
- Canada
- Schedule I Bank
- Retail Banking
- Quebec
- Interac
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public APIs are documented. This is an identity-only (stub) profile; consumer data access to the institution is available only via third-party aggregators.

## Common Properties

- [Website](https://www.laurentianbank.ca/en)
- [Investor Relations](https://www.laurentianbank.ca/en/about-us/investor-relations)
- [Blog / Newsroom](https://news.laurentianbank.ca/)
- [LinkedIn](https://ca.linkedin.com/company/banque-laurentienne)
- [Privacy Policy](https://www.laurentianbank.ca/en/personal/privacy-and-security)
- [Terms of Service / Legal Notice](https://www.laurentianbank.ca/en/personal/legal-notice)
- [Security](https://www.laurentianbank.ca/en/personal/ways-to-bank/security)
- [Support / Contact](https://www.laurentianbank.ca/en/contact-us)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
