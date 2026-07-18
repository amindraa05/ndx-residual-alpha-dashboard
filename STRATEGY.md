# Strategy overview (public brief)

## Alpha One (paper primary)
- Universe: NASDAQ-100 point-in-time members
- Score: residual vs QQQ, lookback 84 / skip 5
- Portfolio: top 1, exit outside top 2
- Rebalance: month-end
- Costs (claim): 10 bps/side + IBKR-style commission

## L3 Risk Sleeve (paper secondary)
- Score: resid_mom lookback 126 / skip 21
- Portfolio: force top 1 weekly
- Overlay: vol-target with frozen scale (train-pinned once)
- Costs (mid-honest claim): 7 bps/side + IBKR-style commission + 5.5% APR on max(lev-1,0)

Hypothetical. Not investment advice.
