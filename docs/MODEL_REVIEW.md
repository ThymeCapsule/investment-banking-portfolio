# Model review and control log

## Export and calculation controls

The three reviewed workbooks were exported and re-imported after editing. Formula-error scans returned no `#REF!`, `#DIV/0!`, `#VALUE!`, `#NAME?` or `#N/A` cells. Base-case sensitivity checks were tied to each model's central valuation output.

| Workbook | Base output | Control check |
|---|---:|---|
| Signet DCF | US$155.83/share (Gordon); US$136.44/share (exit) | Gordon WACC / terminal growth centre equals the DCF output; exit WACC / multiple centre equals the exit output. |
| Northern Star NAV | A$13.89/share | Gold / FX sensitivity centre equals NAV/share; discount-rate / zero-residual sensitivity at 8.0% equals NAV/share. |
| NatWest excess-return | 532.6p/share | Cost-of-equity / terminal RoTE sensitivity centre equals excess-return value/share. |

## Main judgement calls and unresolved items

### Signet Jewelers
- WACC 9.782%, perpetual growth 2.0% and 6.0x exit EV/EBITDA are analyst assumptions.
- FY27 model EBITDA proxy (adjusted EBIT + D&A) is below the lower end of company adjusted EBITDA guidance. No unsupported D&A or EBITDA adjustment has been forced into the model.
- Net working capital is forecast at 10% of change in revenue; this is a simplifying assumption, not a seasonally normalised historical build.
- The model uses a 1 Aug 2026 balance-sheet/share-count base date and 9 Nov 2026 market price. Later repurchases and the announced ASR are not reflected in the cash/share bridge.
- ABL utilisation / letters of credit and lease treatment need a filing-level bridge before live use.

### Northern Star Resources
- NAV is finite-horizon FY27-FY36 only. The 31 Mar 2026 Group Ore Reserve is 28.419Moz, including 5.508Moz at Hemi; derived ex-Hemi reserves are 22.911Moz. No residual is assigned; about 6.436Moz existing-operations reserves and 2.658Moz Hemi reserves are outside the modelled production horizon.
- The forecast is not reserve-engineered. FY27 uses company guidance midpoints; FY28-FY36 mine production, AISC, capex and Hemi ramp-up are analyst scenarios.
- FY27 total growth capital guidance includes Hemi. The model uses A$1.635bn ex-Hemi plus A$225m Hemi = A$1.860bn total midpoint. Sustaining capital midpoint is A$882.5m and is included in AISC.
- Pogo is in Alaska; no single WA-style royalty overlay is applied across the portfolio. Asset-level royalty, tax and closure-cost schedules remain open.
- The 8.0% nominal AUD asset discount rate is judgemental; CAPM cross-check is shown separately and not used in NAV.

### NatWest Group
- Cost of equity uses UK ERP from Damodaran's country-risk table and a 1.10 analyst beta.
- Four-year / five-year operating projections are stylised; the model does not forecast CET1, RWAs, regulatory capital requirements, impairment through a cycle or distribution constraints.
- P/TNAV cross-check uses three external names only; no regression or transaction multiple is presented. HSBC is a global cross-border reference, not a pure domestic UK peer.
- Tangible equity growth and the terminal RoTE are explicit assumptions, not company guidance.

## Interpretation discipline

The valuation outputs should be discussed as model-derived scenarios with explicit assumptions. The Northern Star figure is not a full NAV. Signet's exit-method case is provisional pending EBITDA reconciliation and comparable-company analysis. NatWest requires a fuller capital and credit build.
