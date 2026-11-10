# Investment Banking & Valuation Portfolio

Independent financial modelling, valuation and transaction-analysis projects.

This repository is being developed as a structured portfolio demonstrating the analytical disciplines used in investment banking, corporate finance and public-markets research: financial statement analysis, valuation, scenario analysis, transaction rationale and clear communication of conclusions.

> **Status:** Development portfolio. Existing models are undergoing validation. Outputs should not be treated as final investment conclusions until the review items documented in each project have been resolved.

## Projects

### 1. Signet Jewelers — Discounted Cash Flow Valuation
**Method:** Unlevered DCF / enterprise-to-equity value bridge  
**Status:** Model built; validation and documentation in progress.

The case study examines operating drivers, forecast free cash flow, terminal value and implied equity value. The next review focuses on the cash/debt and diluted-share bridge, treatment of leases and other adjustments, forecast assumptions, and cross-checks against trading comparables and precedent transactions.

- [Signet model review](docs/SIGNET_MODEL_REVIEW.md)
- [Signet case study](projects/signet-jewelers/README.md)

### 2. Northern Star Resources — Net Asset Value
**Method:** Asset-level / life-of-mine NAV  
**Status:** Model built; key terminal-value and operating assumptions require reconciliation.

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
| 1 | Signet DCF completion | Reconciled forecast, enterprise-to-equity bridge, sensitivities, comps cross-check and investment conclusion |
| 2 | M&A transaction analysis | Deal overview, strategic rationale, valuation, sources & uses, financing, accretion/dilution and key risks |
| 3 | Three-statement model | Integrated income statement, balance sheet and cash flow, with scenario controls |
| 4 | Trading comparables & precedent transactions | Peer selection, financial metrics, valuation multiples and adjustments |
| 5 | LBO model | Sources & uses, debt schedule, cash sweep, returns analysis and sensitivities |

## Repository structure

```text
investment-banking-portfolio/
├── README.md
├── docs/
│   └── SIGNET_MODEL_REVIEW.md
└── projects/
    ├── signet-jewelers/
    │   └── README.md
    ├── northern-star/
    │   └── README.md
    └── natwest/
        └── README.md
```

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
