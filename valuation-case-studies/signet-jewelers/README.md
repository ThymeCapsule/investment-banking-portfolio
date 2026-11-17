# Signet Jewelers — Unlevered DCF Valuation

## Case question

What indicative standalone equity value is implied by forecast unlevered free cash flow, and how sensitive is that value to WACC, terminal growth and the exit EV/EBITDA assumption?

## Canonical deliverable

- [Signet DCF — Analyst v3 workbook](Signet_DCF_Analyst_v3.xlsx)
- [Detailed DCF review and open items](../../docs/SIGNET_MODEL_REVIEW.md)

The Analyst v3 workbook is the canonical file. Earlier workbook copies and the previous PDF summary have been removed from this case folder so that the repository has one current source of model outputs. No separate memo or PDF summary is published.

## Model snapshot

| Metric | Gordon growth | Exit multiple |
|---|---:|---:|
| Enterprise value | US$4,988.0m | US$4,236.6m |
| Equity value | US$5,514.8m | US$4,763.4m |
| Implied value per share | **US$140.33** | **US$121.21** |
| Reference share price (9 Nov 2026) | US$118.58 | US$118.58 |
| Implied difference to reference | 18.3% | 2.2% |
| Terminal value / EV | 69.5% | — |

Key assumptions: 9.782% WACC, 2.0% Gordon-growth rate and 6.0x exit EV/EBITDA. The exit multiple is an analyst assumption and is not derived from a completed trading-comparables analysis.

## Methodology and model architecture

The workbook contains a model guide, FY27 H2 stub, inputs, DCF, one-page output, WACC / terminal-growth and exit-multiple sensitivities, source notes, guidance bridge, model checks and audit log.

The H2 stub bridges FY27 company guidance to reported year-to-date results. H2 unlevered free cash flow is linked into the DCF rather than relying on a full-year proxy. H2 working capital is set to zero in the base case and separately sensitised; this is an assumption requiring further diligence.

## Model checks and open items

The workbook's mechanical checks pass for the revenue, EBITDA arithmetic, DCF enterprise-value bridge, equity-value bridge, H2 revenue / EBIT / capex bridges, stub FCF tie and cash bridge. The guidance midpoint diagnostic remains **REVIEW**: the model's adjusted EBIT plus annualised H1 D&A proxy is US$55.4m below company adjusted EBITDA guidance. This is a forecast diagnostic, not a formula error.

Principal outstanding items:

1. Reconcile company adjusted EBITDA guidance to the EBIT-plus-D&A proxy without forcing an unsupported adjustment.
2. Validate the H2 working-capital assumption using historical seasonality and operating balance-sheet drivers.
3. Confirm cash, drawn debt, ABL utilisation, letters of credit and debt-like items at a common valuation date.
4. Reconcile diluted shares and post-quarter repurchases / ASR to the chosen market date.
5. Confirm lease treatment consistently across the DCF and any future peer analysis.
6. Challenge terminal margins, reinvestment, terminal ROIC and the high terminal-value contribution.
7. Complete a consistently dated trading-comparables analysis before treating the exit multiple as market-supported.

## Interpretation

This is an analyst-built DCF case study, not a full three-statement forecast, completed trading-comparables analysis, diligence-ready valuation or proprietary investment-bank template. Market price and risk inputs are dated 6–9 November 2026 while cash, debt and share-count inputs are based on 1 August 2026; the date mismatch is disclosed in the workbook.

**Use:** independent educational modelling only. Not investment advice, a price target or a recommendation to buy or sell securities.
