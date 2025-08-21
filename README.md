Otis 90-Minute 3-Statement Model (from blank sheet)

> A clean, time-boxed build of an Otis 3-statement model (IS/BS/CFS), linked, balanced, and able to test management guidance — all in ~90 minutes from a blank workbook.

![status](https://img.shields.io/badge/build-excel-blue)
![scope](https://img.shields.io/badge/scope-3%20statements%20%2B%20debt%2Fbuybacks-green)
![license](https://img.shields.io/badge/license-MIT-lightgrey)

What’s inside

- Completed Excel model** (`model/Otis_3Statement_Completed.xlsx`) and a **blank scaffold** (`model/Otis_3Statement_Blank.xlsx`) for timed runs.
- Source files** (10-K, investor deck, case prompt, slides) under `data/raw/`.
- Docs** that mirror the tutorial step-by-step:
  - `docs/MODEL_GUIDE.md` — full build logic & line-by-line references.
  - `docs/CHECKLIST_90MIN.md` — speed-run checklist.
  - `docs/ASSUMPTIONS.md` — all drivers, guardrails, and why.
  - `docs/FAQ.md` — troubleshooting & common pitfalls.
- Sanity templates** under `scripts/` and `notebooks/` to validate ratios and quick QA.

 TL;DR — Model objective

Build a driver-based**, **linked** 3-statement model for Otis to:
- forecast 2022–2026,
- implement min cash policy,
- allocate excess cash between debt repayment and share repurchases,
- test mgmt guidance: Service rev → ~$10bn by 2026, cumulative FCF ≈ $5bn (’22–’24), **dividend payout 35–40%, and FCF conversion >100%.


Quickstart (5 steps)

1.Clone
   bash
   git clone https://github.com/<your-org>/otis-90min-3statement-model.git
   cd otis-90min-3statement-model

