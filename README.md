# Hey, I'm Gus 👋

**Building the infrastructure for autonomous commerce.** I architect and ship agent-driven platforms that connect marketplaces, affiliates, and AI — from Cloudflare Workers to monolithic Go backends.

---

## Blytz Ventures

Founder/engineer building an **agentic commerce ecosystem** on Cloudflare Workers:

| Product | Stack | Description |
|---------|-------|-------------|
| **Blytz Marketplace** | Go + CF Workers | Real-time auctions & live streaming marketplace |
| **Blytz Affiliate** | TS + CF Workers | Affiliate CRM & settlement layer for offline services |
| **Blytz Work** | TS + Go | Platform connecting VAs with employers |
| **Blytz Flight** | TS + MCP | Flight search & booking via Model Context Protocol |
| **Blytz Skills** | TS + CF Workers | Edge-executable AI skills sandbox |
| **Blytz Booking** | Go | Booking engine with Gemini integration |

**28 Cloudflare Workers** running in production — API gateway, auth service, catalog MCP, orchestrator, marketplace auction rooms, site platform, affiliate pipeline, and external MCP servers for Shopee, TikTok, and flight search.

---

## Agent Infrastructure

I ported [Flue](https://github.com/withastro/flue) (the 7.2k-star agent harness framework) to Go:

**[GoFlue](https://github.com/gmsas95/goflue)** — single-binary agent harness. Provider-agnostic LLM backend (OpenAI, Gemini, Anthropic), sandboxed tool execution, Markdown skills, MCP integration, HTTP+WebSocket server. Ships as one binary.

Also built **[Shopee MCP Gateway](https://github.com/gmsas95/shopee-mcp-gateway)** and **TikTok Affiliate MCP** — Cloudflare Workers-based MCP servers for commerce integrations with tenant-isolated execution.

---

## Platform Engineering

| Project | Description |
|---------|-------------|
| **[uptender](https://github.com/gmsas95/uptender)** | Malaysian tender dashboard on CF Workers + D1 |
| **[opencode-config](https://github.com/gmsas95/opencode-config)** | OpenCode agent configuration — 12 subagents, 30+ skills, MCP servers |
| **[opcdept](https://github.com/gmsas95/opcdept)** | Custom deployment pipeline on CF Workers |

---

## Stack

`Go` `TypeScript` `Cloudflare Workers` `D1` `SQLite` `Docker` `WebSocket` `MCP` `OpenAI SDK` `Next.js` `tRPC` `Prisma`

---

*28 workers • 30+ repos • one binary at a time*
