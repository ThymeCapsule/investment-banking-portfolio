# Financial Modelling Standards

These standards define the minimum release discipline for the portfolio. They are intended to make models understandable, traceable, flexible and reviewable by another analyst. They are not a claim that any model is equivalent to a bank's internal templates, transaction diligence or formal quality-control process.

## 1. Model architecture

Use a clear workbook flow. The exact tabs depend on the valuation method, but the reader should be able to move from the answer to its assumptions and then to the calculation engine.

1. **Cover / guide:** purpose, company, valuation date, currency, units, version, preparer, model status and sheet map.
2. **Summary / outputs:** key valuation results, scenario range, key assumptions, investment or transaction conclusion and principal risks.
3. **Checks:** formula, accounting, source and transaction checks with PASS / REVIEW / OPEN status.
4. **Timing:** financial year-end, valuation date, stub periods, forecast periods and discounting convention.
5. **Inputs / scenarios:** editable assumptions, units, source, date, rationale and scenario selector.
6. **Historical financials:** reported figures, analyst adjustments and reconciliation to filings.
7. **Operating forecast:** drivers and linked forecast statements / schedules.
8. **Valuation / transaction calculations:** DCF, NAV, residual income, trading comps, precedent transactions, LBO or merger calculations as applicable.
9. **Sensitivities:** key value drivers and scenario outputs; central case must tie to the base model.
10. **Sources / notes:** source register, assumptions, definitions, limitations and unresolved questions.

Do not add tabs solely to make the workbook look sophisticated. Every sheet should have a defined purpose and feed another part of the analysis or document an important control.

## 2. Formula and formatting conventions

- Separate hard-coded inputs, formulas and inter-sheet links visually and consistently.
- Use one unit and sign convention per schedule; label currency and units in every major section.
- Keep formulas short enough to audit. Build supporting schedules rather than burying multiple calculations in one formula.
- Avoid hard-coded constants inside formulas. Put material assumptions in a clearly labelled input cell.
- Use consistent forecast columns, date headers, number formats and sign conventions.
- Use explicit labels for actual, estimate, forecast, management guidance and analyst scenario.
- Do not hide material assumptions in comments, merged cells or narrative text.
- Avoid volatile formulas and unnecessary circularity. If circularity is required, document the switch and calculation method.
- Preserve formula integrity when adding rows, columns or scenario cases.

## 3. Source and assumption discipline

Every material hard-coded input should have a source name and direct URL or filing reference; publication / observation date and retrieval date; period, currency, unit and accounting basis; status as reported fact, market observation, derived figure or analyst assumption; calculation or adjustment where derived; and rationale for judgemental inputs.

Use primary company filings, exchange releases, regulatory disclosures and transaction documents first. Secondary sources may corroborate or contextualise but should not silently replace primary evidence. Never label an analyst estimate as company guidance.

## 4. Model integrity checks

Checks must be visible, specific and linked to the calculation they test. At minimum, include relevant tests for:

- Formula errors and broken references.
- Historical financial statement tie-outs.
- Balance sheet balance and cash-flow-to-cash reconciliation, where three statements are modelled.
- Opening balance plus movements equals closing balance for debt, shares, cash and tangible equity.
- Sources equal uses and purchase consideration bridge, for transactions.
- Valuation bridge from enterprise value to equity value.
- Sensitivity-table centre equals base-case output.
- WACC greater than terminal growth for Gordon growth.
- Scenario selector agrees with selected scenario output.
- Share count, currency, valuation date and units are consistent.
- Key downside cases and source gates are clearly flagged.

A PASS on a formula check is not proof that the assumption or methodology is correct. Separate mechanical checks from source-verification gates and judgemental review items.

## 5. Valuation-specific requirements

### Industrial / consumer DCF
- Forecast operating drivers and link EBIT, tax, D&A, capex and working capital to FCFF.
- Explain WACC, capital structure, tax treatment, terminal growth and terminal-year reinvestment.
- Present Gordon-growth and exit-multiple terminal values separately.
- Disclose terminal value as a percentage of enterprise value.
- Reconcile enterprise value to equity value, net debt, debt-like items and diluted shares.
- Cross-check against trading comparables and relevant transactions where evidence is available.

### Mining NAV
- Build asset-level production, grade, recovery, cost, capex, royalty, tax and closure schedules.
- Reconcile reserve/resource basis and mine life to technical disclosures.
- Separate sustaining and growth capital and avoid double counting sustaining capex in AISC.
- Apply jurisdiction-specific tax and royalty terms.
- Explain nominal / real basis, currency and asset-risk discount rates.
- Distinguish finite-horizon forecast NAV from reserve-life NAV and going-concern value.

### Bank residual-income valuation
- Reconcile tangible ordinary equity / TNAV to reported balance sheet and shares.
- Forecast RoTE, cost of equity, CET1, RWA, capital generation and distributions.
- Include impairment / credit-loss assumptions and regulatory capital constraints.
- Link retained earnings, dividends and buybacks to tangible equity.
- Cross-check P/TNAV against a defensible peer set with comparable RoTE, growth and risk.

## 6. M&A / merger model requirements

A transaction valuation is not a merger model. A complete merger-model workstream should, where relevant, include:

1. Transaction overview, buyer rationale, target overview and deal terms.
2. Target and acquirer historical financials and standalone forecasts.
3. Offer price, fully diluted shares, equity value and enterprise value.
4. Sources & uses, cash / debt / stock consideration and transaction fees.
5. Financing schedule, interest expense, fees, amortisation and cash/debt impact.
6. Purchase-price allocation, asset write-ups, deferred tax and goodwill.
7. Pro forma balance sheet and combined income statement.
8. Synergy build, timing, probability, implementation costs and tax impact.
9. Accretion / dilution with standalone EPS, pro forma EPS and share issuance.
10. Sensitivities for offer price, financing mix, interest rates, synergies and close date.
11. Model checks: sources equal uses, balance sheet balances, debt and cash reconcile, and all deal assumptions flow through the model.

For a partial stake or strategic investment, model ownership and accounting treatment explicitly. Do not assume full consolidation or full target earnings attribution unless the transaction terms and accounting treatment support it.

## 7. Publication standard

Each case-study page must state the question, method, valuation date, key outputs, assumptions, conclusion, risks, source base, limitations and open items. The workbook, summary PDF, README and portfolio index must agree.

Use status labels accurately: **In progress**, **Reconciliation required**, **Partial analysis**, **Reviewed for stated scope**. Avoid “industry standard”, “diligence-ready” or “investment-banking quality” unless the work has actually met the relevant scope and review tests.

## Reference material

- [CohnReznick — Financial modelling best practices](https://www.cohnreznick.com/insights/financial-modeling-best-practices-a-practical-guide-for-model-users)
- [Corporate Finance Institute / Macabacus — Financial Modeling Guidelines (PDF)](https://corporatefinanceinstitute.com/assets/Financial-Modeling-Guidelines.pdf)
- [Wall Street Prep — M&A / LBO modelling seminar materials (PDF)](https://s3.amazonaws.com/wsp_sample_file/ma_lbo_seminar.pdf)

These references inform general modelling conventions; the case-specific source registers and transaction documents remain the authority for each model's facts.
