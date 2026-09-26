# Phase 2: automate the validated process

## Architecture direction

Treat Phase 1 records as a specification for workflows, not as a promise that an AI model can operate the business alone. Integrate machine telemetry and payment exports with a structured SKU catalog, inventory ledger, site CRM, ticket queue, and reporting store. Every agent action needs input provenance, a proposed action, approval status, execution result, and an audit trail.

| Workflow | Inputs | First automation | Human boundary |
| --- | --- | --- | --- |
| Site prospecting | Public gym information, site criteria, CRM | Rank candidates and draft site-specific outreach | Approve claims, recipients and all sending/terms |
| Machine procurement | Quotes, compatibility tests, site constraints | Compare total cost and flag missing terms | Approve vendor and purchase |
| Assortment/pricing | SKU costs, sales, availability, competitor/amenity notes | Suggest swaps and prices with estimated contribution | Approve prices, safety-sensitive items and site changes |
| Replenishment | Per-slot sales, count corrections, lead times | Forecast reorder and propose route/loads | Approve purchase and physical service until accuracy is demonstrated |
| Customer support | Vend/payment errors, support requests | Triage, draft response and flag refunds | Review disputes, safety concerns and exceptions |
| Finance/reporting | Payment settlement, invoices, tax/commission rules | Reconcile and draft weekly scorecards | Approve payouts, filings and accounting adjustments |

## Implementation sequence

1. Standardize IDs and events from the templates; define ownership and retention. Ensure a payment transaction can be reconciled to a vend, refund, and settlement without storing card data.
2. Build deterministic dashboards and exception alerts before AI recommendations. Compare exports and physical counts.
3. Run AI recommendations in shadow mode against real manual decisions. Evaluate stockouts, margin, error rate, operator time, and missed exceptions over a defined period.
4. Grant narrowly scoped execution rights one workflow at a time. Set spend/price bounds, approvals, rollback, alerts, and a manual fallback.
5. Review performance and drift by site. Turn off automation on missing data, faulty telemetry, safety concerns, or repeated errors.

No restroom surveillance is required. Collect the minimum data necessary; do not enter private member information or confidential gym terms into an unapproved AI system. Research applicable privacy, consumer, accessibility, vending, tax, and payment obligations for the operating jurisdiction before implementing integrations.

