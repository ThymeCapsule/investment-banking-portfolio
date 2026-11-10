# Investment Banking & Valuation Portfolio

Independent financial modelling, valuation and transaction-analysis projects.

This repository demonstrates the analytical disciplines used in investment banking, corporate finance and public-markets research: financial statement analysis, valuation, scenario analysis, transaction rationale and clear communication of conclusions.

> **Portfolio status:** Active development. The Signet DCF has been refreshed and published with dated market inputs, formula recalculation and explicit limitations. The remaining case studies are being validated.

## Projects

### 1. Signet Jewelers — Discounted Cash Flow Valuation

**Method:** Unlevered DCF / enterprise-to-equity value bridge  
**Status:** Reviewed workbook published; historical calibration and trading-comps work outstanding.

The model forecasts unlevered free cash flow through FY32 and applies both a Gordon-growth terminal value and an exit-multiple cross-check.

- [Reviewed Signet DCF workbook](projects/signet-jewelers/Signet_DCF_Reviewed_2026-11-10.xlsx)
- [Signet case study and valuation snapshot](projects/signet-jewelers/README.md)
- [Detailed model review and diligence checklist](docs/SIGNET_MODEL_REVIEW.md)

The current model outputs are US$158.47 per share under the 2.0% perpetuity-growth method and US$137.16 under the 6.0x exit-multiple method. The reference share price is US$118.58 (9 Nov 2026). The comparison is not synchronous because financial inputs are from 1 Aug 2026 and market inputs are from 6–9 Nov 2026. These are model outputs, not validated target prices.

### 2. Northern Star Resources — Net Asset Value

**Method:** Asset-level / life-of-mine NAV  
**Status:** Model built; terminal-value methodology and operating assumptions require reconciliation.

The case study considers mine-level cash flows, commodity-price assumptions, operating costs, capital expenditure, tax, rehabilitation and discounting. A material inconsistency between the residual-value input and the stated zero-terminal-value NAV methodology is flagged for resolution.

- [Northern Star case study](projects/northern-star/README.md)

### 3. NatWest Group — Excess Return Valuation

**Method:** Residual income / excess-return valuation  
**Status:** Model built; assumptions and bank-specific cross-checks require further validation.

The analysis considers tangible book value, return on tangible equity, cost of equity and excess returns. Further work is required on CAPM inputs, capital distributions, regulatory capital and peer benchmarking.

- [NatWest case study](projects/natwest/README.md)

## Planned additions

| Priority | Project | Deliverables |
|---|---|---|
| 1 | Signet DCF completion | Historical working-capital calibration, debt / ASR reconciliation, trading comps and investment conclusion |
| 2 | M&A transaction analysis | Deal overview, strategic rationale, valuation, sources & uses, financing, accretion/dilution and key risks |
| 3 | Three-statement model | Integrated income statement, balance sheet and cash flow, with scenario controls |
| 4 | Trading comparables & precedent transactions | Peer selection, financial metrics, valuation multiples and adjustments |
| 5 | LBO model | Sources & uses, debt schedule, cash sweep, returns analysis and sensitivities |

## Modelling and review standards

Each completed project should include:

1. **Executive summary** — question, conclusion and key valuation drivers.
2. **Business and industry overview** — business model, segment economics and relevant industry dynamics.
3. **Historical analysis** — revenue, margins, working capital, capital expenditure, cash conversion and balance-sheet trends.
4. **Forecast methodology** — explicit operating drivers and transparent assumptions.
5. **Valuation** — methodology, calculations, enterprise-to-equity bridge and per-share value where relevant.
6. **Sensitivities** — key operating and valuation variables, including downside cases.
7. **Cross-checks** — relevant market multiples, precedent transactions or alternative valuation methods.
8. **Sources and limitations** — dated source register, assumptions, unresolved items and model limitations.

## Disclaimer

All work is independently prepared for educational and professional portfolio purposes. It is not investment advice, a recommendation to buy or sell securities, or research produced on behalf of an employer, client or financial institution. Market data and assumptions must be checked against current primary sources before use.
