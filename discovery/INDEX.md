# 🔍 Wallet Discovery Pipeline

> Updated: 2026-03-20 22:40 UTC | **6 runs** | **47 wallets** added to shadow

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
| #6 | 2026-03-20 22:14 | 3 | 1 | **1** | [→ Run #6](runs/run_006.md) |
| #5 | 2026-03-20 18:46 | 72 | 9 | **9** | [→ Run #5](runs/run_005.md) |
| #4 | 2026-03-20 18:04 | 151 | 19 | **19** | [→ Run #4](runs/run_004.md) |
| #3 | 2026-03-20 13:11 | 48 | 7 | **7** | [→ Run #3](runs/run_003.md) |
| #2 | 2026-03-20 10:12 | 25 | 8 | **8** | [→ Run #2](runs/run_002.md) |
| #1 | 2026-03-20 01:56 | 13 | 3 | **3** | [→ Run #1](runs/run_001.md) |

## Stats

| Metric | Value |
|--------|-------|
| Total Runs | 6 |
| Total Wallets Added | 47 |
| Avg per Run | 7.8 |

---
*Auto-generated from wallet_discovery.db*
