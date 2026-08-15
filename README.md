# Awesome-Indirect-Tax-Compliance

## Top Indirect Tax Compliance Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Sales Tax, VAT, GST Determination, Calculation, Nexus Monitoring, Filing, Remittance & Multi-Jurisdiction Compliance*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Indirect Tax Compliance**. These tools help businesses accurately determine, calculate, collect, report, and remit sales tax, VAT, GST, and related indirect taxes across multiple jurisdictions — critical for e-commerce, SaaS, digital goods, and cross-border sellers.

**Examples** include Avalara, Vertex, Sovos, ONESOURCE Indirect Tax, ClearTax Enterprise, TaxJar, Anrok, Blue dot, Taxually, and Complyt (the category leaders and widely used platforms).

**Open-source emphasis**: Full-featured open-source platforms that handle multi-jurisdiction determination, filing, and remittance are extremely limited due to the complexity and regulatory nature of tax content. This section prioritizes the strongest available open-source calculation engines, rate databases, and related tools that teams can self-host or embed for tax computation (especially US sales tax).

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Avalara](https://www.avalara.com/)**  
  Leading global tax compliance platform providing real-time sales tax, VAT, and GST calculation, determination, filing, and content management across thousands of jurisdictions.
- **[Vertex](https://www.vertexinc.com/)**  
  Enterprise indirect tax determination and compliance solution with deep ERP integrations (SAP, Oracle, etc.) and strong multi-jurisdictional coverage.
- **[Sovos](https://sovos.com/)**  
  Global tax and regulatory compliance platform covering VAT, GST, e-invoicing, and related indirect tax obligations for multinationals.
- **[ONESOURCE Indirect Tax](https://tax.thomsonreuters.com/)** (Thomson Reuters)  
  Enterprise tax determination and compliance suite used by large organizations for complex indirect tax requirements.
- **[ClearTax Enterprise](https://cleartax.in/)**  
  Strong presence in India and expanding markets for GST and related compliance automation.
- **[TaxJar](https://www.taxjar.com/)** (Stripe)  
  Popular sales tax automation platform for e-commerce and online sellers, covering calculation, reporting, and filing (especially US-focused).
- **[Anrok](https://www.anrok.com/)**  
  Modern sales tax compliance platform built for SaaS and digital businesses, emphasizing automated nexus, calculation, and filing.
- **[Blue dot](https://www.bluedot.global/)** / **[Taxually](https://www.taxually.com/)** / **[Complyt](https://complyt.io/)**  
  Specialized platforms focused on VAT/GST automation, cross-border compliance, and digital services tax for international sellers.
- **[Stripe Tax](https://stripe.com/tax)**, **[Quaderno](https://quaderno.io/)**, **[Fonoa](https://www.fonoa.com/)**, **[Numeral](https://www.numeralhq.com/)**  
  Additional modern calculation and compliance tools frequently used by digital and e-commerce businesses.
- **[TaxCloud](https://taxcloud.com/)** and SST-oriented providers  
  Options leveraging Streamlined Sales Tax (SST) for US multi-state compliance.

## Open-Source GitHub Projects
- **[OpenSalesTax](https://github.com/ejosterberg/open-sales-tax)**  
  Open-source, self-hostable US sales tax calculation engine and API. Covers all 52 US sales-tax jurisdictions with per-state taxability rules, jurisdiction breakdowns, and contributor-driven maintenance. The strongest pure open-source alternative for US sales tax calculation (calculation only — not filing).
- **OpenSalesTax SDKs and WooCommerce integrations**  
  Community PHP and other language SDKs plus store plugins that allow self-hosted replacement of commercial tax APIs for US merchants.
- **[world-tax-rs](https://github.com/franzos/world-tax-rs)**  
  Open-source (Rust) library for offline calculation of worldwide sales tax / VAT rates, with support for various regional rules (EU, GCC, Canadian provinces, US states, etc.). Still evolving.
- **Tax rate databases and offline calculators**  
  Community-maintained JSON/CSV rate tables and lightweight calculators that can be embedded in applications for basic determination.
- **US Federal / State Income Tax Engines** (related but distinct)  
  Projects such as Tax-Calculator (PSL), tax-logic-core, opentax, and similar open engines focus on income tax rather than indirect tax, but demonstrate transparent, auditable tax computation patterns.
- **Streamlined Sales Tax (SST) data consumers**  
  Open tools and scripts that consume publicly available SST rate and boundary data for building custom US sales tax solutions.
- **Emerging AI-agent tax skill libraries**  
  Early open efforts that provide cited tax computation skills for AI agents (broader than pure indirect tax but relevant to automated compliance workflows).

### Additional Strong Open-Source Options
- Custom determination engines built on public rate files + jurisdiction boundary data.
- Integration patterns that combine open calculation engines with commercial filing services.
- Exemption certificate management and document workflows built on open document platforms.
- Reporting templates and workpaper generators for preparing returns from calculated data.
- Monitoring scripts that track rate and rule changes from official sources.

**Frameworks for building custom systems**: For US-focused sellers, **OpenSalesTax** (self-hosted) provides the calculation layer that can replace TaxJar/Avalara-style APIs for determination. Filing, remittance, nexus registration, and international VAT/GST generally still require commercial services or local advisors. Global multi-country VAT/GST determination and automated filing remain almost exclusively commercial due to the volume and volatility of tax content.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Indirect tax compliance tools must be evaluated for jurisdiction coverage accuracy, product taxability rules, real-time vs batch calculation, filing and remittance support, audit defense capabilities, and total cost (including transaction or revenue-based fees).
- Open-source calculation engines do **not** constitute tax advice and do not replace professional compliance services. Tax rates, rules, and filing requirements change frequently; always validate outputs against official authority sources and consider engaging qualified tax professionals for filing and registration obligations.
---
**Made for finance, tax, and e-commerce teams that want more transparent and controllable sales tax / VAT / GST calculation infrastructure.**
Let's make indirect tax determination more open, auditable, and free from unnecessary black-box dependency — while recognizing that full compliance still requires authoritative content and professional processes.
