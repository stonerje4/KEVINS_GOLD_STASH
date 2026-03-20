# 🔍 Wallet Discovery Pipeline

> Updated: 2026-03-20 17:36 UTC | **3 runs** | **18 wallets** added to shadow

## How It Works

1. **GMGN Trending** (5m, 1h, 6h) → fresh meme tokens
2. **GMGN Copytrade** → top-ranked trader wallets
3. **GeckoTerminal + DexScreener** → additional trending tokens
4. Per token → top 100 traders via GMGN API (FlareSolverr)
5. Filter by PnL, win rate, trade count, hold time
6. Winners → `shadow_wallets` → Shadow Tracker monitors them

*Runs every 2 hours. $0 cost (FlareSolverr + free APIs).*

## Run History

| Run | Time (UTC) | Evaluated | Passed | Added | Details |
|-----|------------|-----------|--------|-------|---------|
| #3 | 2026-03-20 13:11 | 48 | 7 | **7** | [→ Run #3](runs/run_003.md) |
| #2 | 2026-03-20 10:12 | 25 | 8 | **8** | [→ Run #2](runs/run_002.md) |
| #1 | 2026-03-20 01:56 | 13 | 3 | **3** | [→ Run #1](runs/run_001.md) |

## Stats

| Metric | Value |
|--------|-------|
| Total Runs | 3 |
| Total Wallets Added | 18 |
| Avg per Run | 6.0 |

---
*Auto-generated from wallet_discovery.db*
