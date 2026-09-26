# Gym Vending

An operating playbook for a women’s locker-room essentials vending business. The long-term vision is an autonomous system that finds sites, manages inventory and service, monitors performance, and recommends decisions. The business process comes first: two local gym pilots will establish what actually works before it is automated.

**Status:** discovery. No gym agreement, machine purchase, product demand, or economics is assumed to be validated.

## Roadmap

| Phase | Goal | Exit condition |
| --- | --- | --- |
| 1 — manual validation | Find a suitable machine, win two local gym locations, source and operate an initial assortment, and record every decision and event | Two machines live at local gyms, with signed site agreements, working payments, a repeatable service routine, and at least 8 weeks of comparable operating data per site |
| 2 — assisted operations | Encode the proven workflows as AI-assisted processes with human approval for commitments and changes | Reliable data capture, recommendations evaluated against Phase 1 outcomes, documented exceptions and rollback paths |
| 3 — autonomous operations | Automate bounded, measurable decisions across site prospecting, replenishment, support, and reporting | Only after controls, legal review, integrations, and observed performance support each decision class |

## Start here

1. Read [the operating workflow](docs/operations.md) and create a copy of the [site record](templates/site.md) for each prospect.
2. Use [machine selection](docs/machine-selection.md) to compare at least three realistic options **before** buying one.
3. Use [gym sales](docs/gym-sales.md) to prospect, pitch, inspect, and contract for two pilot sites.
4. Select the first assortment with [product and inventory guidance](docs/products-inventory.md). Confirm the gym’s existing free amenities first.
5. Build the unit economics in [pilot economics](docs/economics.md), then launch and log every visit, sale, issue, and restock using the [templates](templates/).
6. Review the pilots using [measurement and exit gates](docs/pilots.md). Only then use [automation design](docs/automation.md).

The templates are working records. Put actual site data in `records/` (create it when needed); avoid committing names, phone numbers, contract terms, or other sensitive data to a public repository. Keep signed agreements and personal data in an access-controlled system and record a reference here.

## Principles

- Solve an immediate need during a gym visit. Use small, sealed, familiar products.
- Keep essential menstrual access in mind: check site rules and existing free provision before charging for pads or tampons.
- Test demand, margins, and service effort separately by site and SKU. A retail listing proves availability, not demand or wholesale economics.
- Maintain human ownership of the site relationship, safety, payments, and financial commitments throughout Phase 1.
- Write down the inputs, decision, outcome, and exception every time; Phase 2 can only automate a process that is observable.

## Research basis and limits

An ISSA summary of a survey reports that 86% of respondents had started a period unexpectedly in public without supplies; a university vending study found tampons and ibuprofen among its frequently dispensed products. These are evidence of a need in other settings, **not a forecast for gyms**. Current retail listings show examples of [Dove 0.5 oz deodorant](https://www.target.com/p/-/A-75002996), [Dove 3 fl oz body wash](https://www.target.com/c/mini-travel-size-products/basic-cleansing/body-washes/-/N-4ucorZtei9a), [Batiste 1.06 oz non-aerosol dry shampoo](https://www.target.com/p/-/A-94794445), [Neutrogena individually wrapped makeup wipes](https://www.target.com/p/-/A-94045275), and [Always Pocket FlexFoam pads](https://www.target.com/p/-/A-94505155). Verify availability, pack dimensions, labeling, cost, and vend compatibility before procurement. Sources: [ISSA](https://www.issa.com/industry-news/take-the-issa-period-friendly-restroom-survey/), [university vending study](https://pubmed.ncbi.nlm.nih.gov/40200830/).

