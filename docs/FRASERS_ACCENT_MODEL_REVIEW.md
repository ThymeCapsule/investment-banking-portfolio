# Frasers Group / Accent Group — Transaction Model Review

**Review date:** 11 November 2026  
**Working file:** Frasers_Accent_Takeover_Model_v7_Review_Corrected.xlsx  
**Status:** Rebuild required; not yet a complete integrated merger model.

## 1. What the current workbook does

The workbook contains an Accent standalone forecast and rent-adjusted FCFF DCF, three operating scenarios, offer-premium analysis, trading comparables, a limited precedent-transaction section, a valuation football field and an illustrative Frasers EPS accretion / dilution calculation.

The v7 working file was recalculated in LibreOffice on 11 November 2026:
- No formula-error values (#REF!, #DIV/0!, #VALUE!, #NAME?, #N/A) were detected.
- The programmed historical tie-out, DCF sensitivity-centre, terminal FCFF, scenario-selection, share-count sanity, WACC-versus-growth and offer-price linkage checks returned PASS.
- Seven source / methodology gates remained OPEN.
- Four model-completeness gates were added and remain OPEN: sources & uses / funding waterfall; debt schedule; purchase-price allocation / pro forma balance sheet; integrated buyer / target forecasts.
- The workbook now states “FORMULA CHECKS PASS - SOURCE / SCOPE GATES OPEN” rather than “ALL CHECKS PASS”.

These are mechanical workbook checks only. They do not constitute an independent audit of every formula, source, accounting treatment or transaction assumption.

## 2. Current model-derived outputs

| Metric | Recalculated output |
|---|---:|
| Offer price | A$0.65/share |
| Selected base-case DCF | Approximately A$1.01/share |
| Downside scenario | Approximately A$0.75/share |
| Management-plan scenario | Approximately A$1.40/share |
| Illustrative FY28 EPS accretion | Approximately 6.1% |
| Open source / model-scope gates | 11 |

The outputs depend on analyst assumptions for operating margins, growth, WACC, terminal growth, synergies and financing. They are not a fairness opinion, target price or investment recommendation. The accretion calculation is illustrative and does not yet incorporate a fully integrated pro forma balance sheet, purchase accounting or detailed debt schedule.

## 3. Critical issues to resolve

### A. Transaction consideration and share count

The workbook flags a difference between the A$315.8m maximum consideration referenced in one source and approximately A$301.3m implied by 463.5m shares at A$0.65. Reconcile the bidder's statement, offer mechanics, relevant share classes, options and fully diluted share count. Do not use a derived residual share count as a fact.

### B. Ownership and accounting treatment

Refresh Frasers' latest relevant interest and determine the correct accounting treatment at each ownership level. The model must distinguish an existing associate investment from newly acquired shares and must not attribute 100% of Accent earnings to Frasers without a supported consolidation assumption.

### C. Standalone financials and forecast

Reconcile Accent's reported and underlying historical financials to the Appendix 4E and financial statements. Build a consistent standalone forecast with revenue, gross margin, operating expenses, lease accounting, tax, working capital, capex, depreciation and net debt. The current operating cases are analyst scenarios and need source-backed driver support.

### D. Lease accounting

The DCF uses rent-adjusted / pre-AASB 16 operating earnings and excludes lease liabilities from net debt. Confirm that cash rent, lease depreciation and lease interest are treated consistently in historicals, forecast FCFF, enterprise value, peer multiples and precedent data.

### E. Comps and precedents

The current peer set mixes currencies, fiscal year-ends, reporting periods and levels of comparability. Some EBIT / NPAT figures are derived or proxy measures. Rebuild the peer set with explicit inclusion criteria, common valuation date, consistent lease basis and clear LTM / NTM labels. The two precedent examples do not support a statistically meaningful control-premium range; remove placeholder premium conclusions until the sample is expanded.

### F. Frasers funding and accretion / dilution

The current model assumes a cash-funded transaction and uses a simplified cost-of-debt approach. A full merger model needs sources & uses, cash available, debt capacity, debt tranches, fees, amortisation, interest on average debt, tax effects and any refinancing. Add scrip consideration only as a separately controlled scenario with share issuance and dilution.

### G. Purchase accounting and pro forma statements

Build purchase-price allocation, asset / intangible fair-value step-ups, deferred tax, goodwill, transaction costs and a pro forma opening balance sheet. Link these adjustments into pro forma depreciation / amortisation, interest, tax and EPS.

### H. Synergies and integration costs

Separate revenue and cost synergies, gross and net synergies, run-rate and phased delivery, probability weighting, implementation costs and one-off integration costs. Include a zero-synergy downside and break-even synergy analysis.

## 4. Target workbook architecture

| Order | Worksheet | Purpose |
|---:|---|---|
| 1 | Cover / Guide | Scope, date, units, version, sheet map and limitations |
| 2 | Summary | Transaction snapshot, valuation range, key outputs and recommendation framework |
| 3 | ModelChecks | Formula, accounting, sources & uses, balance-sheet and source-gate checks |
| 4 | Timing | Financial year-ends, stub periods, close date and forecast timing |
| 5 | DealAssumptions | Offer price, ownership, consideration mix, fees, close date and transaction terms |
| 6 | Sources_Uses | Purchase consideration, refinancing, fees and funding sources |
| 7 | Buyer_Historical | Frasers reported and adjusted historical financials |
| 8 | Target_Historical | Accent reported and adjusted historical financials |
| 9 | Buyer_Forecast | Standalone Frasers earnings / EPS assumptions |
| 10 | Target_Forecast | Accent standalone operating forecast and linked statements |
| 11 | Debt_Schedule | Existing and new debt, cash funding, interest, fees and amortisation |
| 12 | Purchase_Accounting | Asset step-ups, intangibles, deferred tax and goodwill |
| 13 | ProForma_BS | Combined opening balance sheet and purchase accounting |
| 14 | ProForma_IS | Combined earnings, synergies, financing and amortisation |
| 15 | Accretion_Dilution | Standalone vs pro forma EPS by period and funding case |
| 16 | Valuation | Target DCF and enterprise-to-equity bridge |
| 17 | Trading_Comps | Comparable companies with standardised metrics |
| 18 | Precedents | Sourced deal screen and transaction multiples / premiums |
| 19 | Sensitivities | Offer price, funding mix, rates, synergies, WACC and terminal growth |
| 20 | Sources | Source register, analyst assumptions and open diligence questions |

## 5. Release gates

- [ ] Bidder's statement and offer terms independently reconciled.
- [ ] Fully diluted share count and consideration reconciled.
- [ ] Ownership and accounting treatment documented.
- [ ] Historical statements tied to primary filings.
- [ ] Standalone forecasts linked and internally consistent.
- [ ] Sources equal uses.
- [ ] Debt schedule and financing costs integrated.
- [ ] Purchase accounting and pro forma balance sheet complete.
- [ ] Pro forma EPS and synergies reconciled.
- [ ] DCF and comparable-company outputs tied to valuation summary.
- [ ] Sensitivity centres tie to base case.
- [ ] All source and model-scope gates closed or clearly disclosed.

## 6. Publication statement

Until these gates are met, describe the workbook as a **takeover valuation and illustrative accretion / dilution model under development**. Do not describe it as a completed merger model or a fully validated investment-banking transaction model.
