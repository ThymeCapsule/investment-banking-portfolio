# Investment Banking & Valuation Portfolio

<sub>INDEPENDENT FINANCIAL RESEARCH · MODELLING · VALUATION · TRANSACTION ANALYSIS</sub>

A collection of company valuation and transaction-analysis exercises. Each case distinguishes reported information, market observations and analyst assumptions, and states the scope and limitations of the work.

## Portfolio overview

| Case | Framework | Current model output | Status / principal limitation |
|---|---|---:|---|
| [Signet Jewelers](valuation-case-studies/signet-jewelers/README.md) | Unlevered DCF with FY27 H2 stub | US$140.33/share (Gordon); US$121.21 (6.0x exit) | **Analyst-built case study** · US$118.58 reference price (9 Nov 2026); 69.5% of Gordon EV is terminal value; guidance bridge and H2 working capital remain review items. |
| [Northern Star Resources](valuation-case-studies/northern-star-resources/README.md) | Forecast-period asset NAV | A$13.89/share | **Partial NAV** · FY27–FY36 explicit forecast; zero residual value beyond FY36, with material reserve cash flows excluded. |
| [NatWest Group](valuation-case-studies/natwest-group/README.md) | Excess-return / residual-income | 556.2p/share | **Simplified bank valuation** · Includes linked operating and simplified CET1/RWA/distribution schedules; not a full regulatory-capital or through-cycle credit model. |
| [Frasers Group / Accent Group](transaction-case-studies/frasers-accent/README.md) | M&A / takeover analysis | See case page | **Model rebuild in progress** · Valuation and EPS-accretion workbench, not yet a complete integrated merger model. |

## Current canonical workbooks

- [Signet DCF — Analyst v3](valuation-case-studies/signet-jewelers/Signet_DCF_Analyst_v3.xlsx)
- [Northern Star NAV — Analyst v3](valuation-case-studies/northern-star-resources/Northern_Star_NAV_Analyst_v3.xlsx)
- [NatWest Excess Return — Analyst v3](valuation-case-studies/natwest-group/NatWest_Excess_Return_Analyst_v3.xlsx)

The Analyst v3 files above are the current canonical workbooks for these three valuation cases. Earlier workbook copies and prior PDF summaries have been removed from the canonical case folders to avoid competing versions. No separate valuation memo or PDF summary is being published.

## Analytical approach

The work is organised around a decision question, a traceable model and a conclusion proportionate to the evidence. The portfolio's release discipline is set out in [Modelling Standards](docs/MODELLING_STANDARDS.md).

- Separate source data, analyst assumptions, calculations and outputs.
- Date-stamp valuation inputs and identify mismatched reporting dates.
- Build short, traceable formulas and link schedules into outputs.
- Reconcile sensitivity-table base cases to the main model.
- Include visible model checks, diagnostics and an open-items register.
- Distinguish a finite-horizon NAV from a full reserve-life valuation, and a simplified bank model from a full regulatory-capital forecast.
- Do not present analyst outputs as price targets or investment recommendations.

## Review and source documentation

- [Portfolio model review and open-items register](docs/MODEL_REVIEW.md)
- [Signet DCF review](docs/SIGNET_MODEL_REVIEW.md)
- [Source register and market-data cut-off](docs/SOURCES.md)
- [Modelling Standards](docs/MODELLING_STANDARDS.md)
- [Case Study Template](docs/CASE_STUDY_TEMPLATE.md)

## Data cut-off and use

The three workbook cases use financial bases and market references stated on their respective summary sheets. Market references are snapshots, not live data. Refresh company filings, share counts, market prices, FX, rates and transaction terms before reuse.

Independent educational portfolio work only. These projects are not investment research, investment advice, price targets or recommendations, and do not represent the views of any employer or client.
