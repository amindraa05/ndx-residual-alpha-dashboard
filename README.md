# Alpha One vs L3 — NDX residual paper comparison

Public static brief comparing:

- **Alpha One** — monthly residual leadership (paper primary)
- **L3 Risk Sleeve** — weekly resid_mom + frozen vol-target (paper secondary, mid-honest fees)

**Live:** https://amindraa05.github.io/ndx-residual-alpha-dashboard/

Simulated start capital in this build: **$50,000**.

## Disclaimer

Hypothetical research simulation only. Not investment advice. Past simulated performance is not indicative of future results. Fees are modeled approximations (not a live IBKR invoice).

## Regenerate (private research repo)

```bash
python -m src.strategy.build_a1_l3_dashboard
```

Then copy `reports/dashboard/*` into this public site repo.
