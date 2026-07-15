# NDX Residual Alpha — Strategy Overview

Long-only NASDAQ-100 residual leadership versus QQQ.

## Process
1. Point-in-time NASDAQ-100 membership on each decision date
2. Residual return = security return − QQQ return
3. Rank by multi-month residual strength (with short skip window)
4. Hold top N equal-weight; exit beyond rank threshold
5. Month-end rebalance with 10 bps slippage and IB-style commissions

## Portfolio constructions
- **Alpha One:** 84-day lookback / 5-day skip / top 1 / exit outside top 2
- **Alpha Pair:** 126-day lookback / 10-day skip / top 2 / exit outside top 4

Simulated starting capital: **$10,000**

*Confidential research material. Hypothetical performance. Not an offer to sell securities.*
