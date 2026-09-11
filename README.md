# Dare Timileyin

**Backend & Systems Engineer** · Go, Python, TypeScript

Five years building backend systems in production. Crypto payments, peer-to-peer trading, prediction markets, AI agents, real estate automation, and IoT device infrastructure.

The work is the same underneath: services that handle money, state, or hardware commands correctly when things go wrong. Duplicate requests, failed payouts, dropped connections, restarts mid-transaction.

Lead engineer at [Nexalware](https://www.nexalware.com/). Open to backend and platform roles internationally.

---

## Stack

**Languages** `Go` `Python` `TypeScript` `SQL` `Solidity` `C++`

**Backend** `gRPC` `FastAPI` `Django REST` `Gin` `Fiber` `Node.js` `WebSockets` `MQTT`

**Data** `PostgreSQL` `MongoDB` `Redis` `Prisma` `Beanie`

**Infra** `Linux` `Docker` `Nginx` `systemd` `GitHub Actions`

**AI** `LangChain` `LangGraph` `CrewAI` `MCP` `RAG`

---

## Work

### Crypto payments backend · DigitWallet
`Python` `PostgreSQL`

Transaction handling and balance integrity for a digital wallet product. Provider integrations, idempotent processing so retries cannot double-credit an account.

### P2P trading platform · DrorPay
`FastAPI` `MongoDB` `Beanie`

Backend for a peer-to-peer crypto exchange running as a Telegram mini app. The hard part was making payouts safe: atomic state transitions, single-fire payout flags so a trade cannot disburse twice, startup sweeps that reconcile in-flight trades after a restart, platform-wallet reversals for failed settlements. Plus fraud detection, moderation, and audit logging on every balance-affecting action.

### AI lead conversion · Wakeeli
`Python` `LLM pipelines`

Backend for a WhatsApp agent that qualifies real estate leads, matches them against live listings, and books viewings. Responses are grounded in actual brokerage inventory rather than generated freely.

### Prediction markets · [RODE](#)
`TypeScript` `Node.js` `Prisma` `PostgreSQL`

Market lifecycle from creation through position taking to resolution and settlement. Shared Prisma schema in a monorepo, migrations that evolve the data model without breaking services already running.

### Smart contracts · TrueSofts
`Solidity` `Ethereum` `BSC` `Base` `Arbitrum`

Backend and integration layer for decentralized applications. Delivered and audited contracts across four chains, reviewing gas efficiency and security before deployment.

---

## Open source

### [Distributed Device Control System](#)
`Go` `gRPC` `Protocol Buffers` `MQTT` `PostgreSQL`

Device registration, telemetry, command dispatch with acknowledgement, reconnection, state sync between edge gateways and backend services. Commands survive network failure and apply once.

### [Nexalware Smart Socket](#)
`ESP32` `C++` `MQTT` `Go`

ESP32 socket with per-device broker authentication and schedules stored in EEPROM, evaluated against an onboard RTC. Runs its schedule without waiting for Wi-Fi or MQTT.

### [Smart Water Pump Controller](#)
`Arduino` `C++` `GSM`

Tank controller with automatic pump switching and two-way SMS control. The README documents the GSM debugging: an SRAM overflow on a 2KB board, and a module difference in how received SMS is announced.

### [Remote MCP Server](#)
`Python` `MCP` `HTTP streaming`

Exposes live market data to AI clients as callable tools. Session lifecycle, tool discovery, streaming responses, multiple concurrent clients.

---

## Background

Top Rated on Upwork, 100% Job Success Score. Clients in the US, Europe and West Africa.

B.Eng. Electrical & Electronics Engineering (Telecommunications), Federal University of Technology Minna.

---

[Nexalware](https://www.nexalware.com/) · [LinkedIn](https://www.linkedin.com/in/dare-timileyin-b2099a241/) · [X](https://x.com/daretimileyin42) · daretimileyin1@gmail.com
