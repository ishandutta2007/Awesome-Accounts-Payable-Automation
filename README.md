# Awesome-Accounts-Payable-Automation

# Top Accounts Payable Automation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Invoice Capture, OCR/AI Extraction, Approval Workflows, 3-Way Matching, Payments & ERP Integration*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Accounts Payable (AP) Automation**. These tools help finance teams digitize invoice processing, extract data, route approvals, match against purchase orders and receipts, schedule payments, and sync with ERPs — reducing manual effort and improving control.

**Examples** include Tipalti, BILL (Bill.com), Stampli, AvidXchange, Melio, Airbase, Beanworks / Quadient AP, MineralTree, Yooz, Corpay One, Zahara, Ramp AP, Lightyear, Ottimate (Plate IQ), Veryfi, Nanonets, Medius, and others (the category leaders).

**Open-source emphasis**: Fully featured end-to-end open-source AP automation platforms comparable to Tipalti or BILL are still rare. However, strong building blocks exist for invoice extraction, workflow, matching, and integration with open-source ERPs. This section highlights every significant active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Tipalti](https://tipalti.com/)**  
  Global AP automation platform strong in mass payments, multi-currency, tax compliance (1099/1042-S), and complex supplier networks.

- **[BILL (Bill.com)](https://www.bill.com/)**  
  Widely adopted AP (and AR) platform for SMBs and mid-market, with invoice processing, approvals, payments, and deep QuickBooks/Xero/NetSuite integrations.

- **[Stampli](https://www.stampli.com/)**  
  AI-powered AP automation focused on collaborative invoice processing, on-invoice communication, and coding accuracy (“Billy the Bot”).

- **[AvidXchange](https://www.avidxchange.com/)**  
  Mid-market AP automation with a large supplier payment network, popular in real estate, construction, and property management.

- **[Melio](https://www.melio.com/)**  
  Simple, modern bill-pay and AP solution aimed at growing businesses, with flexible payment options (including paying vendors who only accept checks).

- **[Airbase](https://www.airbase.com/)**  
  Spend management and AP platform combining invoice processing, approvals, purchasing controls, and payments.

- **[Quadient AP / Beanworks](https://www.quadient.com/)**  
  AP automation solution with strong approval workflows and ERP integrations for mid-market organizations.

- **[Yooz](https://www.getyooz.com/)**  
  Cloud AP automation platform offering invoice capture, workflow, and integration capabilities with all-inclusive pricing models in some markets.

- **[Ramp AP](https://ramp.com/)**  
  Modern finance platform with AI-assisted invoice processing, coding, approvals, and payments as part of a broader spend-management suite.

- **[Medius](https://www.medius.com/)**  
  Enterprise-grade AP automation focused on touchless processing, advanced matching, and complex approval hierarchies.

- **[Ottimate (formerly Plate IQ), Veryfi, Nanonets, Lightyear, Zahara, Corpay One, MineralTree](https://www.ottimate.com/)**  
  Specialized or complementary AP automation and document-AI platforms offering capture, extraction, coding, and workflow features.

## Open-Source GitHub Projects

- **[Invoice-to-Pay Agent](https://github.com/mshojaei77/invoice-to-pay-agent)**  
  Open-source AP automation prototype using AI agents for OCR/VLM extraction, 3-way matching, approvals, fraud checks, ERP posting simulation, and full audit logging.

- **[AgenticAP / AI-Invoice projects](https://github.com/williamjxj/AgenticAP)**  
  AI-native platforms focused on processing heterogeneous invoice formats (PDF, images, Excel) with LLM-based extraction, validation, and routing — no per-vendor templates required.

- **[InvoiceBridge](https://github.com/pradhankukiran/invoice-bridge)**  
  Production-oriented open-source AP automation on .NET: UBL invoice ingestion, 3-way match, approval workflows, and accounting export.

- **[ERPNext / Frappe](https://github.com/frappe/erpnext)**  
  Fully open-source ERP with robust accounts payable, purchase invoice, payment entry, and multi-company features that form a strong foundation for AP processes.

- **[Odoo Community](https://github.com/odoo/odoo)**  
  Modular open-source ERP whose Accounting and Purchase apps support vendor bills, approvals, payments, and reconciliation; highly extensible for AP automation.

- **[InvoiceShelf](https://github.com/InvoiceShelf/InvoiceShelf)**  
  Open-source invoicing and expense tracking solution (self-hosted) that can serve as part of a broader AP/AR toolkit for smaller organizations.

- **[Document AI & OCR toolkits](https://github.com/search?q=invoice+ocr+OR+document+ai+invoice)**  
  Open-source OCR, layout analysis, and LLM extraction projects (Docling, PaddleOCR, various VLM pipelines) commonly used as the capture layer in custom AP systems.

### Additional Strong Open-Source Options

- **Workflow engines**: Temporal, Prefect, or Airflow for orchestrating multi-step invoice approval and matching flows.
- **Rules & policy engines**: Open Policy Agent or custom rule engines for coding and approval routing.
- **Payment & banking integrations**: Community connectors for bank APIs and payment files (ACH, SEPA, etc.).
- **Audit & compliance**: Tools for immutable logging and retention of invoice processing evidence.
- **Plain-text / lightweight accounting**: Systems that can receive structured AP data from custom pipelines.
- Emerging **agentic finance** repositories focused on autonomous invoice handling with human-in-the-loop controls.

**Frameworks for building custom systems**:  
Use **ERPNext** or **Odoo** as the system of record for vendors, purchase orders, invoices, and payments.  
Layer an open-source or custom **document AI / agent pipeline** (Invoice-to-Pay Agent style) for capture, extraction, and matching.  
Orchestrate approvals with a workflow engine and enforce policies with a rules engine.  
This approach delivers full data ownership and deep customization at the cost of higher engineering and maintenance effort.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Accounts payable processes involve financial controls, fraud risk, tax reporting, and regulatory compliance. Any automation system (commercial or open-source) must be properly controlled, audited, and reviewed by qualified finance personnel.
- Self-hosted open-source solutions require strong security, access controls, backup strategies, and careful integration with banking and ERP systems before production use.

---

**Made for finance leaders, AP managers, controllers, and fintech / automation engineers.**  
Let's make accounts payable more automated, transparent, and under organizational control.
