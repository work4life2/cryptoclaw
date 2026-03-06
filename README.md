# CryptoClaw

> Private crypto AI assistant — wallet management, DeFi, NFTs, and multi-chain operations from your terminal.

[![npm version](https://img.shields.io/npm/v/@termix-it/cryptoclaw?style=for-the-badge)](https://www.npmjs.com/package/@termix-it/cryptoclaw)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

## Official Binance Skills Integration

CryptoClaw proudly integrates the official Binance Skills Hub — 7 native skills powered by Binance's Web3 and CEX infrastructure, giving your AI assistant direct access to Binance market data, trading, and on-chain intelligence.

Thanks to [@binance](https://github.com/binance) for building and open-sourcing the [Binance Skills Hub](https://github.com/binance/binance-skills-hub). 🙌

| Skill                    | Description                                                       |
| ------------------------ | ----------------------------------------------------------------- |
| `binance-spot`           | CEX spot trading — place orders, manage accounts, 60+ endpoints   |
| `binance-market-rank`    | Trending tokens, smart money inflow, social hype, PnL leaderboard |
| `binance-token-info`     | Token search, metadata, real-time market data, candlestick charts |
| `binance-token-audit`    | Security audit — detect honeypots, rug pulls, malicious contracts |
| `binance-trading-signal` | Smart Money on-chain buy/sell signals on BSC & Solana             |
| `binance-address-info`   | Query any wallet's token holdings and portfolio across chains     |
| `binance-meme-rush`      | Real-time meme token launchpad tracking and trending narratives   |

## What is CryptoClaw?

CryptoClaw is an AI-powered crypto assistant that runs locally in your terminal. It connects to the messaging channels you already use and helps you manage wallets, interact with DeFi protocols, track NFTs, and execute multi-chain operations — all through natural language.

## Features

- **Multi-chain support** — Ethereum, Solana, and more
- **Wallet management** — create, import, and monitor wallets
- **DeFi integration** — swap, stake, and track positions
- **NFT operations** — query, transfer, and monitor collections
- **Messaging channels** — WhatsApp, Telegram, Slack, Discord, and more
- **AI-native** — natural language interface powered by leading LLMs
- **Privacy-first** — runs on your own machine, your keys stay yours

## Install

```bash
npm install -g @termix-it/cryptoclaw
```

Or with pnpm / bun:

```bash
pnpm add -g @termix-it/cryptoclaw
bun add -g @termix-it/cryptoclaw
```

**Requirements:** Node.js 22+

## Quick Start

```bash
# Run the onboarding wizard
cryptoclaw onboard

# Start the gateway
cryptoclaw gateway run

# Check channel status
cryptoclaw channels status
```

## Supported Chains

| Chain    | Status    |
| -------- | --------- |
| Ethereum | Supported |
| Solana   | Supported |
| Base     | Supported |
| Arbitrum | Supported |
| Polygon  | Supported |

## Supported Channels

Connect CryptoClaw to your preferred messaging platform:

- Telegram
- WhatsApp
- Discord
- Slack
- Signal
- iMessage
- Microsoft Teams
- Matrix
- and more...

## Configuration

```bash
# Set your preferred AI model
cryptoclaw config set model openai/gpt-4o

# Add a wallet
cryptoclaw wallet add

# List connected channels
cryptoclaw channels list
```

## License

MIT — see [LICENSE](LICENSE) for details.
