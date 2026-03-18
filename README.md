# MemeOracle — Memecoin Intelligence MCP Server

> Early meme detection, rug-check risk scoring, momentum analysis, whale monitoring, viral potential. 9 tools, 80+ chains.

**Part of [ToolOracle](https://tooloracle.io) — Policy-enforced, tier-gated, usage-metered tool execution**

[![MemeOracle MCP server](https://glama.ai/mcp/servers/ToolOracle/memeoracle/badges/card.svg)](https://glama.ai/mcp/servers/ToolOracle/memeoracle)

## Connect

```bash
npx -y mcp-remote https://tooloracle.io/meme/mcp/
```

## x402 Pay-per-call (autonomous agents)

```
POST https://tooloracle.io/x402/meme/mcp/
→ 402 with structured pricing → Send USDC on Base → Retry with X-PAYMENT header
```

## 9 Tools · 1 unit = $0.01

| Tool | Units | Price | Tier |
|------|-------|-------|------|
| `rug_check` | 10 | $0.10 | Premium |
| `momentum_score` | 8 | $0.08 | Deep |
| `viral_score` | 8 | $0.08 | Deep |
| `whale_watch` | 5 | $0.05 | Deep |
| `trending_memes` | 3 | $0.03 | Standard |
| `chain_radar` | 3 | $0.03 | Standard |
| `new_launches` | 3 | $0.03 | Standard |
| `token_scan` | 2 | $0.02 | Standard |
| `health_check` | 0 | free | — |

## Risk scoring

`rug_check` returns a 0-100 risk score based on: liquidity depth, token age, volume patterns, buy/sell ratio, FDV/liquidity ratio. Rating: LOW / MEDIUM / HIGH / CRITICAL.

## Tier gating

| Tier | Max/call | Blocked |
|------|----------|---------|
| Free ($0) | 3 units | rug_check |
| Starter ($49/mo) | 8 units | — |
| Pro+ / x402 | 15 units | — |

## Data sources (all free, no API key)

DexScreener (300 req/min) · CoinGecko · SerpAPI Google Trends

## Links

- [ToolOracle](https://tooloracle.io) · [x402 Gateway](https://tooloracle.io/x402/)
- [RankOracle](https://github.com/ToolOracle/rankoracle) · [ShopOracle](https://github.com/ToolOracle/shoporacle) · [YieldOracle](https://github.com/ToolOracle/yieldoracle) · [SmartMoneyOracle](https://github.com/ToolOracle/smartmoneyoracle)