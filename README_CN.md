# Fnzero Community

[中文](./README_CN.md) | [English](./README.md) | [Website](https://fnzero.dev/) | [Telegram](https://t.me/fnzero_group) | [Discord](https://discord.gg/vuazbGkqQE)

专注于 Solana 交易基础设施、DEX 事件解析、Yellowstone gRPC / Jito ShredStream 工具、钱包安全和 AI 开发者自动化的开源团队。

## 重点方向

| 方向 | 我们在做什么 |
| --- | --- |
| Solana 交易 SDK | Rust、TypeScript、Go、Python SDK，覆盖 Pump.fun、PumpSwap、Bonk、Raydium、Meteora、Jito、SWQoS 和 Bot 执行链路。 |
| 实时数据 | Yellowstone gRPC、Jito ShredStream、RPC 交易、账户数据和 DEX 事件的解析与流式工具。 |
| 钱包安全 | 本地优先的钱包工具、加密 keystore、WSOL 操作、durable nonce 流程和桌面钱包 UI。 |
| 基础设施 | Solana RPC 安装脚本、ShredStream 部署、性能压测、IDL 目录、示例和运维指南。 |
| AI 开发者工具 | Codex、Claude Code、Cursor 相关教程与 Agent 技能，服务 Solana Bot 开发。 |

## 联系方式

- Website: [fnzero.dev](https://fnzero.dev/)
- Telegram 社区: [t.me/fnzero_group](https://t.me/fnzero_group)
- Discord: [discord.gg/vuazbGkqQE](https://discord.gg/vuazbGkqQE)
- 商务合作: [t.me/xyz_0xfnzero](https://t.me/xyz_0xfnzero)

## 公开项目

这里只列当前公开、非 fork 的仓库。私有、归档、已删除、fork 和内部仓库会刻意省略。

### Solana 交易 SDK 与 Bot

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [sol-trade-sdk](https://github.com/0xfnzero/sol-trade-sdk) | Rust | 低延迟 Solana DEX 交易 SDK，支持 Pump.fun、PumpSwap、Bonk、Raydium、Meteora、Jito 和 SWQoS 通道。 |
| [sol-trade-sdk-nodejs](https://github.com/0xfnzero/sol-trade-sdk-nodejs) | TypeScript | Solana DEX 交易 Bot TypeScript SDK，与 Rust SDK 保持能力对齐。 |
| [sol-trade-sdk-golang](https://github.com/0xfnzero/sol-trade-sdk-golang) | Go | Solana DEX 交易 Bot Go SDK，支持多协议执行链路。 |
| [sol-trade-sdk-python](https://github.com/0xfnzero/sol-trade-sdk-python) | Python | Solana DEX 异步交易 Python SDK，适合策略和 Bot 快速开发。 |
| [pumpfun-sdk](https://github.com/0xfnzero/pumpfun-sdk) | Rust | Pump.fun SDK，支持创建代币、买卖、日志、Yellowstone gRPC 订阅和多通道交易提交。 |
| [sol-trade-router](https://github.com/0xfnzero/sol-trade-router) | Rust | Raydium 与 Pump / PumpAMM 买卖指令路由的链上 AMM proxy 和交易 router。 |
| [trading-bot-proxy](https://github.com/0xfnzero/trading-bot-proxy) | TypeScript | 交易 Bot proxy，提供 Unix Socket + Protobuf 事件流、HTTP 交易命令和 TypeScript 参考 Bot。 |
| [trading-bot-ts](https://github.com/0xfnzero/trading-bot-ts) | TypeScript | PumpSwap 跟单 Bot，包含连续买入检测、止盈、止损和 proxy 集成。 |
| [fnzero-examples](https://github.com/0xfnzero/fnzero-examples) | Rust | Pump.fun、PumpSwap、Yellowstone gRPC、ShredStream、SWQoS 和 SafeKey 流程的可运行示例。 |

### Solana 流式数据、解析与数据资产

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [solana-streamer](https://github.com/0xfnzero/solana-streamer) | Rust | 基于 parser、Yellowstone gRPC、Jito ShredStream 和 RPC 解析的 DEX 事件流 SDK。 |
| [sol-parser-sdk](https://github.com/0xfnzero/sol-parser-sdk) | Rust | Solana DEX 事件解析核心，覆盖 Yellowstone gRPC、Jito ShredStream、RPC 交易和账户数据。 |
| [sol-parser-sdk-nodejs](https://github.com/0xfnzero/sol-parser-sdk-nodejs) | TypeScript | Solana DEX 事件和账户数据 TypeScript parser SDK。 |
| [sol-parser-sdk-golang](https://github.com/0xfnzero/sol-parser-sdk-golang) | Go | Solana DEX 事件 Go parser SDK。 |
| [sol-parser-sdk-python](https://github.com/0xfnzero/sol-parser-sdk-python) | Python | Solana DEX 事件 Python parser SDK。 |
| [parser-proxy-ws](https://github.com/0xfnzero/parser-proxy-ws) | Rust | 实时 Solana DEX 事件 WebSocket proxy，提供 HTML、TypeScript 和 Python 客户端示例。 |
| [sol-shred-sdk](https://github.com/0xfnzero/sol-shred-sdk) | Rust | ShredStream gRPC 客户端，用于 Solana 交易 entries、Pump.fun 回调和低延迟管线。 |
| [grpc-benchmark](https://github.com/0xfnzero/grpc-benchmark) | Rust | 面向 Solana Yellowstone gRPC、FzStream 对比、延迟测试和 Jito 性能的压测工具。 |
| [solana-program-idls](https://github.com/0xfnzero/solana-program-idls) | IDLs | Pump.fun、PumpSwap、Raydium、Meteora、Orca 和 SDK 集成所需 Program IDL 目录。 |

### 钱包、基础设施与运维

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [sol-safekey](https://github.com/0xfnzero/sol-safekey) | Rust | Solana 钱包密钥管理 CLI 和库，支持加密 keystore、2FA/3FA、转账和 WSOL 工具。 |
| [sol-safekey-ui](https://github.com/0xfnzero/sol-safekey-ui) | TypeScript / Rust | 本地优先 Solana 钱包、keystore 管理器、Squads v4 多签工作台、SPL Token 看板和桌面应用。 |
| [solana-rpc-install](https://github.com/0xfnzero/solana-rpc-install) | Shell | Ubuntu Solana RPC 节点安装脚本，覆盖 Jito Solana / Agave、Yellowstone gRPC、NVMe 调优、快照和监控。 |
| [jito-shredstream-install](https://github.com/0xfnzero/jito-shredstream-install) | Shell | 面向验证节点、RPC 节点、交易 Bot 和 parser 基础设施的 Jito ShredStream proxy 安装脚本。 |
| [ServerReport](https://github.com/0xfnzero/ServerReport) | Docs | 低成本 Solana RPC 裸金属服务器硬件、服务商、地区和稳定性取舍记录。 |
| [k8s-notes](https://github.com/0xfnzero/k8s-notes) | Shell | kubeadm、Docker、Flannel 网络和 Nginx 示例相关 Kubernetes 笔记与脚本。 |

### BSC 与 EVM 交易

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [four-trading-sdk](https://github.com/0xfnzero/four-trading-sdk) | TypeScript | FOUR.meme BNB Smart Chain 代币交易 SDK，支持创建、买卖、报价、滑点检查和事件监听。 |
| [pancakeswap-sdk](https://github.com/0xfnzero/pancakeswap-sdk) | TypeScript | PancakeSwap V2 SDK，支持 swap、流动性管理、价格报价、AMM 工具和事件监听。 |

### AI 与开发者自动化

| 项目 | 技术栈 | 简介 |
| --- | --- | --- |
| [AI-Code-Tutorials](https://github.com/0xfnzero/AI-Code-Tutorials) | Docs | Claude Code 和 OpenAI Codex 双语教程，覆盖安装、CLI 工作流、MCP、Agent、代码审查和提示词。 |
| [solana-bot-dev-skills](https://github.com/0xfnzero/solana-bot-dev-skills) | Shell | 面向 Codex、Claude Code、Cursor 等 AI 编程 Agent 的 Solana 交易 Bot 开发技能。 |
| [YiSphere](https://github.com/0xfnzero/YiSphere) | Python | AI 易经、八字、六爻、黄历、取名和择日应用。 |
