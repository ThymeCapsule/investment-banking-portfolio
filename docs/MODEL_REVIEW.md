# Portfolio Model Review and Open-Items Register

**Review basis:** documentation and repository consistency review, 11 November 2026. This is not an independent audit of every formula in the three published valuation workbooks. Existing workbook checks are described as recorded by the project; they should be rerun after any workbook change.

## Portfolio-level status

| Case | Current output shown in repository | Review status | Release blocker |
|---|---:|---|---|
| Signet Jewelers | Conflicting per-share outputs across published files | **Hold headline output** | Recalculate the canonical workbook and reconcile workbook, PDF, README and review note. |
| Northern Star Resources | A$13.89/share | **Partial NAV** | Explicit FY27–FY36 horizon omits reserve cash flows beyond FY36; mine schedules and asset-level fiscal items need further work. |
| NatWest Group | 532.6p/share | **Simplified residual-income model** | No integrated regulatory-capital, RWA and through-cycle credit-loss forecast. |
| Frasers / Accent | Local working workbook; not yet published in this repository | **Transaction model in rebuild** | Source gates and model-completeness gates remain open; not yet a complete integrated merger model. |

## Signet Jewelers

The portfolio index and model review note show US$155.83 / US$136.44 per share, while the case-study README and separate project workbook copy show US$158.47 / US$137.16. The repository contains multiple workbook copies. The discrepancy is unresolved; neither set of figures should be treated as the final published output until the canonical file is identified and recalculated.

Other open items include FY27 EBITDA guidance reconciliation, seasonally normalised working capital, D&A and capex calibration, ABL utilisation / letters of credit, post-quarter buybacks and ASR, lease treatment, and trading comparables.

## Northern Star Resources

The current canonical case describes a finite FY27–FY36 forecast with zero residual value and A$13.89/share forecast-period NAV. The result excludes reserve tonnes and potential cash flows outside the modelled horizon. The model is not reserve-engineered. Production, costs, Hemi ramp-up, royalties, tax and closure costs require asset-level validation.

Do not describe the current output as a full NAV, fair value or target price.

## NatWest Group

The 532.6p/share output is based on a simplified residual-income framework. Cost of equity, terminal RoTE and tangible-equity growth are assumptions. The model does not fully project CET1, RWA, regulatory buffers, credit impairments through a cycle or distribution capacity. The peer P/TNAV sample is limited and not fully like-for-like.

## Frasers Group / Accent Group

The local working workbook was updated to v7 and recalculated in LibreOffice on 11 November 2026. No formula-error values (#REF!, #DIV/0!, #VALUE!, #NAME?, #N/A) were detected after recalculation. The programmed formula checks passed. Seven source / methodology gates and four model-completeness gates remain OPEN, for eleven open gates in total. The workbook status now explicitly reads “FORMULA CHECKS PASS - SOURCE / SCOPE GATES OPEN”; this is not a claim that all model checks are complete.

The v7 workbook currently produces a base-case DCF value of approximately A$1.01/share, a scenario range of approximately A$0.75–A$1.40/share and illustrative FY28 EPS accretion of approximately 6.1%. These are model outputs under analyst assumptions, not validated conclusions. Key open items include:

- Reconcile the A$315.8m headline maximum consideration with the A$301.3m implied by 463.5m shares at A$0.65; confirm offer mechanics in the bidder's statement.
- Refresh Frasers' and Accent's current holdings, share counts, share prices and FX.
- Revalidate risk-free rate, ERP, beta, cost of debt and capital structure.
- Support operating scenarios and synergies; run a zero-synergy downside.
- Rebuild peer and precedent analysis on consistent dates and accounting definitions.
- Confirm lease treatment throughout DCF, enterprise-value bridge and comparables.
- Build full sources & uses, debt schedule, purchase-price allocation, pro forma balance sheet and integrated buyer / target forecasts.

The detailed transaction-model review is in [Frasers / Accent Model Review](FRASERS_ACCENT_MODEL_REVIEW.md).

## Interpretation and release discipline

A formula check passing means only that the specific programmed test passed. It does not prove that the underlying assumption is correct, that a formula is conceptually appropriate, or that a model is complete.

A case may be published as a work-in-progress if the scope and limitations are explicit. Do not publish a headline valuation where key workbook and summary outputs disagree. Do not describe an incomplete model as “fully reviewed”, “diligence-ready” or “industry standard”.
