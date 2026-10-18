### Hi, I'm Oluwatobi Ajibola

**Full-stack engineer.** I build products end to end: the NestJS backend, the React Native app, the web dashboard, and the infrastructure in between. Most of my recent work sits in fintech and trading, where data has to be fast and correct.

- 🔭 Currently building trading infrastructure (MetaTrader 5 bridges, market-data pipelines) and mobile products at [@Bossbus-Tech](https://github.com/Bossbus-Tech)
- 🧰 Comfortable owning a product from database schema to App Store build
- 📫 Open to full-time roles and contract work

<br>

#### Stack

**Backend** &nbsp; TypeScript · Node.js · NestJS · Bun / Elysia · PostgreSQL · Prisma · MongoDB · Redis / BullMQ · WebSockets · REST · GraphQL
**Mobile & web** &nbsp; React Native · Expo · React · Next.js · TanStack Query · Tailwind CSS
**Also** &nbsp; MQL5 (MetaTrader 5) · Solidity · EVM / Sui / Starknet · MCP servers & LLM agents · Docker

<br>

#### Selected work

Most of my production code lives in private and client repositories. Here's what some of it does.

**Cue — multi-timeframe trading desk** · *iOS / Android app, backend, and MT5 feed*
Reads twelve markets across four timeframes and explains, in plain English, what the charts are doing. I built all three parts: an MQL5 expert advisor that pushes HMAC-signed market data out of MetaTrader 5, a NestJS + Postgres service that ingests it and computes multi-timeframe analysis, and an Expo app that receives live prices over WebSocket. Paid "Deep Analysis" calls run on credits.
`Expo` `React Native` `NestJS` `Prisma` `Postgres` `WebSocket` `MQL5`

**MarketBridge — trading data & execution platform**
A NestJS platform that replaced a legacy PHP data API. It bridges MetaTrader 5 terminals to HTTP: candles, indicators, analysis feeds, chart rendering, order management, the economic calendar, and an MCP server so AI agents can use it as a toolset. Every legacy endpoint kept its exact contract, so existing bots and integrations moved over without changes. It runs as separate API, EA-gateway, and worker processes.
`NestJS` `Redis` `BullMQ` `MCP` `Anthropic SDK` `OpenAPI`

**DEX — crypto trading app and backend**
A mobile exchange with spot and perpetual futures (TP/SL, up to 5× leverage), live charts and order books, and portfolio tracking, backed by a NestJS backend organised into clean-architecture modules: execution, market data, portfolio/PnL, social, and an outbox-based messaging layer.
`Expo` `NestJS` `Prisma` `PostgreSQL` `Smart wallets`

**Blu — mobility & delivery**
- *Bike-rental GPS gateway:* a NestJS service that terminates raw TCP from GT06 GPS trackers, decodes binary CRC-framed packets, and exposes live positions and remote commands over HTTP.
- *WhatsApp food delivery:* customers, vendors, and riders order and deliver entirely through WhatsApp. It also has Paystack payments and a Next.js admin for menus, payouts, and analytics.

`NestJS` `TCP / binary protocols` `MongoDB` `Twilio` `Paystack` `Next.js`

**TheThread — phone-video directing tool**
A desktop app for building realistic phone-interaction videos on a timeline. Every screen is a pure function of time, so the same React components render the live preview and the exported 9:16 MP4.
`React` `Vite` `Remotion`

<br>

#### Open source

| Project | What it is |
|---|---|
| [uniswap-mcp-trading-agent](https://github.com/Emmanuel0705/uniswap-mcp-trading-agent) | An MCP server exposing Uniswap V3 trading on Base, plus an AI agent that trades through it |
| [code-auditor](https://github.com/Emmanuel0705/code-auditor) | An ElizaOS agent that audits GitHub repos (Lighthouse, Filecoin storage, X integration) |
| [gitstark](https://github.com/Emmanuel0705/gitstark) | An ElizaOS agent connecting GitHub activity to Starknet |
| [nest-boilerplate](https://github.com/Emmanuel0705/nest-boilerplate) | My NestJS starter template |
| [staking_reward](https://github.com/Emmanuel0705/staking_reward) · [erc20_erc721_token](https://github.com/Emmanuel0705/erc20_erc721_token) | Solidity: staking rewards, ERC-20 / ERC-721 tokens |
