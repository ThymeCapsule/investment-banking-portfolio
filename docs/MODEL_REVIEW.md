# Portfolio Model Review and Open-Items Register

**Review basis:** repository and workbook review of the Analyst v3 valuation workbooks, 17 November 2026. Mechanical checks are reported as displayed in each workbook. A PASS means the specified arithmetic test passes; it is not independent verification of every input, assumption or methodology.

## Portfolio-level status

| Case | Analyst v3 output | Mechanical check status | Key remaining limitation |
|---|---:|---|---|
| Signet Jewelers | US$140.33/share Gordon; US$121.21/share exit | Core bridges PASS; guidance midpoint diagnostic REVIEW | H2 working capital, guidance reconciliation, capital structure and terminal-value dependence require further diligence. |
| Northern Star Resources | A$13.89/share forecast-period NAV | All displayed checks PASS | FY27–FY36 finite horizon; reserve cash flows beyond FY36 excluded; Hemi and asset-level schedules remain scenario-based. |
| NatWest Group | No updated integrated-model valuation published | Mechanical workbook checks only; economic calibration remains open | Analyst-proxy PD/LGD and stage behaviour; no fully calibrated through-cycle loss rate or exposure-level Basel 3.1 rebuild. |
| Frasers / Accent | See transaction case page | Separate workbook review | Valuation and EPS-accretion workbench remains short of a complete integrated merger model. |

## Signet Jewelers

The canonical workbook is [Signet_DCF_Analyst_v3.xlsx](../valuation-case-studies/signet-jewelers/Signet_DCF_Analyst_v3.xlsx). Its summary sheet reports US$140.33/share under Gordon growth and US$121.21/share under a 6.0x exit multiple, against a US$118.58 reference share price dated 9 November 2026. WACC is 9.782%, terminal growth is 2.0%, and Gordon terminal value is 69.5% of enterprise value.

The model's revenue, EBITDA arithmetic, DCF EV, equity bridge, H2 revenue / adjusted EBIT / capex, stub FCF and cash bridge checks pass. The guidance midpoint diagnostic is REVIEW, with a US$55.4m gap between the adjusted EBIT plus annualised H1 D&A proxy and company adjusted EBITDA guidance. This is a forecast diagnostic, not a formula error.

Open items include guidance reconciliation, seasonally calibrated H2 working capital, ABL / debt-like items, post-quarter buybacks and ASR, diluted shares, lease treatment, terminal assumptions and trading comparables. The valuation-date mismatch between 1 August 2026 financial inputs and 6–9 November market / risk references remains disclosed.

## Northern Star Resources

The canonical workbook is [Northern_Star_NAV_Analyst_v3.xlsx](../valuation-case-studies/northern-star-resources/Northern_Star_NAV_Analyst_v3.xlsx). It reports A$19.93bn asset NAV, A$19.77bn equity NAV and A$13.89/share forecast-period NAV. The explicit horizon is FY27–FY36 with zero residual value beyond FY36. The reserve reconciliation identifies approximately 6.436Moz of existing-operations reserves and 2.658Moz of Hemi reserves remaining beyond the modelled horizon.

Displayed checks pass for the asset and equity NAV bridges, per-share bridge, reserve reconciliations, FY27 production guidance and reserve total. The main limitation is scope: the model excludes value from reserve cash flows beyond FY36. FY28–FY36 operating assumptions and Hemi development timing / ramp-up are analyst scenarios. Asset-level production, royalties, tax, closure costs and capex require further validation.

Do not describe this as a full reserve-life NAV, full fair-value conclusion or price target.

## NatWest Group

The canonical workbook is [NatWest_Full_Reg_Capital_Through_Cycle_Credit_Model_v3_Audit_Checked.xlsx](../valuation-case-studies/natwest-group/NatWest_Full_Reg_Capital_Through_Cycle_Credit_Model_v3_Audit_Checked.xlsx). The case methodology and scope are documented in the [NatWest case page](../valuation-case-studies/natwest-group/README.md).

The expanded workbook links the operating forecast and excess-return framework to IFRS 9 credit scenarios, an RWA forecast, regulatory-capital schedules, distribution constraints and analyst stress overlays. Reported starting points are anchored to NatWest's Q3 2026 Pillar 3 disclosures; FY25 Annual Report data inform the stage / segment credit reference set.

Do not carry forward the prior 556.2p/share output as the integrated-model valuation. No new per-share value is published pending recalculation and review of the updated linked forecasts.

Material open items are granular PD/LGD calibration, Stage 1/2/3 migration and cure behaviour, default inflows and recoveries, historical through-cycle credit-cost calibration, bottom-up Basel 3.1 RWA and output-floor treatment, firm-specific supervisory requirements, and instrument-level AT1 / Tier 2 maturity and eligibility schedules. The model is an external analyst framework, not NatWest's internal IFRS 9 / ICAAP model or a PRA supervisory stress test.

## Frasers Group / Accent Group

The separate transaction-model review remains in [Frasers / Accent Model Review](FRASERS_ACCENT_MODEL_REVIEW.md). The model should continue to be described as a valuation and EPS-accretion workbench until sources and uses, financing, purchase-price allocation, pro forma statements, synergy timing and full model checks are complete.

## Interpretation and release discipline

A formula check passing means only that the specific programmed test passed. It does not prove that the underlying assumption is correct, that a formula is conceptually appropriate, or that a model is complete.

A case may be published as a work-in-progress if scope and limitations are explicit. Do not describe an incomplete model as fully audited, diligence-ready, “industry standard” or equivalent to a proprietary investment-bank template.
