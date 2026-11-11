# Analyst Development Roadmap

## Purpose

This roadmap sets out five technical deliverables intended to strengthen the portfolio's evidence of investment-banking readiness. It is a build specification, not a claim that the models or presentation have been completed. Each item must be supported by source documentation, transparent assumptions, functioning model links and reviewable checks before it is described as complete.

## Priority summary

| Priority | Deliverable | Status | Primary capability |
|---:|---|---|---|
| 1 | Frasers–Accent integrated merger model | In progress | M&A and transaction modelling |
| 2 | Trading comparables and precedent transactions | Planned | Valuation judgement |
| 3 | Three-statement financial model | Planned | Financial modelling fundamentals |
| 4 | Leveraged buyout (LBO) model | Planned | Leveraged finance |
| 5 | Investment committee / transaction presentation | Planned | Commercial judgement and communication |

## 1. Frasers–Accent integrated merger model

**Objective:** build a transaction model that connects standalone company forecasts, deal terms, financing and purchase accounting to pro forma financial statements and EPS impact.

**Required workstreams**
- Transaction overview: strategic rationale, offer terms, undisturbed price, premium, fully diluted shares, consideration and enterprise-value bridge.
- Historical financials: sourced income statements, balance sheets and cash flow statements for bidder and target, with consistent accounting treatment.
- Standalone forecasts: revenue, margins, operating costs, working capital, capex, D&A, leases, tax and cash flow drivers.
- Sources & uses: cash consideration, scrip (if applicable), existing cash, new debt, refinancing, fees and other uses.
- Financing: debt tranches, interest rates, mandatory amortisation, maturity, cash sweep and financing fees.
- Purchase-price allocation: identifiable intangibles, deferred tax, goodwill and incremental D&A / amortisation.
- Synergies: cost and revenue categories, timing, probability, implementation costs, tax and dis-synergies.
- Pro forma outputs: combined income statement, opening balance sheet and cash / debt bridge.
- Accretion / dilution: EPS by year, share issuance, interest expense, synergies, purchase-accounting charges and sensitivity to funding mix and offer price.

**Minimum model controls**
- Sources equal uses.
- Pro forma balance sheet balances.
- Debt and cash schedules roll forward.
- Share count and consideration reconcile to transaction terms.
- Sensitivity table base case ties to the core model.
- No unexplained hardcodes or broken links.

**Publication evidence:** Excel model, source register, assumptions and open-items log, model review notes, and a concise transaction summary. Do not call the model complete until all material schedules are integrated and the checks pass.

## 2. Trading comparables and precedent transactions

**Objective:** demonstrate defensible relative valuation rather than a mechanically calculated peer average.

**Trading comparables**
- Define the valuation date and screening universe.
- Explain inclusion / exclusion criteria and business-model comparability.
- Source market capitalisation, enterprise value, financial metrics and share counts.
- Normalise fiscal periods, currency, leases, exceptional items and non-recurring costs.
- Calculate relevant multiples (for example EV / revenue, EV / EBITDA, EV / EBIT and P / E where appropriate).
- Present median, mean and selected range; explain outliers rather than silently removing them.
- Bridge selected multiples to an implied enterprise and equity value.

**Precedent transactions**
- Identify announced / completed transactions with credible strategic or financial comparability.
- Source announcement date, buyer, target, consideration, stake acquired, implied enterprise value and available financial metrics.
- Distinguish equity value from enterprise value and control premium from other valuation effects.
- Normalise financial periods and disclose incomplete or unavailable data.
- Explain why each transaction is included and why others are excluded.

**Publication evidence:** source-backed peer and deal tables, selection methodology, calculation workbook, valuation summary and limitations register. Avoid false precision where public disclosures do not support a reliable multiple.

## 3. Three-statement financial model

**Objective:** demonstrate that the income statement, balance sheet and cash flow statement are fully integrated through operating and financing schedules.

**Required build**
- Historical financial statements with source references and consistent classifications.
- Revenue build by segment, volume / price or another evidence-based operating driver.
- Cost and margin forecasts, operating expenses and tax.
- Working-capital schedules for receivables, inventory, payables and other material balances.
- PP&E, capex and D&A schedule.
- Debt, interest and cash schedule; equity and dividend assumptions where material.
- Integrated forecast income statement, balance sheet and cash flow statement.
- Scenario controls for key operating and financing assumptions.

**Minimum model controls**
- Balance sheet balances in every forecast period.
- Cash flow movement reconciles opening to closing cash.
- Debt balances reconcile to financing cash flows.
- Retained earnings reconcile to net income and distributions.
- Circularity is either avoided or clearly controlled and documented.

**Publication evidence:** historical source pack, forecast workbook, assumptions page, model checks and a short explanation of the key forecast drivers.

## 4. Leveraged buyout (LBO) model

**Objective:** assess the returns generated by an acquisition funded with a combination of sponsor equity and debt, and show how leverage, cash generation and exit valuation affect those returns.

**Required build**
- Entry valuation and transaction enterprise-value bridge.
- Sources & uses, sponsor equity contribution and debt tranches.
- Operating forecast and free cash flow available for debt repayment.
- Interest, amortisation, mandatory repayment and cash-sweep mechanics.
- Debt paydown and leverage progression.
- Exit valuation using a clearly justified exit multiple and holding period.
- Sponsor proceeds, MOIC and IRR.
- Sensitivities for entry multiple, exit multiple, leverage, operating performance and holding period.
- Downside case showing covenant / liquidity pressure where relevant.

**Minimum controls**
- Sources equal uses.
- Debt roll-forward reconciles.
- Sponsor equity proceeds reconcile to ownership and exit enterprise-to-equity bridge.
- IRR and MOIC reconcile to dated cash flows.
- Exit assumptions are clearly separated from operating performance.

**Publication evidence:** functioning LBO workbook, sources, assumptions, returns bridge, downside analysis and concise investment case. Do not present a single IRR without explaining the assumptions that produce it.

## 5. Investment committee / transaction presentation

**Objective:** convert the analysis into a concise, decision-oriented presentation that a senior reviewer can follow.

**Suggested structure**
1. Executive summary and decision requested.
2. Company, market and transaction overview.
3. Investment / strategic thesis.
4. Historical financial performance and forecast drivers.
5. Valuation methodology and triangulated valuation range.
6. Transaction structure, financing and pro forma impact.
7. Key sensitivities and downside case.
8. Principal risks, mitigants and diligence questions.
9. Recommendation, conditions and outstanding issues.
10. Appendix: assumptions, sources and model checks.

**Quality standard**
- Every headline number ties to the model.
- Facts, assumptions and judgement are visibly distinguished.
- Charts are labelled, dated and sourced.
- Risks are specific and linked to financial consequences.
- Recommendation is conditional on evidence; uncertainty is not hidden.
- Slides are concise and contain no unsupported claims.

**Publication evidence:** editable presentation, linked model outputs, source notes and a short review checklist.

## Execution discipline and release gates

A workstream should move from **Planned** to **In progress** only when active modelling begins. It should move to **Review** when the core workbook / analysis exists, and to **Complete** only after:
- independent formula and logic review;
- source and date validation;
- model checks and sensitivity reconciliation;
- consistency between workbook, README and presentation;
- clear disclosure of remaining limitations.

The Frasers–Accent merger model is the first build priority. The three-statement model is a foundational dependency and should be developed as part of the transaction model rather than as a disconnected exercise. The comps / precedents work should then provide an independent valuation cross-check. The LBO and committee presentation follow once the underlying operating and valuation work is defensible.

## Important distinction

This is an independent educational portfolio. It does not represent live transaction execution, client advisory work, or affiliation with Goldman Sachs or any other investment bank. The objective is to produce work that can be explained and defended in a technical interview—not to imply that a checklist alone establishes hiring readiness.
