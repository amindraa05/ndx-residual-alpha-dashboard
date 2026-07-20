# Strategy overview (public brief)

## VECTOR Unit (unlever)
- Universe: NASDAQ-100 point-in-time members
- Score: residual vs QQQ, lookback 84 / skip 5
- Portfolio: top 1, exit outside top 2
- Rebalance: month-end
- Costs (claim): 10 bps/side + IBKR-style commission

## VECTOR Gear (lever primary)
- Score: resid_mom lookback 126 / skip 21
- Portfolio: force top 1 weekly
- Overlay: vol-target with frozen scale (train-pinned once)
- Costs (mid-honest claim): 7 bps/side + IBKR-style commission + 5.5% APR on max(lev-1,0)

## VECTOR Overdrive
- Same signal tape as Gear; hotter vol scale (deeper DD, higher thrust)

Hypothetical. Not investment advice.