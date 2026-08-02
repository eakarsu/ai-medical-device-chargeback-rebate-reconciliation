# Medical Device Chargeback & Rebate Reconciliation

Validate distributor chargebacks and calculate earned rebates, price protection, and contract credits at device and customer level.

**Primary buyer:** Medical-device manufacturers. **Evidence:** customer contracts, distributor sales, device SKUs, lot and serial data, chargebacks, rebates, returns, eligibility, credits, and deductions.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Contract price library
- Distributor customer mapping
- Device SKU registry
- Sales trace ingestion
- Eligibility validation
- Contract price calculation
- Chargeback validation
- Duplicate claim detection
- Volume rebate calculation
- Price-protection calculation
- Return credit coordination
- Distributor deduction matching
- Dispute workflow
- Settlement reconciliation
- Device channel analytics

Run `./start.sh`, then open <http://127.0.0.1:4656>. API: `5656`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
