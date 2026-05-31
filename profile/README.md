# Rug Munch Intelligence

> **The Bloomberg Terminal of Shitcoins.**  
> All-in-one crypto security & intelligence platform. Built to protect retail investors from scams and give everyone professional-grade tools — no signup, no API key, free to start.

---

## The Platform

We're building the command center for crypto security. Not just an MCP server — a full ecosystem of products that work for humans, traders, developers, and AI agents alike.

| Product | What It Does | Access |
|---------|-------------|--------|
| **Web Terminal** | Full dashboard: token scanner, wallet profiler, live markets, scam school, community trenches | [rugmunch.io](https://rugmunch.io) |
| **MCP Server** | 210+ AI-powered tools for AI agents (Claude, Cursor, ChatGPT) — scam detection, whale tracking, contract audit | `pip install rug-munch-intelligence-mcp` |
| **Telegram Bot** | Scan tokens, detect bundles, profile wallets — all from Telegram | [@rugmunchbot](https://t.me/rugmunchbot) |
| **RugCharts** | Real-time charting with AI technical analysis, live trade streaming, whale tagging across 7 chains | [rugmunch.io](https://rugmunch.io) |
| **RugMaps** | Interactive scam network visualization, wallet connection mapping, threat geography | [rugmunch.io](https://rugmunch.io) |
| **x402 Marketplace** | Pay-per-call crypto security tools — humans pay with crypto, AI agents pay via HTTP 402 protocol | [x402.rugmunch.io](https://x402.rugmunch.io) |

---

## For Humans → The Web Terminal

Visit [rugmunch.io](https://rugmunch.io) for the full dashboard experience:

- **Token Scanner** — Paste any contract address. 15 risk indicators across 7 chains. Honeypot detection, bundler analysis, contract audit, social verification.
- **Wallet Profiler** — Deep forensic analysis of any wallet. Holdings, P&L, risk exposure, connected wallets, whale classification.
- **Live Market Intelligence** — Real-time prices, volume, trends powered by Birdeye + Jupiter + DexScreener.
- **Scam School** — Free educational modules: LP drain mechanics, honeypot anatomy, MEV sandwich attacks, and more.
- **Rug Pull Rehab** — Community program helping victims turn into vigilantes. Earn badges, build reputation, track scammers.
- **The Trenches** — Community feed: scam alerts, new token discoveries, wallet of interest reports.

**Pricing:** Free tier (5 scans/day). Pro ($29.99/mo, 100 scans/day). Elite ($99.99/mo, unlimited). No signup required to start.

---

## For AI Agents → MCP Server

210+ tools across 13 blockchains. The most complete crypto intelligence MCP on the market.

```bash
pip install rug-munch-intelligence-mcp
```

```json
{
  "mcpServers": {
    "rug-munch-intelligence": {
      "command": "python3",
      "args": ["-m", "rug_munch_mcp"],
      "env": { "RUG_MUNCH_API_BASE": "https://rugmunch.io/api/v1" }
    }
  }
}
```

**210 tools · 13 chains · 8 payment facilitators**

| Category | Tools | What It Does |
|----------|-------|-------------|
| Security | 38 | Honeypot detection, rug pull prediction, contract audit, MEV protection, wash trading detection |
| Intelligence | 27 | Whale tracking, smart money flows, wallet clustering, insider detection, syndicate mapping |
| Market | 15 | Market pulse, chain health, arbitrage scanning, funding rates, liquidation heatmaps |
| Analysis | 14 | Wallet forensics, PnL tracking, portfolio aggregation, token deep dive, correlation matrix |
| Social | 11 | Sentiment analysis, Twitter/X signals, KOL tracking, Telegram pump detection |
| Launchpad | 7 | New token discovery, launch intelligence, sniper alerts, airdrop finder |
| Premium | 7 | OSINT identity hunt, forensic investigation, DCF valuation, deep forensics |
| DeFi | 4 | Yield scanning, impermanent loss, protocol risk scoring |
| NFT | 2 | Wash trading detection, floor price analytics |
| Data Providers | 150+ | DexScreener, Jupiter, Helius, Birdeye, CoinGecko, Nansen, Arkham, GMGN, Moralis, DeFiLlama, PumpFun |

**Payment:** Free trials on every tool. Pay-per-use via x402 (USDC across 13 chains). Wallet-connected users get bonus calls.

---

## For On-The-Go → Telegram Bot

[@rugmunchbot](https://t.me/rugmunchbot) brings the terminal to your pocket:

`/scan <address>` — Full token security scan  
`/bundle <address>` — Sniper/bundler detection  
`/wallet <address>` — Wallet analysis & risk scoring  
`/whales <address>` — Holder concentration analysis  
`/trending` — Hot tokens right now  
`/new` — Recent token launches  

---

## Payment Infrastructure (x402 Protocol)

We built the rails for AI-native micropayments. HTTP 402 Payment Required — agents pay for tools automatically, no API keys needed.

**13 chains · 10 facilitators. Auto-routed for best price & speed.**

| Chain | Facilitators | Currency |
|-------|-------------|----------|
| Solana | PayAI | USDC |
| Base | Coinbase CDP, PayAI, EIP-7702 | USDC |
| Ethereum | Primev (free), PayAI, EIP-7702 | USDC |
| BSC | Pieverse, EIP-7702 | USDC, USDT |
| Arbitrum, Optimism, Polygon, Avalanche, Fantom, Gnosis | EIP-7702 | USDC |
| TRON | MERX | USDT, USDC, USDD |
| Bitcoin | Satoshi | BTC |
| SEPA/EUR | AsterPay | EUR |

**Anti-abuse:** Browser fingerprinting, progressive wallet requirement, IP rate limiting, global daily caps, burst protection. Full refund if tool returns no data.

---

## All Repositories

| Repo | Description | Status |
|------|-------------|--------|
| [rug-munch-intelligence-mcp](https://github.com/Rug-Munch-Media-LLC/rug-munch-intelligence-mcp) | MCP server — 210+ AI-powered crypto tools | Public |
| [rugmuncher-backend](https://github.com/Rug-Munch-Media-LLC/rugmuncher-backend) | Backend API & services (FastAPI, Redis, FAISS) | Private |
| [rmi-frontend](https://github.com/Rug-Munch-Media-LLC/rmi-frontend) | Web terminal — React/Next.js dashboard | Private |
| [token-scanner](https://github.com/Rug-Munch-Media-LLC/token-scanner) | SENTINEL token security scanner | Public |
| [wallet-scanner](https://github.com/Rug-Munch-Media-LLC/wallet-scanner) | SENTINEL wallet forensics & behavioral analysis | Public |
| [rugcharts](https://github.com/Rug-Munch-Media-LLC/rugcharts) | Real-time charting, AI technical analysis, live trade streaming | Public |
| [rugmaps](https://github.com/Rug-Munch-Media-LLC/rugmaps) | Interactive scam network & wallet connection mapping | Private |
| [x402-gateway](https://github.com/Rug-Munch-Media-LLC/x402-gateway) | x402 MCP marketplace for crypto security tools | Public |
| [x402-gateway-base](https://github.com/Rug-Munch-Media-LLC/x402-gateway-base) | x402 gateway on Base + EVM chains (97 tools, USDC) | Public |
| [x402-gateway-solana](https://github.com/Rug-Munch-Media-LLC/x402-gateway-solana) | x402 gateway on Solana (97 tools, USDC via PayAI) | Public |
| [rmi-docs](https://github.com/Rug-Munch-Media-LLC/rmi-docs) | Platform documentation, API reference, integration guides | Public |
| [rugmuncher-telegram](https://github.com/Rug-Munch-Media-LLC/rugmuncher-telegram) | Telegram bot (@rugmunchbot) — token scanning, wallet analysis | Private |
| [awesome-x402](https://github.com/Rug-Munch-Media-LLC/awesome-x402) | Curated list of x402 HTTP 402 protocol resources | Public |

---

## Find Us

| Platform | Link |
|----------|------|
| Website | [rugmunch.io](https://rugmunch.io) |
| MCP Server | `https://rugmunch.io/mcp` |
| Twitter/X | [@CryptoRugMunch](https://x.com/CryptoRugMunch) |
| Telegram | [@CryptoRugMunch](https://t.me/CryptoRugMunch) |
| Telegram Bot | [@rugmunchbot](https://t.me/rugmunchbot) |
| Telegram Group | [@CryptoRugMuncher](https://t.me/CryptoRugMuncher) |
| Smithery | [@cryptorugmuncher/rug-munch-intelligence](https://smithery.ai/server/@cryptorugmuncher/rug-munch-intelligence) |
| Glama | [@cryptorugmuncher/rug-munch-intelligence](https://glama.ai/mcp/servers/@cryptorugmuncher/rug-munch-intelligence) |
| mcp.so | [rug-munch-intelligence](https://mcp.so/server/rug-munch-intelligence) |
| HuggingFace | [cryptorugmunch](https://huggingface.co/cryptorugmunch) |
| GitLab | [rug-munch-media-group](https://gitlab.com/rug-munch-media-group) |

---

## Our Philosophy

- **Instant access.** No signup, no API key, no wait. Start scanning in seconds.
- **Free first.** Every tool has a free trial. Pay only when you need more.
- **Pay-per-use.** No subscriptions required. Pay per scan via crypto.
- **Built for everyone.** Humans get a beautiful web terminal. AI agents get MCP + x402. Traders get Telegram. Developers get APIs.
- **Protect retail.** Every tool we build is designed to catch scams before they rug. We've been where you are.

---

**Rug Munch Intelligence** — Don't get rugged. Get intelligence.

© 2026 Rug Munch Media LLC. All Rights Reserved.
