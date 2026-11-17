# NatWest Group — Integrated Excess-Return Valuation and Credit / Capital Model

## Case question

What equity value is implied by NatWest's tangible net asset value and the present value of expected returns on tangible equity above the cost of equity, after allowing for credit losses, capital requirements and distributions?

## Canonical deliverable

- [Integrated regulatory-capital and through-cycle credit model — v3](NatWest_Full_Reg_Capital_Through_Cycle_Credit_Model_v3_Audit_Checked.xlsx)
- [Portfolio model review and open items](../../docs/MODEL_REVIEW.md)
- [Source register](../../docs/SOURCES.md)

The v3 workbook is the current canonical NatWest model in this folder. The earlier standalone Analyst v3 workbook is retained only as historical model development and should not be used as the current integrated deliverable.

## Model status

**Status: expanded external analyst model; not a completed bank regulatory-capital forecast or a fully calibrated through-the-cycle credit model.**

The workbook has been expanded to connect the excess-return valuation to operating forecasts, IFRS 9 credit scenarios, risk-weighted assets, regulatory capital and distribution capacity. Mechanical spreadsheet checks do not establish that analyst assumptions are economically calibrated or that regulatory treatment is complete.

No updated per-share valuation is presented here. The prior 556.2p/share output belongs to the earlier simplified model and must not be treated as the output of this integrated workbook until the workbook has been recalculated, the linked forecasts independently reviewed and the valuation bridge revalidated.

## Methodology and model architecture

The workbook contains linked schedules covering:

1. **Credit risk:** reported loan and expected-credit-loss reference data, portfolio assumptions and stage-based loss coverage.
2. **Credit scenarios:** upside, base, downside and extreme-downside macroeconomic paths and scenario weights.
3. **Credit projection:** portfolio balances, impairment and expected-credit-loss projections.
4. **Scenario projection:** probability-weighted impairment path feeding the operating forecast.
5. **RWA engine:** reported risk-type RWA starting point and forecast RWA assumptions.
6. **Regulatory capital:** CET1, AT1, Tier 1, Tier 2 and total capital, capital requirements, buffers, leverage and distributions.
7. **Stress test:** analyst-defined stress overlays and capital impact.
8. **Model governance:** source references, modelling conventions, limitations and outstanding validation requirements.

The excess-return framework remains the primary bank valuation method:

- Forecast earnings and return on tangible equity.
- Deduct the cost of equity from forecast tangible equity to derive residual income.
- Discount explicit and terminal residual income.
- Reconcile the implied value to tangible net asset value and diluted shares.

A conventional industrial-company EV/EBITDA DCF is not the primary valuation method for a deposit-taking bank.

## Data and calibration approach

Reported capital and risk-weighted asset starting points are anchored to NatWest's Q3 2026 Pillar 3 disclosures. Credit exposure, stage and expected-credit-loss reference data are drawn from the FY25 Annual Report, with selected balances calibrated to the more recent loan-book perimeter. The workbook also uses NatWest's published macroeconomic scenario framework and management's stated RWA outlook as forecast anchors.

Where NatWest does not publicly disclose the granular inputs needed to reproduce its internal models, the workbook uses explicitly identified analyst assumptions. These include portfolio-level PD/LGD proxies, exposure growth, stage behaviour, scenario overlays and forward RWA composition.

## Key limitations and outstanding validation

The workbook is an independent external analyst model. It is not NatWest's internal IFRS 9, ICAAP, ILAAP or regulatory capital model, and it is not a PRA supervisory stress test.

The following limitations remain material:

1. **Credit calibration:** granular segment-level PD and LGD curves, default inflows, cures, write-offs, recoveries and stage-transition matrices are not fully calibrated to a complete public historical time series.
2. **Through-the-cycle loss rate:** scenario-weighted forecast impairments require calibration against a longer historical credit-cost series and portfolio-specific loss experience. Scenario convergence alone is not evidence of a normalized through-cycle loss rate.
3. **IFRS 9 staging:** stage migration and lifetime ECL behaviour require more granular origination, arrears, default and cure data than the public disclosures provide.
4. **Basel 3.1:** the RWA schedule is an analyst forecast anchored to disclosed figures and management guidance. It is not a bottom-up exposure-level rebuild of standardised and IRB risk weights, model permissions, output-floor adjustments and transitional arrangements.
5. **Capital instruments:** AT1 and Tier 2 maturity, call, coupon, eligibility amortisation and refinancing schedules require instrument-level modelling.
6. **Capital requirements:** firm-specific supervisory requirements and confidential Pillar 2 guidance cannot be independently reconstructed from public information. Published minimums and buffers should not be mistaken for the full confidential supervisory position.
7. **Valuation integration:** the updated credit and capital forecasts must be recalculated and reconciled through earnings, retained profits, dividends, buybacks, tangible equity and residual income before a new per-share valuation is published.

## Interpretation

This workbook is a substantial expansion of the earlier simplified residual-income model. It is designed to demonstrate how credit performance and regulatory capital constrain a bank's distributable earnings and valuation.

It should be described as an **integrated analyst-built credit and capital framework**, not as a fully validated through-the-cycle credit model or complete regulatory-capital model. No investment recommendation or target price is implied.

**Use:** independent educational modelling only. Not investment advice or a recommendation to transact in any security.
