# Signet Jewelers — Analyst v3 DCF Model Review

## Review status

**Analyst-built DCF case study; mechanical core bridges pass, with forecast and diligence items open.**

The current canonical workbook is [Signet_DCF_Analyst_v3.xlsx](../valuation-case-studies/signet-jewelers/Signet_DCF_Analyst_v3.xlsx). This note reflects its current summary and model-check outputs. It is not an independent audit of every assumption or a claim of equivalence to an investment bank's internal model.

## Current valuation snapshot

| Metric | Gordon growth | Exit multiple |
|---|---:|---:|
| WACC | 9.782% | 9.782% |
| Terminal assumption | 2.0% perpetual growth | 6.0x EV/EBITDA |
| Enterprise value | US$4,988.0m | US$4,236.6m |
| Equity value | US$5,514.8m | US$4,763.4m |
| Implied value per share | US$140.33 | US$121.21 |
| Reference market price | US$118.58 | US$118.58 |
| Implied difference to reference | 18.3% | 2.2% |
| Terminal value / EV | 69.5% | — |

The reference share price is dated 9 November 2026. Financial inputs for cash, debt and shares are based on 1 August 2026, so the comparison is not fully synchronous. The exit multiple is an analyst assumption and has not been supported by a completed trading-comparables analysis.

## Model architecture and changes

The Analyst v3 workbook includes:
- Model guide and map of the workbook.
- FY27 H2 stub linked to company guidance less reported year-to-date actuals.
- Inputs and CAPM / WACC assumptions.
- DCF with separate Gordon-growth and exit-multiple terminal methods.
- One-page valuation output and sensitivities.
- Source register and guidance bridge.
- Model checks and audit log.

The H2 stub produces US$261.7m of unlevered free cash flow in the base case. H2 working capital is set to zero in the base case and sensitised at +/- US$100m. This is a material assumption requiring historical and seasonal calibration.

## Model checks

The following checks are displayed as PASS:
- Revenue forecast link.
- EBITDA arithmetic.
- DCF enterprise-value bridge.
- Equity-value bridge.
- H2 revenue bridge.
- H2 adjusted EBIT bridge.
- H2 capex bridge.
- Stub FCF tie.
- Cash bridge.

The guidance midpoint check is **REVIEW**. The adjusted EBIT midpoint plus annualised H1 D&A proxy is US$55.4m below company adjusted EBITDA guidance. This is a forecast diagnostic, not a formula error and should not be plugged without evidence.

## Outstanding diligence

### 1. Guidance and forecast calibration
- Reconcile FY27 adjusted EBITDA guidance to the adjusted EBIT plus D&A proxy; do not force an unsupported adjustment.
- Tie revenue, margins and SG&A to historical filings and company guidance.
- Separate recurring operating performance from restructuring, impairment, tariff refunds and other exceptional items.

### 2. Working capital and cash flow
- Replace the zero H2 working-capital base assumption with a historical, seasonally aware operating working-capital build.
- Distinguish inventory, trade payables, accrued liabilities and deferred revenue.
- Keep company-defined FCF separate from unlevered DCF FCF; avoid double counting.

### 3. Capital structure and share count
- Confirm cash, drawn debt, ABL utilisation, letters of credit and debt-like items at a common valuation date.
- Reconcile post-quarter repurchases and the announced ASR before using a post-quarter valuation date.
- Confirm diluted shares against the latest filing and subsequent buyback settlement.
- Keep lease treatment consistent: lease rent remains in operating expenses and lease liabilities are not separately deducted in the current bridge.

### 4. Terminal value and market cross-checks
- Gordon terminal value is 69.5% of enterprise value, so value is materially sensitive to WACC and terminal growth.
- Support terminal growth, terminal margins, reinvestment and terminal ROIC.
- Build trading comparables using consistent dates and accounting definitions before describing the exit multiple as market-supported.
- Add precedent transactions only where deal terms and target financials are reliably sourced.

## Conclusion

The Analyst v3 workbook is a more transparent, linked DCF case study with an explicit H2 bridge, sensitivities, source notes and visible checks. The model's arithmetic bridges pass, but the guidance diagnostic and material forecast / diligence items remain open. Do not describe it as a completed investment recommendation, fully validated target price, diligence-ready model or proprietary investment-bank template.

Independent educational portfolio work only. Not investment advice or a recommendation to transact in any security.
