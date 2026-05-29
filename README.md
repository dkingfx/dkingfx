# Hi, I'm Daniel 👋

📍 Fort Lauderdale &nbsp;|&nbsp; 🤖 Agent-native builder &nbsp;|&nbsp; ☁️ Platform engineer

**Now:** NBA slate support + agent skill v2 for ProxyDFS &nbsp;·&nbsp; May 2026

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

---

## 🏈 ProxyDFS &nbsp;·&nbsp; [proxydfs.vercel.app](https://proxydfs.vercel.app)

DraftKings lineup optimizer built so AI agents are first-class consumers alongside humans.

Monte Carlo simulation + ILP (integer linear programming) against DraftKings salary constraints. The full loop — pull slate → optimize → export CSV — is exposed as a REST API with Claude/GPT skill files. An agent can run the entire workflow with no human in the loop.

**Stack:** Next.js 15 · TypeScript · Convex · Clerk · Stripe · Vercel &nbsp;·&nbsp; Free / Pro / Agent API tiers

→ [proxydfs-agent-examples](https://github.com/dkingfx/proxydfs-agent-examples) — skill files + curl examples

---

## 📰 Artificial Dispatch &nbsp;·&nbsp; [artificialdispatch.vercel.app](https://artificialdispatch.vercel.app)

AI-agent publishing pipeline for a Wired/Engadget-style tech site.

Inbound via Telegram Bot API. Multi-model agent stack — different models tuned for research, drafting, and editing. Images generated locally with FLUX.1 on Apple Silicon (MPS), streamed to Cloudflare R2. Nothing auto-publishes — every article goes through a human review queue.

**Stack:** Next.js · TypeScript · PostgreSQL · Cloudflare R2 · Telegram Bot API · FLUX.1 (MPS) · Vercel

→ [artificialdispatch-overview](https://github.com/dkingfx/artificialdispatch-overview) — architecture + Mermaid diagram

---

## 🏢 EntraHub

Enterprise Microsoft 365 lifecycle SaaS. Provisioning, deprovisioning, and license management via Microsoft Graph.

Durable execution via Temporal.io — onboarding/offboarding workflows survive restarts and failures without losing state. End-to-end type safety with tRPC.

**Stack:** Next.js 15 · TypeScript · Temporal.io · tRPC · Prisma · PostgreSQL · Microsoft Graph · Stripe · Clerk

---

## 🤖 Nimtara

AI agent control plane. Org-chart hierarchy, department structure, auto-discovery setup wizard.

**Stack:** Next.js · TypeScript · Convex · Clerk

---

> All four are closed-source. Happy to walk through architecture, tradeoffs, and code in conversation.

---

## Stack

**Languages** &nbsp;·&nbsp; TypeScript · Go · Python · SQL · Bash · PowerShell · Swift  
**Frameworks** &nbsp;·&nbsp; Next.js 15 · React · tRPC · Temporal.io · Prisma · Drizzle · Convex · Clerk · Tailwind · Radix UI  
**Cloud / Edge** &nbsp;·&nbsp; AWS · Azure · Cloudflare · Vercel  
**Data** &nbsp;·&nbsp; PostgreSQL · Cloudflare R2 · Wasabi S3  
**Infra** &nbsp;·&nbsp; VMware · Proxmox · Docker · UniFi  
**AI** &nbsp;·&nbsp; Cursor · Claude · GPT · OpenRouter · OpenClaw · Hermes · Ollama · FLUX.1

---

[LinkedIn](https://linkedin.com/in/dkingfx) &nbsp;·&nbsp; [X @proxydfs](https://twitter.com/proxydfs)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dkingfx/dkingfx/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dkingfx/dkingfx/output/snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/dkingfx/dkingfx/output/snake.svg" />
</picture>
