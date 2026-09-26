# Initial assortment and inventory

The gym checklist supplied for this project covers workout, shower, getting ready, clothes, after-workout, and extras. A restroom machine should focus on small, sealed items that solve an immediate problem, not reproduce the entire gym bag.

## Starting hypothesis: one to two slots per item

| Tier | Candidate | Format and validation |
| --- | --- | --- |
| Core | Mini antiperspirant/deodorant | Example: Dove Advanced Care 0.5 oz. Test packaging and scent preference. |
| Core | Hair ties | Sealed small retail pack; source and test actual packaging. |
| Core if showers | Body wash | Example: Dove Deep Moisture 3 fl oz. Check leaks and bottle drop. |
| Core | Pads and tampons | Individually manufacturer-wrapped, with a modest choice of absorbency. Check existing free supply, rules, and gym approval first. |
| Test | Makeup remover | Example: Neutrogena fragrance-free individually wrapped wipe. Never sell a loose wipe. |
| Test | Dry shampoo | Example: Batiste 1.06 oz non-aerosol powder. Test container and hair-type preferences. |
| Test if showers/pool | Wet-clothes bag | Sealed compact pouch; check slot dimensions. |
| Test if showers | Shampoo/conditioner, shower cap | Compact sealed retail packs; compare with gym-provided products. |
| Test | Blister bandages, floss picks, lip balm | Small sealed packs; validate demand and hygiene before expanding. |

Towels, shower shoes, spare clothing/underwear, drinks, and protein products may need size choices, larger slots, or a different placement. Consider a front desk or larger machine only if the site supports them. Avoid repackaging cosmetics, food, medicines, or menstrual supplies without checking applicable labeling and resale requirements. Keep drugs and emergency contraception outside the initial assortment pending local legal, storage, and partner review.

## SKU qualification

For each SKU record brand, exact product and UPC, supplier, pack size, unit dimensions/weight, sealed condition, expiry or shelf life, storage limits, landed cost, applicable tax, proposed price, expected margin, machine slot/test vend, reorder lead time, minimum order, and returns policy. Retail examples are linked in the README; their prices and availability may change. Get wholesale quotes before fixing prices.

## Inventory rules

Use a unique SKU and site/slot ID. Log every receipt, load, unload, sale, damaged unit, expiry, refund, and count correction with timestamp and reason. Reorder point = expected daily units × supplier lead time in days + safety stock. Initially estimate demand conservatively, inspect twice weekly, and revise from actual sales and stockout data. Rotate dated stock first-expiring-first-out. Count both machine and backstock; reconcile unexplained differences weekly.

