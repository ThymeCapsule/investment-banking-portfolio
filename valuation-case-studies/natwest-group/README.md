# NatWest Group — Excess-Return / Residual-Income Valuation

## Case question

What equity value is implied by NatWest's tangible net asset value and the present value of expected returns on tangible equity above the cost of equity?

## Canonical deliverable

- [NatWest Excess Return — Analyst v3 workbook](NatWest_Excess_Return_Analyst_v3.xlsx)
- [Portfolio model review and open items](../../docs/MODEL_REVIEW.md)
- [Source register](../../docs/SOURCES.md)

The Analyst v3 workbook is the canonical file. Earlier workbook copies and the prior PDF summary have been removed from this case folder. No separate memo or PDF summary is published.

## Model snapshot

| Metric | Model output |
|---|---:|
| Excess-return value | **556.2p/share** |
| Reference market price (9 Nov 2026) | 597.6p |
| Implied difference to reference | (6.9%) |
| TNAV per share | 359.0p |
| Justified P/TNAV | 1.55x |
| Market P/TNAV | 1.66x |
| Cost of equity | 11.17% |
| Terminal RoTE / tangible-equity growth | 14.0% / 2.0% |
| Terminal value / equity value | 17.4% |

These are model outputs, not a recommendation or target price. The cost of equity and terminal assumptions are analyst judgements.

## Methodology and model architecture

The model uses a residual-income framework appropriate for a deposit-taking bank:

1. Establish opening tangible ordinary equity / tangible net asset value.
2. Forecast operating income, costs, impairments, earnings and return on tangible equity.
3. Link the operating forecast to a simplified CET1, risk-weighted assets and distributions schedule.
4. Calculate excess returns above the cost of equity.
5. Discount explicit and terminal excess returns.
6. Reconcile implied equity value to diluted shares and the reference market price.

The workbook includes operating forecast, excess-return valuation, bank forecast, peer P/TNAV cross-check, sensitivities, one-page output, notes, model checks, audit log and sources.

A conventional industrial-company EV/EBITDA DCF is not the primary valuation method for a bank.

## Model checks and limitations

The workbook's mechanical checks pass for CAPM cost of equity, CET1 capital bridge and floor in Year 1, excess-return PV bridge, equity-value scaling, TNAV per-share path, operating forecast PBT and net-income bridges, RoTE link and TNAV roll-forwards.

This remains a simplified bank valuation. It does not constitute a full regulatory-capital model or fully forecast risk-weighted assets, capital requirements, through-cycle impairments, minimum capital buffers and regulatory distribution constraints. The peer P/TNAV cross-check uses three external references; HSBC is a global bank rather than a pure UK domestic comparable.

Principal outstanding items:

1. Reconcile tangible equity to the latest reported balance sheet, including deductions and adjustments.
2. Expand and validate CET1 and RWA forecasts, capital requirements and management buffers.
3. Forecast credit impairments by portfolio and through the cycle.
4. Link earnings, retained profits, dividends and buybacks through a fully integrated capital roll-forward.
5. Test distributions against regulatory requirements and management buffers.
6. Calibrate RoTE, cost of equity, payout and terminal fade against history and a more defensible peer set.

## Interpretation

The 556.2p/share output is a simplified residual-income valuation using a linked operating and capital schedule. It is more developed than a standalone residual-income worksheet, but it is not a completed bank operating model or a full regulatory-capital forecast.

**Use:** independent educational modelling only. Not investment advice or a recommendation to transact in any security.
