# Data & Methodology Card

Public diligence fields only (no absolute file paths).

```json
{
  "price_source": "Institutional-grade end-of-day vendor (EODHD)",
  "price_field": "Split/dividend-adjusted close",
  "securities_in_archive": 51607,
  "benchmark": "Invesco QQQ Trust (QQQ)",
  "benchmark_history": "2005-05-02 \u2192 2026-07-10",
  "study_panel_history": "2005-05-02 \u2192 2026-07-10",
  "study_panel_breadth": "199 listed names \u00d7 5331 sessions",
  "universe": "NASDAQ-100 constituents",
  "membership_method": "Point-in-time (PIT) interval membership (join / leave dates)",
  "membership_policy": "No look-ahead: only names that were index members on each decision date",
  "historical_member_universe": 274,
  "priced_coverage": "199 of 274 historical members with complete EOD history in panel",
  "rebalance_convention": "Month-end close",
  "cost_model": "10 bps slippage per side + Interactive Brokers\u2013style US equity commissions (see Fees)",
  "implementation_notes": [
    "Backtest assumes month-end close execution; live fills may differ by venue and timing.",
    "Commission schedule is a transparent fixed approximation, not a client-specific IBKR invoice.",
    "Index membership uses research-grade PIT intervals; commercial reconstitutions may differ slightly.",
    "Past simulated performance is not indicative of future results."
  ]
}
```
