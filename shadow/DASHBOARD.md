# 🧪 Wallet Backtest Dashboard

> Updated: 2026-03-21 14:35 UTC | **87** wallets backtested | Min 5 trades
> Strategy: Our TP ladder + trailing stops + SL simulated on 1m candles over 48h

## Overview

| Metric | Value |
|--------|-------|
| Wallets Scored | **87** |
| Profitable (>1.0x avg) | **38** 🟢 |
| Losing (≤1.0x avg) | **49** 🔴 |
| Avg Alpha Score | **46.7** |
| Best P&L/trade | **$+11.70** |

## Alpha Score Formula

```
Alpha Score (0-100) = EV (40) + WinRate (25) + Anti-SL (15) + Runner (10) + Confidence (10)
  EV:         Expected $ profit per $10 buy mapped to 0-40pts
  WinRate:    Win rate × 25pts
  Anti-SL:    Penalty for stop losses (0% SL = 15pts, 50% = 0)
  Runner:     Avg peak multiplier bonus (5x+ = 10pts)
  Confidence: More trades = more reliable (20+ = 10pts)
```

## Wallet Rankings

| Grade | Wallet | Alpha | P&L/$10 | AvgRet | WinR | SL% | Peak | Trades | GMGN |
|-------|--------|-------|---------|--------|------|-----|------|--------|------|
| 🟢 A | `HEnpWwkY2MG16FRp...` | **92** | $+11.70 | 2.17x | 82% | 6% | 3721307810.9x | 17 | [📊](https://gmgn.ai/sol/address/HEnpWwkY2MG16FRpmbSMrbBRMvMCA5vPJxtqfuvF1Pd7) |
| 🟢 A | `2CHrnc2LyagAbMaM...` | **81** | $+5.45 | 1.54x | 60% | 15% | 3.2x | 20 | [📊](https://gmgn.ai/sol/address/2CHrnc2LyagAbMaMFgthiDWh7ZZ9zT9TF8WEJf7MNE71) |
| 🟢 A | `AQUQHWfnEFoSpCva...` | **80** | $+5.13 | 1.51x | 56% | 6% | 2.9x | 16 | [📊](https://gmgn.ai/sol/address/AQUQHWfnEFoSpCvaBMbUVdkbSB3oqgrHXN8QZnj15Na8) |
| 🟢 B | `6TbDFs2dkHETrRWV...` | **80** | $+6.35 | 1.63x | 60% | 0% | 2.8x | 10 | [📊](https://gmgn.ai/sol/address/6TbDFs2dkHETrRWVbheiC11bwg7EWLDgszsCADF1ML1b) |
| 🟢 B | `5vweNikgScdnGkZC...` | **78** | $+5.24 | 1.52x | 56% | 22% | 3.6x | 18 | [📊](https://gmgn.ai/sol/address/5vweNikgScdnGkZCC3ya2FoJrezJBrSrhZgp8kK8bbtg) |
| 🟢 B | `EEdJsNJrxNjrnW3R...` | **78** | $+4.44 | 1.44x | 60% | 7% | 2.8x | 15 | [📊](https://gmgn.ai/sol/address/EEdJsNJrxNjrnW3RLGRn3hajoZEcjiuLLkeQbbma5DTK) |
| 🟢 B | `G1nVBXwCrXFNVifH...` | **76** | $+3.52 | 1.35x | 70% | 10% | 2.1x | 20 | [📊](https://gmgn.ai/sol/address/G1nVBXwCrXFNVifHx64m3jssXoyMSL8KNYc3X2fYL13Y) |
| 🟢 B | `J4n7sK27eoDCVwzG...` | **76** | $+5.70 | 1.57x | 65% | 35% | 3.1x | 20 | [📊](https://gmgn.ai/sol/address/J4n7sK27eoDCVwzGJdcrmQz4kEH6cvvL2strjkYu5imW) |
| 🟢 B | `2w85VLX4W4qm8SPS...` | **74** | $+2.86 | 1.29x | 75% | 0% | 2.0x | 12 | [📊](https://gmgn.ai/sol/address/2w85VLX4W4qm8SPS7UJ35XwKZuLiNEeJr9MGzArKXkBF) |
| 🟢 B | `AgecAR8Dmjgev5kj...` | **73** | $+9.00 | 1.90x | 57% | 29% | 4.4x | 7 | [📊](https://gmgn.ai/sol/address/AgecAR8Dmjgev5kjYGRqFqW7TzP4tPTkxtwJd7ecn2qh) |
| 🟢 B | `DBxYf63XXmxbrzyr...` | **72** | $+3.23 | 1.32x | 60% | 15% | 2.6x | 20 | [📊](https://gmgn.ai/sol/address/DBxYf63XXmxbrzyrgveTxF2mzE9y6C3qdYcGGWsusiZX) |
| 🟢 B | `7bStznDD61wKjvQk...` | **70** | $+2.33 | 1.23x | 71% | 0% | 1.5x | 14 | [📊](https://gmgn.ai/sol/address/7bStznDD61wKjvQkjQRcwe9T5zgVHTZ8Qq95MexoPKtX) |
| 🟢 B | `HCDsVE5Y22dzxFzi...` | **69** | $+2.17 | 1.22x | 55% | 0% | 1.8x | 20 | [📊](https://gmgn.ai/sol/address/HCDsVE5Y22dzxFzibEFSq4UD4RdHAvQKUHPuTcRJUGmQ) |
| 🟢 B | `Fi8idX7gVVYeJWbd...` | **69** | $+3.35 | 1.34x | 30% | 5% | 2.7x | 20 | [📊](https://gmgn.ai/sol/address/Fi8idX7gVVYeJWbdWjTZD1a4AAopXmixosrFGbSKXB8Z) |
| 🟡 C | `DHfshpzoC9Q7rz32...` | **64** | $+2.93 | 1.29x | 62% | 12% | 1.7x | 8 | [📊](https://gmgn.ai/sol/address/DHfshpzoC9Q7rz32j5juq2do3Bo8bA1KLmkNiRYaA8tf) |
| 🟡 C | `Gd78s23HFeN29Hhk...` | **64** | $+1.39 | 1.14x | 60% | 7% | 2.0x | 15 | [📊](https://gmgn.ai/sol/address/Gd78s23HFeN29Hhk4KAReoqysb2KdCZqJSodq5a9Es3E) |
| 🟡 C | `3q4cdqL7QLfmNHA4...` | **63** | $+1.10 | 1.11x | 50% | 5% | 2.0x | 20 | [📊](https://gmgn.ai/sol/address/3q4cdqL7QLfmNHA4mR186Jje7UnGSG5LUo5YcWdiCe5a) |
| 🟡 C | `r9pFHjFe2CiovRvr...` | **59** | $-0.04 | 1.00x | 55% | 0% | 1.3x | 20 | [📊](https://gmgn.ai/sol/address/r9pFHjFe2CiovRvrakTCGmW7THY7yzSX147vRnSK9De) |
| 🟡 C | `42HG8wPULnwoWPCc...` | **59** | $+0.75 | 1.08x | 40% | 0% | 1.3x | 20 | [📊](https://gmgn.ai/sol/address/42HG8wPULnwoWPCcixwBeYw9kb8Vdci7mQjs9iXV4nVv) |
| 🟡 C | `7aMgK5L4qEQ8Nyv6...` | **59** | $-0.04 | 1.00x | 50% | 0% | 1.5x | 20 | [📊](https://gmgn.ai/sol/address/7aMgK5L4qEQ8Nyv6ZzhZi2B82NSSRnwb2NGJnNagA46D) |
| 🟡 C | `Dw3npcfcks5hYoeV...` | **58** | $+1.02 | 1.10x | 50% | 12% | 1.8x | 16 | [📊](https://gmgn.ai/sol/address/Dw3npcfcks5hYoeViCKGFEctykaReBGKJnLrmoxtggRA) |
| 🟡 C | `Da6s2A815tKadQ7g...` | **58** | $+0.96 | 1.10x | 50% | 8% | 2.1x | 12 | [📊](https://gmgn.ai/sol/address/Da6s2A815tKadQ7gUSRPaUoyNP6qDjGJoEKD54fpx5Pc) |
| 🟡 C | `D3X29KMMpSKf862c...` | **57** | $+1.14 | 1.11x | 54% | 15% | 1.8x | 13 | [📊](https://gmgn.ai/sol/address/D3X29KMMpSKf862cHLffa48zQSyie6zxptBvwETB8HMq) |
| 🟡 C | `6S1op4eXQ4PVG6XS...` | **56** | $+2.21 | 1.22x | 33% | 11% | 2.1x | 9 | [📊](https://gmgn.ai/sol/address/6S1op4eXQ4PVG6XSa67VkZJR9FDMNV2GL87aLe1Hj6Zo) |
| 🟡 C | `7t9kYGrqtrSbGoQ6...` | **56** | $-0.07 | 0.99x | 45% | 0% | 1.0x | 20 | [📊](https://gmgn.ai/sol/address/7t9kYGrqtrSbGoQ6sfhfUS2UX4wYgekKek1AKPmEnS4p) |
| 🟡 C | `DDApL88zun3vGuhk...` | **55** | $-0.02 | 1.00x | 55% | 0% | 1.4x | 11 | [📊](https://gmgn.ai/sol/address/DDApL88zun3vGuhkxkUx6HmoXUyj37xs2NiwW5SMknHZ) |
| 🟡 C | `FkowYxE4xBAtGCpN...` | **55** | $-0.19 | 0.98x | 44% | 0% | 1.7x | 16 | [📊](https://gmgn.ai/sol/address/FkowYxE4xBAtGCpNr7hPLfg4L6XfTqvXN8RLg2ZK1fv3) |
| 🟡 C | `HEv3JdLTMm7pBDpS...` | **54** | $-0.34 | 0.97x | 45% | 5% | 1.4x | 20 | [📊](https://gmgn.ai/sol/address/HEv3JdLTMm7pBDpS9u2PXXhfMegvrN5gKpj6eQLYhXRW) |
| 🟡 C | `J5jm7BnBiGaB1x72...` | **54** | $-0.28 | 0.97x | 55% | 0% | 1.4x | 11 | [📊](https://gmgn.ai/sol/address/J5jm7BnBiGaB1x72FGNHPKuxcm8Rx51wdA24ewETF1yU) |
| 🟡 C | `HerkeyfRFFi7fWuy...` | **54** | $+0.63 | 1.06x | 42% | 8% | 1.9x | 12 | [📊](https://gmgn.ai/sol/address/HerkeyfRFFi7fWuykrBZpKc733NxHU7DhYrSBKebLX1D) |
| 🟡 C | `A3qbMytqdNRZ3sEc...` | **54** | $-0.42 | 0.96x | 45% | 5% | 1.2x | 20 | [📊](https://gmgn.ai/sol/address/A3qbMytqdNRZ3sEckrdyqnngXrVUoyHhKdLL7e4du3Ub) |
| 🟡 C | `J6bV2zN6u8BgCtxh...` | **53** | $+3.28 | 1.33x | 22% | 56% | 6.3x | 9 | [📊](https://gmgn.ai/sol/address/J6bV2zN6u8BgCtxhFz7GW4vpQiVZEDBfUnqyfzs98eMn) |
| 🟡 C | `EvZqb6PEm8sT5mK4...` | **53** | $+2.18 | 1.22x | 42% | 42% | 3.1x | 12 | [📊](https://gmgn.ai/sol/address/EvZqb6PEm8sT5mK4v2TTsRr9LpWrwAdkoSGC9UhmX29C) |
| 🟡 C | `W5D6nFHPARxc2wHj...` | **52** | $+0.99 | 1.10x | 58% | 33% | 1.9x | 12 | [📊](https://gmgn.ai/sol/address/W5D6nFHPARxc2wHjFgNXpudjnfFuXwWe3cWssyRjf1N) |
| 🟡 C | `2RxrBZPJePYpCffm...` | **52** | $+0.39 | 1.04x | 64% | 27% | 1.7x | 11 | [📊](https://gmgn.ai/sol/address/2RxrBZPJePYpCffmPF6gx3BodUUiZ4p6PM6XMiKrKTpw) |
| 🟡 C | `GLfMEoXygnBcriGe...` | **51** | $+0.64 | 1.06x | 30% | 0% | 1.5x | 10 | [📊](https://gmgn.ai/sol/address/GLfMEoXygnBcriGeQhRzUiVtwa5PeiZxsMUkhgLcqvgm) |
| 🟡 C | `3wjH8sQVn2M68TsW...` | **50** | $+2.18 | 1.22x | 29% | 43% | 3.0x | 14 | [📊](https://gmgn.ai/sol/address/3wjH8sQVn2M68TsW17Nh9fpddQU11Mf6kDrf7x9BG1KC) |
| 🟠 D | `6GGytYh7paCtSpHb...` | **50** | $+0.33 | 1.03x | 21% | 16% | 2.3x | 19 | [📊](https://gmgn.ai/sol/address/6GGytYh7paCtSpHbNQEhEsLxydpzam7SjPJHwxFvU332) |
| 🟠 D | `8e3rSXunFGgKc3NK...` | **49** | $+0.67 | 1.07x | 40% | 40% | 2.3x | 20 | [📊](https://gmgn.ai/sol/address/8e3rSXunFGgKc3NKQbKd4FCMCDDxEXsYDozuq27gKDt) |
| 🟠 D | `8hsSDYaV6V9JAqZX...` | **49** | $-0.14 | 0.99x | 50% | 12% | 1.6x | 8 | [📊](https://gmgn.ai/sol/address/8hsSDYaV6V9JAqZXbzPojZoebJBMt1bs3rss9mdakjV8) |
| 🟠 D | `A9S1bt9fVLMzmAtu...` | **49** | $-1.17 | 0.88x | 40% | 10% | 1.6x | 20 | [📊](https://gmgn.ai/sol/address/A9S1bt9fVLMzmAtuJPjLwYRJRKyWi9PfD1AAKF8dh4cN) |
| 🟠 D | `9MtWVfyxv6n3zcWr...` | **48** | $+0.33 | 1.03x | 30% | 10% | 1.9x | 10 | [📊](https://gmgn.ai/sol/address/9MtWVfyxv6n3zcWrVag4d3UwPKpWkz3g3AtGbGKsiNf) |
| 🟠 D | `8Q5SU1hd7VzieR1R...` | **48** | $+0.03 | 1.00x | 38% | 25% | 2.1x | 16 | [📊](https://gmgn.ai/sol/address/8Q5SU1hd7VzieR1RNWGQmp1aX2T1Gr4ED8R2iA46VdTx) |
| 🟠 D | `DsUVGPXJw9Mr9W2H...` | **47** | $+0.37 | 1.04x | 27% | 20% | 1.8x | 15 | [📊](https://gmgn.ai/sol/address/DsUVGPXJw9Mr9W2HZMG7TjXRVKJAUMnz59VXvUD1DRTy) |
| 🟠 D | `7oEGqcyjQxQmJwST...` | **47** | $+0.16 | 1.02x | 19% | 12% | 1.8x | 16 | [📊](https://gmgn.ai/sol/address/7oEGqcyjQxQmJwST191xvEqhmEt8nhMM8QvUmmciuokr) |
| 🟠 D | `FC4rpNEMY3EFpEm1...` | **46** | $+1.40 | 1.14x | 44% | 44% | 2.4x | 9 | [📊](https://gmgn.ai/sol/address/FC4rpNEMY3EFpEm1RtzZtUkyUFjDFBbunuDYcEgTeGoL) |
| 🟠 D | `5n593DWQkpfFgA69...` | **46** | $-0.40 | 0.96x | 30% | 25% | 1.9x | 20 | [📊](https://gmgn.ai/sol/address/5n593DWQkpfFgA69mS1MFWJDRZDCLcAuEsQYryqxi22Z) |
| 🟠 D | `7UAtsYVMnj4HCcG8...` | **45** | $-1.03 | 0.90x | 50% | 21% | 1.3x | 14 | [📊](https://gmgn.ai/sol/address/7UAtsYVMnj4HCcG8v5QzQ31kCnjXfhc17Sp6MbYyz5c4) |
| 🟠 D | `2SxPE8kdWRytZZnj...` | **43** | $+0.83 | 1.08x | 38% | 38% | 2.2x | 8 | [📊](https://gmgn.ai/sol/address/2SxPE8kdWRytZZnjVtxqkyAQVGGJSXs97y92RjXcrBGu) |
| 🟠 D | `GLjnQ8VT9yFHs78N...` | **43** | $-1.41 | 0.86x | 25% | 15% | 1.7x | 20 | [📊](https://gmgn.ai/sol/address/GLjnQ8VT9yFHs78N5CZWGGn22a3pm4XHih5WxUpozYnq) |
| 🟠 D | `EK1QXupxGp4CPRis...` | **43** | $-0.98 | 0.90x | 15% | 10% | 1.4x | 20 | [📊](https://gmgn.ai/sol/address/EK1QXupxGp4CPRisU5AsX1Zr5EqBMmqNUkn7DyRU4EEo) |
| 🟠 D | `12VFrc1dFynPzs4H...` | **43** | $-1.64 | 0.84x | 33% | 11% | 1.1x | 18 | [📊](https://gmgn.ai/sol/address/12VFrc1dFynPzs4HBRdRoMKNm1jca2S2uhaNKCkdffwy) |
| 🟠 D | `6c2UH8dKBvuAAUqD...` | **42** | $-1.05 | 0.90x | 19% | 6% | 1.3x | 16 | [📊](https://gmgn.ai/sol/address/6c2UH8dKBvuAAUqDqd62k4rgmde1xB5vGULNBQyGegcc) |
| 🟠 D | `6aDxNrF6CjkiFg8C...` | **42** | $-0.93 | 0.91x | 25% | 25% | 1.8x | 20 | [📊](https://gmgn.ai/sol/address/6aDxNrF6CjkiFg8C8Xdm4PWwsoEpkF5Z3hdopzuVrq5Y) |
| 🟠 D | `3DvvfDupSoTDJrPm...` | **41** | $-1.69 | 0.83x | 40% | 30% | 1.8x | 20 | [📊](https://gmgn.ai/sol/address/3DvvfDupSoTDJrPmcG7MW6CK3sm4j161WSsQYQEs4FLZ) |
| 🟠 D | `6HZxRR4QhYsh6Sus...` | **39** | $-1.56 | 0.84x | 5% | 5% | 1.3x | 20 | [📊](https://gmgn.ai/sol/address/6HZxRR4QhYsh6SussNfHSQThN4HwQFbja2eGrgZzFo47) |
| 🟠 D | `HhABnzict8byp1Xs...` | **37** | $-1.24 | 0.88x | 29% | 14% | 1.3x | 7 | [📊](https://gmgn.ai/sol/address/HhABnzict8byp1XsU4wVYCV6oYYvsydXjjEqifB48qpb) |
| 🟠 D | `DdJheoS6u66asrLr...` | **37** | $-0.60 | 0.94x | 33% | 47% | 1.9x | 15 | [📊](https://gmgn.ai/sol/address/DdJheoS6u66asrLrAYByjz9CwKhacTVDushMYLv7Av8V) |
| 🟠 D | `Hc7jNB8FeqV3RLyJ...` | **36** | $-0.94 | 0.91x | 35% | 47% | 1.8x | 17 | [📊](https://gmgn.ai/sol/address/Hc7jNB8FeqV3RLyJUqAVugEGwub7GS47Vc1kPp4wvqsH) |
| 🟠 D | `DFNX498a1T1UUPBT...` | **36** | $-0.48 | 0.95x | 19% | 69% | 3.2x | 16 | [📊](https://gmgn.ai/sol/address/DFNX498a1T1UUPBT4FwkWPNcz85qd9jzrbx9fzMWrC1e) |
| 🟠 D | `8f4JACu4cBSNseB1...` | **36** | $-0.06 | 0.99x | 27% | 45% | 1.9x | 11 | [📊](https://gmgn.ai/sol/address/8f4JACu4cBSNseB1jKG5WNfaD7kpBMq8D4oDLdoCh5YY) |
| 🟠 D | `EaUsbvhdRH4g7Se9...` | **35** | $-1.17 | 0.88x | 33% | 33% | 1.9x | 9 | [📊](https://gmgn.ai/sol/address/EaUsbvhdRH4g7Se9wvaisBBUDWbi31KJdbvuQZudbVzm) |
| 🟠 D | `ENnZhS5eer1WGMFh...` | **35** | $-0.74 | 0.93x | 31% | 50% | 1.8x | 16 | [📊](https://gmgn.ai/sol/address/ENnZhS5eer1WGMFhYXss45VpKTEJo9S1g1EoKHXc8Y3F) |
| 🔴 F | `Joo9mcSPcrzTcM1J...` | **34** | $-2.09 | 0.79x | 35% | 35% | 1.3x | 17 | [📊](https://gmgn.ai/sol/address/Joo9mcSPcrzTcM1JxSLvCefjzxHHZybtGPijruL7h2U) |
| 🔴 F | `CgkXJFh5Nme6Mrdv...` | **34** | $-1.12 | 0.89x | 36% | 50% | 1.9x | 14 | [📊](https://gmgn.ai/sol/address/CgkXJFh5Nme6MrdvpkT7Q81Myw24itbA6JnLxwFQArh) |
| 🔴 F | `8sf3LnCbPeYZ3QRL...` | **34** | $-1.86 | 0.81x | 25% | 25% | 1.6x | 12 | [📊](https://gmgn.ai/sol/address/8sf3LnCbPeYZ3QRLL3LszomLCr6cHE3g1U92XgLrLDH4) |
| 🔴 F | `DpbzC9NVymQZBJ4Y...` | **33** | $-0.21 | 0.98x | 18% | 45% | 2.2x | 11 | [📊](https://gmgn.ai/sol/address/DpbzC9NVymQZBJ4Y3pei5mBorh3kDeTWEEHjBqxHkAM8) |
| 🔴 F | `5w2o5TZtezrQqZGn...` | **33** | $-1.00 | 0.90x | 25% | 42% | 1.7x | 12 | [📊](https://gmgn.ai/sol/address/5w2o5TZtezrQqZGnH6jbKmKQaABVMSLUMHpSvwKpmG4m) |
| 🔴 F | `FFEzdAjs3DpM78V5...` | **32** | $+0.16 | 1.02x | 20% | 60% | 2.4x | 5 | [📊](https://gmgn.ai/sol/address/FFEzdAjs3DpM78V5McqZANTRmzuNDMhaQTqZyHnuYKKp) |
| 🔴 F | `HkCFF8sC1KHKKTuZ...` | **30** | $-2.13 | 0.79x | 33% | 33% | 1.4x | 9 | [📊](https://gmgn.ai/sol/address/HkCFF8sC1KHKKTuZJMk1m3FRhgVx9c7hEJces9Kpt5tN) |
| 🔴 F | `7Kwg1fLczGQummK7...` | **30** | $-2.06 | 0.79x | 20% | 45% | 1.6x | 20 | [📊](https://gmgn.ai/sol/address/7Kwg1fLczGQummK767feiZpaCboarmGLpKxFoeXMAwvz) |
| 🔴 F | `A8CEY24jporTAUgu...` | **30** | $-2.38 | 0.76x | 40% | 53% | 1.7x | 15 | [📊](https://gmgn.ai/sol/address/A8CEY24jporTAUguhQgaWgykAETM2K1UAxKHhbdceo1t) |
| 🔴 F | `GHrFb4ta1kUNKms5...` | **28** | $-0.99 | 0.90x | 22% | 56% | 1.7x | 9 | [📊](https://gmgn.ai/sol/address/GHrFb4ta1kUNKms5ZUFwBQpu4dSkpYJ7etgHoDV87vXn) |
| 🔴 F | `2Lmwct2Tz85RDNKn...` | **27** | $-1.91 | 0.81x | 38% | 62% | 1.7x | 8 | [📊](https://gmgn.ai/sol/address/2Lmwct2Tz85RDNKnbQnTZeupP1DPjJ1E4GF9E2dpGtaT) |
| 🔴 F | `6qTPHgnSZZUy5Aeo...` | **27** | $-2.42 | 0.76x | 19% | 44% | 1.8x | 16 | [📊](https://gmgn.ai/sol/address/6qTPHgnSZZUy5AeoqDBtFXvuPRSMT7i6kjx6JM3Q8nKy) |
| 🔴 F | `5hiiMugYNkYGmx8j...` | **25** | $-2.53 | 0.75x | 18% | 36% | 1.4x | 11 | [📊](https://gmgn.ai/sol/address/5hiiMugYNkYGmx8jR7RGLGJtgvTVxLteJtYbg6UbyJ2p) |
| 🔴 F | `2KSosr3PnCAsfWyH...` | **25** | $-2.78 | 0.72x | 15% | 60% | 1.8x | 20 | [📊](https://gmgn.ai/sol/address/2KSosr3PnCAsfWyHyj6EzxvfbFNiUPKPryqEjR3HjLaA) |
| 🔴 F | `AccVJGCog5YCJ6J6...` | **24** | $-2.88 | 0.71x | 43% | 57% | 1.6x | 7 | [📊](https://gmgn.ai/sol/address/AccVJGCog5YCJ6J64CvxkQNGADLHUvc4ZjqBU1z56coq) |
| 🔴 F | `HFgvdSkEGDArpwpp...` | **24** | $-2.83 | 0.72x | 15% | 55% | 1.6x | 20 | [📊](https://gmgn.ai/sol/address/HFgvdSkEGDArpwppJtx2mpeDvr1mUmVY8zmrXzDnG4Bt) |
| 🔴 F | `4jWWqx2vaExs9jFh...` | **23** | $-2.91 | 0.71x | 38% | 50% | 1.4x | 8 | [📊](https://gmgn.ai/sol/address/4jWWqx2vaExs9jFhoq9B8yptKfcaHJfDZsj9GdzetPAT) |
| 🔴 F | `FMuYYJvyxTmAgcPR...` | **22** | $-3.15 | 0.69x | 15% | 50% | 1.5x | 20 | [📊](https://gmgn.ai/sol/address/FMuYYJvyxTmAgcPRXhjwUjaHxXJAtqzkoLuGLMgC7EdJ) |
| 🔴 F | `8KBPi8gmgcw57fPK...` | **17** | $-3.29 | 0.67x | 14% | 43% | 1.3x | 7 | [📊](https://gmgn.ai/sol/address/8KBPi8gmgcw57fPKErRudUgA9YgW1pdgV5wTAzbYFTCZ) |
| 🔴 F | `DTXQKEbt4nS4c8kU...` | **17** | $-3.89 | 0.61x | 29% | 71% | 1.6x | 7 | [📊](https://gmgn.ai/sol/address/DTXQKEbt4nS4c8kUreV1mVrJzKscEhRNvhLEjB1SQq1t) |
| 🔴 F | `5FPytvPnCfQNN454...` | **14** | $-4.17 | 0.58x | 20% | 50% | 1.4x | 10 | [📊](https://gmgn.ai/sol/address/5FPytvPnCfQNN454uT342ChLoyb72dpkvZpdGwR2cnii) |
| 🔴 F | `F15vgDs9vrutUkne...` | **14** | $-3.68 | 0.63x | 10% | 50% | 1.4x | 10 | [📊](https://gmgn.ai/sol/address/F15vgDs9vrutUknejy8yeaPyqhb51F6Pu1WG2Ky326RU) |
| 🔴 F | `8DRc7a6w3r87bMCt...` | **12** | $-3.88 | 0.61x | 12% | 62% | 1.3x | 8 | [📊](https://gmgn.ai/sol/address/8DRc7a6w3r87bMCt7DFd2rhTAXmrLYDSTgdDccgMAMms) |
| 🔴 F | `DrWXfkgnmBxBXujD...` | **10** | $-4.92 | 0.51x | 7% | 87% | 1.4x | 15 | [📊](https://gmgn.ai/sol/address/DrWXfkgnmBxBXujD1fx4AxALNCowDgB8hkRq3jGCqWc4) |

## 🎯 PRD Recommendations

**14 wallets ready for PRD** (Alpha ≥ 65, profitable):

- `HEnpWwkY2MG16FRpmbSMrbBRMvMCA5vPJxtqfuvF1Pd7` — Alpha 92, +11.70/trade, 82% WR
- `2CHrnc2LyagAbMaMFgthiDWh7ZZ9zT9TF8WEJf7MNE71` — Alpha 81, +5.45/trade, 60% WR
- `AQUQHWfnEFoSpCvaBMbUVdkbSB3oqgrHXN8QZnj15Na8` — Alpha 80, +5.13/trade, 56% WR
- `6TbDFs2dkHETrRWVbheiC11bwg7EWLDgszsCADF1ML1b` — Alpha 80, +6.35/trade, 60% WR
- `5vweNikgScdnGkZCC3ya2FoJrezJBrSrhZgp8kK8bbtg` — Alpha 78, +5.24/trade, 56% WR
- `EEdJsNJrxNjrnW3RLGRn3hajoZEcjiuLLkeQbbma5DTK` — Alpha 78, +4.44/trade, 60% WR
- `G1nVBXwCrXFNVifHx64m3jssXoyMSL8KNYc3X2fYL13Y` — Alpha 76, +3.52/trade, 70% WR
- `J4n7sK27eoDCVwzGJdcrmQz4kEH6cvvL2strjkYu5imW` — Alpha 76, +5.70/trade, 65% WR
- `2w85VLX4W4qm8SPS7UJ35XwKZuLiNEeJr9MGzArKXkBF` — Alpha 74, +2.86/trade, 75% WR
- `AgecAR8Dmjgev5kjYGRqFqW7TzP4tPTkxtwJd7ecn2qh` — Alpha 73, +9.00/trade, 57% WR
- `DBxYf63XXmxbrzyrgveTxF2mzE9y6C3qdYcGGWsusiZX` — Alpha 72, +3.23/trade, 60% WR
- `7bStznDD61wKjvQkjQRcwe9T5zgVHTZ8Qq95MexoPKtX` — Alpha 70, +2.33/trade, 71% WR
- `HCDsVE5Y22dzxFzibEFSq4UD4RdHAvQKUHPuTcRJUGmQ` — Alpha 69, +2.17/trade, 55% WR
- `Fi8idX7gVVYeJWbdWjTZD1a4AAopXmixosrFGbSKXB8Z` — Alpha 69, +3.35/trade, 30% WR

---
*Generated by backtest engine | 1m candles | 48h per trade | 2026-03-21 14:35 UTC*