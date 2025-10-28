---
title: DDP vs FOB for Water Bottling Lines (2026) — A Practical Overview
layout: default
---

**Goal:** Compare landed cost in **USD per 1,000 bottles** instead of looking only at machine price tags.

## Key Concepts
- **FOB (Free on Board):** Seller covers export clearance and delivery to origin port. Buyer pays ocean freight, insurance, import duty, and inland transport.
- **DDP (Delivered Duty Paid):** Seller covers almost everything to your door, including duty and inland transport (varies by contract).

## Simple Formulas (heuristic)
- `FOB_1k ≈ (Machine FOB Price Allocation)/1k` *(often treated as 0 when assessing only logistics)*
- `DDP_1k = (FEU_Freight / Bottles_per_FEU * 1000) + (Duty% * CIF_per_1k) + (Inland / Bottles_per_FEU * 1000)`

> **Tip (2026):** When the **World Container Index (WCI)** hovers around ~USD 1,700–2,000/FEU and consolidation is efficient, DDP can be competitive for many routes. Always compute on a per‑1k basis.

## What to Compare
- Ocean freight volatility (±3–8% week‑to‑week typical)
- Duty/tariff scenarios and exemptions
- Demurrage/detention risks
- Bottles‑per‑FEU equivalents (crating strategy)
- Insurance and payment terms (impact on cash flow)

**See also:** `/calculators/ddp_fob_estimator.json`
