# Rug Munch Media LLC

Crypto security tooling: token risk scoring, wallet forensics, the indexers underneath,
and machine-payable access to all of it. Wyoming LLC, self-funded, one maintainer.

The public repositories are parts of a running product rather than a portfolio. The
platform behind rugmunch.io is the backend below; the indexer and the MCP server are the
same code that serves it in production.

## What is here

**RMI** — token risk scoring and wallet forensics across 21 networks (20 EVM-family
chains including Tron, plus Solana). FastAPI, SQLAlchemy, Redis, Celery; premium calls
settle in USDC over x402.
[rmi-backend](https://github.com/Rug-Munch-Media-LLC/rmi-backend) — source-available

**RMI MCP** — the same intelligence exposed as typed tools for Claude, Cursor or any
other MCP client, priced and paid per call instead of by API key.
[rmi-mcp-x402](https://github.com/Rug-Munch-Media-LLC/rmi-mcp-x402) — MIT

**Lite Chain Indexer** — 21 networks indexed on free public RPCs only: 283M transfers and
628M internal transfers, held in 1–3 GB of RAM on a $5 VPS.
[lite-chain-indexer](https://github.com/Rug-Munch-Media-LLC/lite-chain-indexer) — MIT

**RugBrain** — retrieval over scam reports, token analyses and on-chain evidence, with
citations back to the record it answered from.
[rugbrain](https://github.com/Rug-Munch-Media-LLC/rugbrain) — MIT

Also public: [Pry](https://github.com/Rug-Munch-Media-LLC/pryscraper) turns a URL into
Markdown, JSON or a screenshot through 15 anti-bot tiers; [WalletPress](https://github.com/Rug-Munch-Media-LLC/walletpress)
derives and vaults wallets on 55 chains; [x402-coffer](https://github.com/Rug-Munch-Media-LLC/x402-coffer)
is the settlement facilitator; [rugmunchbot](https://github.com/Rug-Munch-Media-LLC/rugmunchbot)
is the platform in Telegram.

## Getting the code

HTTPS works anonymously on all three hosts. No account, no token.

```bash
git clone https://github.com/Rug-Munch-Media-LLC/rmi-backend      # GitHub
git clone https://git.rugmunch.io/RugMunchMedia/rmi-backend       # Forgejo, canonical
git clone https://gitlab.com/rug-munch-media-group/rmi-backend    # GitLab mirror
```

Forgejo is where the work and the CI happen; GitHub and GitLab are push mirrors that
catch up within minutes. SSH clones need a key registered on the host you clone from, so
the HTTPS URLs are the portable ones.

Every repository carries its own README with the install, run and test commands it
actually uses. Nothing in the public tier needs a private service to build.

## Docs

[docs.cryptorugmunch.com](https://docs.cryptorugmunch.com) — API reference, x402
discovery, deployment notes. `rmi-backend` also serves its own OpenAPI document at
`/openapi.json` and Swagger at `/docs`.

## Licence and contact

Licences are per repository: MIT on the MCP server, indexer, RugBrain, Pry, Coffer and
degenfeed; BSL 1.1 on WalletPress; source-available on rmi-backend and rugmunchbot. Read
the `LICENSE` file before you build on anything here.

Security reports go to biz@rugmunch.io privately, as described in
[SECURITY.md](https://github.com/Rug-Munch-Media-LLC/.github/blob/main/SECURITY.md).
Everything else: [cryptorugmunch.com](https://cryptorugmunch.com) ·
[Telegram](https://t.me/cryptorugmunch).

Status, plainly: beta, one maintainer, no SLA and no funding round. The MCP schemas and
the payment flow are stable; breadth of coverage is not, and reported gaps get fixed.
