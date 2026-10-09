# Hi, I'm Zhenghao Zhang

**Full-stack developer building reliable workflow tools, data automation, and responsive business interfaces.**

I work across frontend UX, API design, data modeling, testing, and delivery. The projects below use synthetic or demo data, provide reproducible evidence, and state their production boundaries explicitly.

## Featured project

### [CommerceOps Desk](https://github.com/Zhang-ZhengHao/commerce-ops-desk)

CommerceOps Desk is a synthetic ecommerce operations desk that proves a signed payment-failure event from HMAC-authenticated ingress through an assigned and resolved case.

- React + TypeScript interface with a FastAPI, SQLAlchemy, and Alembic backend
- Tenant-scoped Manager/Agent RBAC, optimistic concurrency, retry-safe commands, and ordered audit history
- Fresh, byte-identical replay, post-signing tamper, and stale-timestamp webhook scenarios
- Safe event provenance and GET-only recovery after a committed delivery whose refresh failed
- Single-node SQLite demo plus live PostgreSQL 17 CI for migrations, constraints, concurrency, and the hardened container path

[Watch the v0.2 walkthrough](https://github.com/Zhang-ZhengHao/commerce-ops-desk/releases/tag/v0.2.0) · [Review the final CI run](https://github.com/Zhang-ZhengHao/commerce-ops-desk/actions/runs/37859704804) · [Read the versioned security model](https://github.com/Zhang-ZhengHao/commerce-ops-desk/blob/v0.2.0/docs/security-model.md)

All identities, orders, and outcomes are synthetic. This release has no live store or payment-provider connection, asynchronous worker or outbox, automatic retry queue, exactly-once guarantee, or production-readiness claim.

## Other selected work

### [HAURUX ERP Portfolio](https://github.com/Zhang-ZhengHao/haurux-erp-portfolio)

A responsive ERP concept covering role-aware workflows across access, procurement, inventory, sales, and accounting. It includes bilingual documentation, a proposed 37-screen scope map, accessibility considerations, contract tests, and a [live GitHub Pages demo](https://zhang-zhenghao.github.io/haurux-erp-portfolio/).

### [E-commerce Lead Automation](https://github.com/Zhang-ZhengHao/ecommerce-lead-automation)

A tested Python and Streamlit workflow that turns redacted XLSX/CSV customer messages into a reviewable lead queue, with deterministic offline processing, optional AI assistance, human confirmation before sendable export, and spreadsheet formula-injection protection.

[Open the v0.1.0 release](https://github.com/Zhang-ZhengHao/ecommerce-lead-automation/releases/tag/v0.1.0) · [Review the final CI run](https://github.com/Zhang-ZhengHao/ecommerce-lead-automation/actions/runs/37864303689) · [Read the release changelog](https://github.com/Zhang-ZhengHao/ecommerce-lead-automation/blob/v0.1.0/CHANGELOG.md)

### [Market Research Brief](https://github.com/Zhang-ZhengHao/market-research-brief)

A tested Python and Streamlit tool that supports up to five supplied public pages or pasted documents, preserves source-level traceability, and exports reusable project files.

## Technical focus

- React, TypeScript, FastAPI, SQLAlchemy, Alembic, PostgreSQL, Playwright, and pytest
- Tenant-scoped RBAC, authenticated webhooks, idempotency, optimistic concurrency, and audit trails
- Python, Streamlit, pandas, openpyxl, HTML, CSS, and JavaScript
- Spreadsheet ingestion, validation, structured exports, and responsive interfaces
- Human-in-the-loop AI workflows with explicit review, privacy, and security boundaries

## Available for

- Full-stack internal tools and operations dashboards
- API integrations and auditable business workflows
- Spreadsheet and data-workflow automation
- AI-assisted tools that keep a human approval step

English / 中文 · Available for remote freelance projects

## Contact

For a technical question, use the [CommerceOps engineering inquiry form](https://github.com/Zhang-ZhengHao/commerce-ops-desk/issues/new?template=engineering-feedback.yml) with synthetic data only. For private project details, contact me through the platform where you found this profile.
