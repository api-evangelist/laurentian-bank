# Laurentian Bank of Canada (laurentian-bank)

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
