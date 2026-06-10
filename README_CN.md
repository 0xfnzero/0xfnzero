# 0xfnzero Team

[中文](https://github.com/0xfnzero/0xfnzero/blob/main/README_CN.md) | [English](https://github.com/0xfnzero/0xfnzero/blob/main/README.md) | [Website](https://fnzero.dev/) | [Telegram](https://t.me/fnzero_group) | [Discord](https://discord.gg/vuazbGkqQE)

专注于 Solana 与 EVM 交易基础设施、SDK、实时流式数据工具和开发者自动化的开源团队。

## 联系方式

| 商务合作 | 开发者社区 |
| --- | --- |
| [t.me/xyz_0xfnzero](https://t.me/xyz_0xfnzero) | [t.me/fnzero_group](https://t.me/fnzero_group) |

## 开源项目

这里只列 0xfnzero 的 public 原创项目，不包含 fork 项目，也不包含 GitHub 主页仓库本身。

### Solana 交易 SDK 与 Bot

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [sol-trade-sdk](https://github.com/0xfnzero/sol-trade-sdk) | Rust | 高性能 Solana DEX 交易 SDK，支持 PumpFun、PumpSwap、Bonk、Meteora、Raydium 等协议，适合低延迟交易 Bot。 |
| [sol-trade-sdk-golang](https://github.com/0xfnzero/sol-trade-sdk-golang) | Go | Go 版本 Solana DEX 交易 SDK，支持多协议与 MEV 服务商。 |
| [sol-trade-sdk-nodejs](https://github.com/0xfnzero/sol-trade-sdk-nodejs) | TypeScript | Node.js / TypeScript 版本 Solana DEX 交易 SDK。 |
| [sol-trade-sdk-python](https://github.com/0xfnzero/sol-trade-sdk-python) | Python | Python 版本 Solana DEX 交易 SDK，适合快速开发交易策略与 Bot。 |
| [pumpfun-sdk](https://github.com/0xfnzero/pumpfun-sdk) | Rust | PumpFun Solana 程序交互 Rust SDK。 |
| [sol-trade-router](https://github.com/0xfnzero/sol-trade-router) | Rust | Solana 交易路由与执行工具。 |
| [trading-bot-proxy](https://github.com/0xfnzero/trading-bot-proxy) | TypeScript / Rust | 面向 Solana DEX 交易 Bot 的代理服务，封装复杂链上交互为简单 API。 |
| [trading-bot-ts](https://github.com/0xfnzero/trading-bot-ts) | TypeScript | PumpSwap 自动交易 Bot，包含跟单、止盈和止损逻辑。 |
| [trading-proxy-http](https://github.com/0xfnzero/trading-proxy-http) | TypeScript | 面向交易系统的 HTTP 代理工具。 |
| [fnzero-examples](https://github.com/0xfnzero/fnzero-examples) | Rust | Rust 示例集合，覆盖 SDK 用法、交易案例、解析工具、密钥管理和实时流式数据。 |

### Solana 流式数据、解析与数据资产

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [solana-streamer](https://github.com/0xfnzero/solana-streamer) | Rust | Solana DEX 实时事件流工具，支持 PumpFun、PumpSwap、Bonk、Raydium 等协议。 |
| [sol-parser-sdk](https://github.com/0xfnzero/sol-parser-sdk) | Rust | 轻量级 Rust SDK，用于解析和订阅 Solana DEX 事件。 |
| [sol-parser-sdk-golang](https://github.com/0xfnzero/sol-parser-sdk-golang) | Go | 通过 Yellowstone gRPC 实时解析 Solana DEX 事件的 Go SDK。 |
| [sol-parser-sdk-nodejs](https://github.com/0xfnzero/sol-parser-sdk-nodejs) | TypeScript | Node.js / TypeScript 版本 Solana DEX 实时事件解析 SDK。 |
| [sol-parser-sdk-python](https://github.com/0xfnzero/sol-parser-sdk-python) | Python | Python 版本 Solana DEX 实时事件解析 SDK。 |
| [parser-proxy-ws](https://github.com/0xfnzero/parser-proxy-ws) | Rust | 将已解析的 Solana DEX 事件通过 WebSocket 推送给客户端的代理服务。 |
| [parser-proxy-unixsocket](https://github.com/0xfnzero/parser-proxy-unixsocket) | Rust | 面向解析与流式数据管线的 Unix socket 代理。 |
| [sol-shred-sdk](https://github.com/0xfnzero/sol-shred-sdk) | Rust | Shredstream 客户端，用于订阅和处理 Solana 交易数据。 |
| [grpc-benchmark](https://github.com/0xfnzero/grpc-benchmark) | Rust | Rust 版 gRPC 压测工具，面向 Yellowstone 与实时流式基础设施。 |
| [solana-program-idls](https://github.com/0xfnzero/solana-program-idls) | IDL | PumpFun、Bonk、Raydium、Meteora、Orca 等 Solana 协议 Program IDL 集合。 |

### Solana 基础设施、安全与运维

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [solana-rpc-install](https://github.com/0xfnzero/solana-rpc-install) | Shell | Solana RPC 节点安装与 Ubuntu 系统参数优化指南。 |
| [jito-shredstream-install](https://github.com/0xfnzero/jito-shredstream-install) | Shell | Jito Shredstream 安装指南。 |
| [sol-safekey](https://github.com/0xfnzero/sol-safekey) | Rust | Solana 私钥安全生成、管理、分片和加密 CLI 工具。 |
| [sol-safekey-ui](https://github.com/0xfnzero/sol-safekey-ui) | TypeScript | Solana 钱包与 keystore 安全管理 Web UI。 |
| [solana-bot-dev-skills](https://github.com/0xfnzero/solana-bot-dev-skills) | Shell | 面向 Codex、Claude Code、Cursor 等 AI 编程 Agent 的 Solana Bot 开发技能。 |

### BSC 与 EVM 交易

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [four-trading-sdk](https://github.com/0xfnzero/four-trading-sdk) | TypeScript | Four.Meme BSC Launchpad 代币交易 SDK。 |
| [pancakeswap-sdk](https://github.com/0xfnzero/pancakeswap-sdk) | TypeScript | PancakeSwap V2 交易、流动性管理与链上事件监听 SDK。 |

### Fzstream

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [fzstream-client](https://github.com/0xfnzero/fzstream-client) | Rust | Fzstream 客户端。 |
| [fzstream-common](https://github.com/0xfnzero/fzstream-common) | Rust | Fzstream 公共库。 |
| [fzstream-demo](https://github.com/0xfnzero/fzstream-demo) | Rust | Fzstream 示例项目。 |

### AI 与开发者自动化

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [AI-Code-Tutorials](https://github.com/0xfnzero/AI-Code-Tutorials) | Docs | Claude Code、Codex、OpenAI 与 AI 辅助编程教程。 |
| [hermes-gui](https://github.com/0xfnzero/hermes-gui) | Python | Hermes AI Agent 的 PySide6 桌面端界面。 |
| [shop-ai](https://github.com/0xfnzero/shop-ai) | Python | AI 应用项目。 |

### 工具、文档与其它项目

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [fxpoi](https://github.com/0xfnzero/fxpoi) | Java | 用于读取和导出 Excel / CSV 的 Flutter 插件。 |
| [ServerReport](https://github.com/0xfnzero/ServerReport) | Docs | 裸金属服务器选择与避坑指南。 |
| [k8s-notes](https://github.com/0xfnzero/k8s-notes) | Shell | Kubernetes 笔记。 |
| [install-scripts](https://github.com/0xfnzero/install-scripts) | Shell | 安装脚本集合。 |
| [sdk-documents](https://github.com/0xfnzero/sdk-documents) | Docs | SDK 文档仓库。 |
| [YiSphere](https://github.com/0xfnzero/YiSphere) | Python | AI 辅助的易学与自然语言占卜应用。 |
