# Investment Banking & Valuation Portfolio

<sub>INDEPENDENT FINANCIAL RESEARCH · MODELLING · VALUATION · TRANSACTION ANALYSIS</sub>

A collection of company valuation and transaction-analysis exercises. Each case distinguishes reported information, market observations and analyst assumptions, and states the scope and limitations of the work.

## Portfolio overview

| Case | Framework | Current model output | Status / principal limitation |
|---|---|---:|---|
| [Signet Jewelers](valuation-case-studies/signet-jewelers/README.md) | Unlevered DCF with FY27 H2 stub | US$140.33/share (Gordon); US$121.21 (6.0x exit) | Analyst-built case study. US$118.58 reference price (9 Nov 2026); 69.5% of Gordon EV is terminal value. Guidance bridge and H2 working capital remain review items. |
| [Northern Star Resources](valuation-case-studies/northern-star-resources/README.md) | Forecast-period asset NAV | A$13.89/share | Partial NAV. FY27–FY36 explicit forecast; zero residual value beyond FY36, with material reserve cash flows excluded. |
| [NatWest Group](valuation-case-studies/natwest-group/README.md) | Excess-return valuation linked to credit and capital schedules | No current per-share value published | Expanded analyst framework. Credit calibration, Basel 3.1 RWA, capital instruments and valuation integration remain open. The former 556.2p output belongs to an earlier simplified model. |
| [Frasers Group / Accent Group](transaction-case-studies/frasers-accent/README.md) | Takeover valuation and illustrative accretion / dilution | A$0.65 offer price; illustrative model outputs in review note | In development. Not a complete integrated merger model; the working workbook is not currently published in this repository. |

## Current canonical workbooks

- [Signet DCF — Analyst v3](valuation-case-studies/signet-jewelers/Signet_DCF_Analyst_v3.xlsx)
- [Northern Star NAV — Analyst v3](valuation-case-studies/northern-star-resources/Northern_Star_NAV_Analyst_v3.xlsx)
- [NatWest integrated credit and capital model — v3](valuation-case-studies/natwest-group/NatWest_Full_Reg_Capital_Through_Cycle_Credit_Model_v3_Audit_Checked.xlsx)

The Analyst v3 Signet and Northern Star files and the integrated NatWest v3 file above are the canonical workbooks for their respective cases. Earlier NatWest standalone excess-return work is historical development, not the current integrated deliverable. No new NatWest per-share valuation is published pending recalculation and review of the integrated model.

The Frasers / Accent working workbook is not yet published in this repository. Its current state and required rebuild are documented in the [transaction model review](docs/FRASERS_ACCENT_MODEL_REVIEW.md).

## Additional financial modelling

- [LVMH Integrated Forecast and DCF Model](LVMH_Integrated_Forecast_DCF_Model_v1.xlsx)

The LVMH workbook combines reported historical financial and segment data with an analyst-built operating forecast, discounted cash flow valuation and WACC / terminal-growth sensitivity analysis. Forecast assumptions are explicitly identified. This is an illustrative valuation model, not a fully integrated three-statement model; balance-sheet roll-forwards and lease treatment remain limitations, and the output is not an investment recommendation or price target.

## Analytical approach

The work is organised around a decision question, a traceable model and a conclusion proportionate to the evidence. The portfolio's release discipline is set out in [Modelling Standards](docs/MODELLING_STANDARDS.md).

- Separate source data, analyst assumptions, calculations and outputs.
- Date-stamp valuation inputs and identify mismatched reporting dates.
- Build short, traceable formulas and link schedules into outputs.
- Reconcile sensitivity-table base cases to the main model.
- Include visible model checks, diagnostics and an open-items register.
- Distinguish a finite-horizon NAV from a full reserve-life valuation, and a simplified bank model from a fully calibrated regulatory-capital forecast.
- Do not present analyst outputs as price targets or investment recommendations.

## Review and source documentation

- [Portfolio model review and open-items register](docs/MODEL_REVIEW.md)
- [Signet DCF review](docs/SIGNET_MODEL_REVIEW.md)
- [Frasers / Accent transaction model review](docs/FRASERS_ACCENT_MODEL_REVIEW.md)
- [Source register and market-data cut-off](docs/SOURCES.md)
- [Modelling Standards](docs/MODELLING_STANDARDS.md)
- [Case Study Template](docs/CASE_STUDY_TEMPLATE.md)

## Data cut-off and use

Market references and financial reporting periods are case-specific and are stated in the relevant workbook and review note. Market references are snapshots, not live data. Refresh company filings, share counts, market prices, FX, rates and transaction terms before reuse.

Independent educational portfolio work only. These projects are not investment research, investment advice, price targets or recommendations, and do not represent the views of any employer or client.
