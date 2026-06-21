# Fnzero Community

[中文](./README_CN.md) | [English](./README.md) | [Website](https://fnzero.dev/) | [Telegram](https://t.me/fnzero_group) | [Discord](https://discord.gg/vuazbGkqQE)

Open-source team focused on Solana trading infrastructure, DEX event parsing, Yellowstone gRPC / Jito ShredStream tooling, wallet security, and AI developer automation.

## Focus Areas

| Area | What we build |
| --- | --- |
| Solana trading SDKs | Rust, TypeScript, Go, and Python SDKs for Pump.fun, PumpSwap, Bonk, Raydium, Meteora, Jito, SWQoS, and bot execution flows. |
| Real-time data | Parsers and streaming tools for Yellowstone gRPC, Jito ShredStream, RPC transactions, account data, and DEX events. |
| Wallet security | Local-first Solana wallet tooling, encrypted keystores, WSOL operations, durable nonce flows, and desktop wallet UI. |
| Infrastructure | Solana RPC installers, ShredStream deployment scripts, benchmark tools, IDL catalogs, examples, and operational guides. |
| AI developer tooling | AI coding tutorials and agent skills for Codex, Claude Code, Cursor, and Solana bot development. |

## Contact

- Website: [fnzero.dev](https://fnzero.dev/)
- Telegram: [t.me/fnzero_group](https://t.me/fnzero_group)
- Discord: [discord.gg/vuazbGkqQE](https://discord.gg/vuazbGkqQE)
- Business: [t.me/xyz_0xfnzero](https://t.me/xyz_0xfnzero)

## Public Projects

Only current public, non-fork repositories are listed here. Private, archived, deleted, forked, and internal repositories are intentionally omitted.

### Solana Trading SDKs and Bots

| Project | Stack | Description |
| --- | --- | --- |
| [sol-trade-sdk](https://github.com/0xfnzero/sol-trade-sdk) | Rust | Low-latency Solana DEX trading SDK for Pump.fun, PumpSwap, Bonk, Raydium, Meteora, Jito, and SWQoS lanes. |
| [sol-trade-sdk-nodejs](https://github.com/0xfnzero/sol-trade-sdk-nodejs) | TypeScript | TypeScript SDK for Solana DEX trading bots with Rust SDK parity. |
| [sol-trade-sdk-golang](https://github.com/0xfnzero/sol-trade-sdk-golang) | Go | Go SDK for Solana DEX trading bots and multi-protocol execution. |
| [sol-trade-sdk-python](https://github.com/0xfnzero/sol-trade-sdk-python) | Python | Async Python SDK for Solana DEX trading bots and strategy development. |
| [pumpfun-sdk](https://github.com/0xfnzero/pumpfun-sdk) | Rust | Pump.fun SDK with token create, buy/sell, logs, Yellowstone gRPC subscriptions, and transaction submission lanes. |
| [sol-trade-router](https://github.com/0xfnzero/sol-trade-router) | Rust | On-chain AMM proxy and trade router for Raydium and Pump / PumpAMM buy-sell instruction routing. |
| [trading-bot-proxy](https://github.com/0xfnzero/trading-bot-proxy) | TypeScript | Trading bot proxy with Unix Socket + Protobuf event streams, HTTP trade commands, and a TypeScript reference bot. |
| [trading-bot-ts](https://github.com/0xfnzero/trading-bot-ts) | TypeScript | PumpSwap follow-trading bot with consecutive-buy detection, take-profit, stop-loss, and proxy integration. |
| [fnzero-examples](https://github.com/0xfnzero/fnzero-examples) | Rust | Runnable examples for Pump.fun, PumpSwap, Yellowstone gRPC, ShredStream, SWQoS, and SafeKey flows. |

### Solana Streaming, Parsing, and Data

| Project | Stack | Description |
| --- | --- | --- |
| [solana-streamer](https://github.com/0xfnzero/solana-streamer) | Rust | DEX event streaming SDK over parser, Yellowstone gRPC, Jito ShredStream, RPC parsing, and bot-friendly filters. |
| [sol-parser-sdk](https://github.com/0xfnzero/sol-parser-sdk) | Rust | Parser core for Solana DEX events from Yellowstone gRPC, Jito ShredStream, RPC transactions, and account data. |
| [sol-parser-sdk-nodejs](https://github.com/0xfnzero/sol-parser-sdk-nodejs) | TypeScript | TypeScript parser SDK for Solana DEX events and account data. |
| [sol-parser-sdk-golang](https://github.com/0xfnzero/sol-parser-sdk-golang) | Go | Go parser SDK for Solana DEX events. |
| [sol-parser-sdk-python](https://github.com/0xfnzero/sol-parser-sdk-python) | Python | Python parser SDK for Solana DEX events. |
| [parser-proxy-ws](https://github.com/0xfnzero/parser-proxy-ws) | Rust | WebSocket proxy for real-time Solana DEX events with HTML, TypeScript, and Python clients. |
| [sol-shred-sdk](https://github.com/0xfnzero/sol-shred-sdk) | Rust | ShredStream gRPC client for Solana transaction entries, Pump.fun callbacks, and low-latency pipelines. |
| [grpc-benchmark](https://github.com/0xfnzero/grpc-benchmark) | Rust | Benchmark tools for Solana Yellowstone gRPC endpoints, FzStream comparison, latency testing, and Jito performance. |
| [solana-program-idls](https://github.com/0xfnzero/solana-program-idls) | IDLs | Program IDL catalog for Pump.fun, PumpSwap, Raydium, Meteora, Orca, and SDK integrations. |

### Wallet, Infrastructure, and Operations

| Project | Stack | Description |
| --- | --- | --- |
| [sol-safekey](https://github.com/0xfnzero/sol-safekey) | Rust | CLI and library for Solana wallet key management, encrypted keystores, 2FA/3FA, transfers, and WSOL tools. |
| [sol-safekey-ui](https://github.com/0xfnzero/sol-safekey-ui) | TypeScript / Rust | Local-first Solana wallet, keystore manager, Squads v4 multisig workbench, SPL Token dashboard, and desktop app. |
| [solana-rpc-install](https://github.com/0xfnzero/solana-rpc-install) | Shell | Solana RPC node installer for Ubuntu with Jito Solana / Agave, Yellowstone gRPC, NVMe tuning, snapshots, and monitoring. |
| [jito-shredstream-install](https://github.com/0xfnzero/jito-shredstream-install) | Shell | Jito ShredStream proxy installation scripts for validators, RPC nodes, trading bots, and parser infrastructure. |
| [ServerReport](https://github.com/0xfnzero/ServerReport) | Docs | Bare metal server notes for low-cost Solana RPC node hardware, providers, regions, and stability tradeoffs. |
| [k8s-notes](https://github.com/0xfnzero/k8s-notes) | Shell | Kubernetes notes and scripts for kubeadm setup, Docker install, Flannel networking, and Nginx examples. |

### BSC and EVM Trading

| Project | Stack | Description |
| --- | --- | --- |
| [four-trading-sdk](https://github.com/0xfnzero/four-trading-sdk) | TypeScript | SDK for FOUR.meme token trading on BNB Smart Chain: create, buy/sell, price quotes, slippage checks, and event monitoring. |
| [pancakeswap-sdk](https://github.com/0xfnzero/pancakeswap-sdk) | TypeScript | PancakeSwap V2 SDK with swaps, liquidity management, price quotes, AMM utilities, and event monitoring. |

### AI and Developer Automation

| Project | Stack | Description |
| --- | --- | --- |
| [AI-Code-Tutorials](https://github.com/0xfnzero/AI-Code-Tutorials) | Docs | Bilingual AI coding tutorials for Claude Code and OpenAI Codex: setup, CLI workflows, MCP, agents, code review, and prompts. |
| [solana-bot-dev-skills](https://github.com/0xfnzero/solana-bot-dev-skills) | Shell | Agent skills for Codex, Claude Code, Cursor, and other AI coding agents building Solana trading bots. |
| [YiSphere](https://github.com/0xfnzero/YiSphere) | Python | AI I Ching, BaZi, Liu Yao, Huangli, naming, and date-selection application. |
