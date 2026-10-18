<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Kalam&weight=700&size=52&duration=1&pause=100000&color=F0457A&center=true&vCenter=true&repeat=false&width=720&height=80&lines=Hello!+I'm+Oluwatobi" alt="Hello! I'm Oluwatobi" />
<br />
<img src="https://readme-typing-svg.demolab.com?font=Kalam&weight=700&size=24&duration=2800&pause=1200&color=8B5CF6&center=true&vCenter=true&width=720&height=40&lines=I+build+products+end+to+end+%3A);NestJS+%C2%B7+React+Native+%C2%B7+Postgres;Trading+systems+%C2%B7+Mobile+apps+%C2%B7+APIs" alt="I build products end to end" />


<a href="https://trade.dex.org/"><img src="https://img.shields.io/badge/Working_at-DEX-F0457A?style=for-the-badge" alt="DEX" /></a>&nbsp;
<img src="https://img.shields.io/badge/Open_to-Contract_work-8B5CF6?style=for-the-badge" alt="Open to contract work" />
<!-- LINK BADGES: add LinkedIn / X / Email here -->

</div>

<br />

I'm a full-stack engineer. I build products from the database schema to the App Store build: NestJS backends, React Native apps, web dashboards, and the infrastructure in between. Lately that's mostly fintech and trading, where data has to be fast and correct.

### About me

- 💼 Developer at [**DEX**](https://trade.dex.org/), building the trading app and backend
- 📈 I build trading infrastructure: MetaTrader 5 bridges, market-data pipelines, MCP servers for AI agents
- 📱 I've shipped mobile apps, APIs and admin dashboards for fintech, mobility, food delivery and Web3
- 🔥 **3,300+ contributions** since 2018, most of them in private production repos
- 💬 Open to full-time roles and contract work

<br />

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,bun,react,nextjs,tailwind,postgres,prisma,mongodb,redis,graphql,docker,solidity&perline=15" alt="TypeScript, JavaScript, Node.js, NestJS, Bun, React, Next.js, Tailwind, PostgreSQL, Prisma, MongoDB, Redis, GraphQL, Docker, Solidity" />

<br /><br />

<img src="https://streak-stats.demolab.com/?user=Emmanuel0705&hide_border=true&background=00000000&ring=F0457A&fire=F0457A&currStreakLabel=F0457A&sideLabels=8B5CF6&currStreakNum=8B949E&sideNums=8B949E&dates=8B949E" alt="GitHub streak" />

</div>

<br />

### 🛠 Selected work

<sub>Most of my production code lives in private and client repositories. Here's what some of it does.</sub>

**[DEX](https://trade.dex.org/): crypto trading app and backend**<br />
A mobile exchange with spot and perpetual futures (TP/SL, up to 5× leverage), live charts and order books, and portfolio tracking, backed by a NestJS backend organised into clean-architecture modules: execution, market data, portfolio/PnL, social, and an outbox-based messaging layer.
`Expo` `NestJS` `Prisma` `PostgreSQL` `Smart wallets`

**Cue: multi-timeframe trading desk** · *iOS / Android app, backend, and MT5 feed*<br />
Reads twelve markets across four timeframes and explains, in plain English, what the charts are doing. I built all three parts: an MQL5 expert advisor that pushes HMAC-signed market data out of MetaTrader 5, a NestJS + Postgres service that ingests it and computes multi-timeframe analysis, and an Expo app that receives live prices over WebSocket. Paid "Deep Analysis" calls run on credits.
`Expo` `React Native` `NestJS` `Prisma` `Postgres` `WebSocket` `MQL5`

**MarketBridge: trading data & execution platform**<br />
A NestJS platform that replaced a legacy PHP data API. It bridges MetaTrader 5 terminals to HTTP: candles, indicators, analysis feeds, chart rendering, order management, the economic calendar, and an MCP server so AI agents can use it as a toolset. Every legacy endpoint kept its exact contract, so existing bots and integrations moved over without changes.
`NestJS` `Redis` `BullMQ` `MCP` `Anthropic SDK` `OpenAPI`

**Blu: mobility & delivery**
- *Bike-rental GPS gateway:* a NestJS service that terminates raw TCP from GT06 GPS trackers, decodes binary CRC-framed packets, and exposes live positions and remote commands over HTTP.
- *WhatsApp food delivery:* customers, vendors, and riders order and deliver entirely through WhatsApp. It also has Paystack payments and a Next.js admin for menus, payouts, and analytics.

`NestJS` `TCP / binary protocols` `MongoDB` `Twilio` `Paystack` `Next.js`

**TheThread: phone-video directing tool**<br />
A desktop app for building realistic phone-interaction videos on a timeline. Every screen is a pure function of time, so the same React components render the live preview and the exported 9:16 MP4.
`React` `Vite` `Remotion`

<br />

### 🌱 Open source

| Project | What it is |
|---|---|
| [uniswap-mcp-trading-agent](https://github.com/Emmanuel0705/uniswap-mcp-trading-agent) | An MCP server exposing Uniswap V3 trading on Base, plus an AI agent that trades through it |
| [code-auditor](https://github.com/Emmanuel0705/code-auditor) | An ElizaOS agent that audits GitHub repos (Lighthouse, Filecoin storage, X integration) |
| [gitstark](https://github.com/Emmanuel0705/gitstark) | An ElizaOS agent connecting GitHub activity to Starknet |
| [nest-boilerplate](https://github.com/Emmanuel0705/nest-boilerplate) | My NestJS starter template |
| [staking_reward](https://github.com/Emmanuel0705/staking_reward) · [erc20_erc721_token](https://github.com/Emmanuel0705/erc20_erc721_token) | Solidity: staking rewards, ERC-20 / ERC-721 tokens |
