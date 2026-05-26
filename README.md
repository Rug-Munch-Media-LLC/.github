# 🛡️ Rug Munch Media LLC

**Protecting retail crypto investors from scams. Building Rug Munch Intelligence.**

> Community-driven DAO LLC. 210 AI-powered crypto intelligence tools across 13 blockchains.

## 🔗 Links

- **Website**: [rugmunch.io](https://rugmunch.io)
- **API Docs**: [rugmunch.io/docs](https://rugmunch.io/docs)
- **x402 Discovery**: [rugmunch.io/.well-known/x402](https://rugmunch.io/.well-known/x402)
- **OpenAPI Spec**: [rugmunch.io/openapi.json](https://rugmunch.io/openapi.json)
- **Twitter**: [@cryptorugmunch](https://twitter.com/cryptorugmunch)

## 📦 Repositories

| Repo | Description |
|------|-------------|
| [rugmuncher-backend](https://github.com/Rug-Munch-Media-LLC/rugmuncher-backend) | FastAPI backend — 210 x402 tools, 13 chains, 8 payment facilitators |
| [rmi-frontend](https://github.com/Rug-Munch-Media-LLC/rmi-frontend) | React + Vite + Tailwind frontend |
| [x402-gateway-base](https://github.com/Rug-Munch-Media-LLC/x402-gateway-base) | Cloudflare Worker — x402 payment gateway for Base chain |
| [x402-gateway-solana](https://github.com/Rug-Munch-Media-LLC/x402-gateway-solana) | Cloudflare Worker — x402 payment gateway for Solana |
| [rug-munch-intelligence-mcp](https://github.com/Rug-Munch-Media-LLC/rug-munch-intelligence-mcp) | MCP server for Claude Desktop / Cursor |
| [awesome-x402](https://github.com/Rug-Munch-Media-LLC/awesome-x402) | Curated list of x402 protocol implementations |
| [rugmuncher-telegram](https://github.com/Rug-Munch-Media-LLC/rugmuncher-telegram) | Telegram bot for Rug Munch Intelligence |
| [rugmaps](https://github.com/Rug-Munch-Media-LLC/rugmaps) | Rugged project mapping |
| [rugcharts](https://github.com/Rug-Munch-Media-LLC/rugcharts) | Crypto chart and analytics dashboard |

## 🛠️ x402 Protocol Endpoints

All 210 tools exposed across multiple formats:

| Format | Endpoint |
|--------|----------|
| x402 v2 Discovery | `GET /.well-known/x402` |
| Tool Catalog | `GET /api/v1/x402/tools-catalog` |
| OpenAI Function Calling | `GET /api/v1/x402-tools/openai-tools` |
| Anthropic Claude API | `GET /api/v1/x402-tools/anthropic-tools` |
| Google Gemini | `GET /api/v1/x402-tools/gemini-tools` |
| LangChain | `GET /api/v1/x402-tools/langchain-tools` |
| REST API | `POST /api/v1/x402-tools/{tool_name}` |

All discovery endpoints are free to access. Payment only required for tool execution via x402 protocol.

## 🔒 Security

- DMARC p=reject on both rugmunch.io and cryptorugmunch.com
- Cloudflare Bot Fight Mode + AI Labyrinth
- RFC 9116 security.txt on both domains

## 📜 License

Proprietary — see [rugmunch.io/terms](https://rugmunch.io/terms)