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

## 🏈 ProxyDFS · [proxydfs.vercel.app](https://proxydfs.vercel.app)

DraftKings lineup optimizer — built so AI agents are first-class consumers alongside humans.

The optimizer runs Monte Carlo simulation + ILP (integer linear programming) under the hood to generate GPP and cash lineups against DraftKings salary constraints. The full loop — pull slate → optimize → export DraftKings CSV — is exposed as a REST API with Claude/GPT skill files, so an agent can run the entire workflow with no human in the loop.

**Stack**: Next.js 15 · TypeScript · Convex · Clerk · Stripe · Vercel  
**Tiers**: Free · Pro · Agent API (paid)

- [proxydfs-agent-examples](https://github.com/dkingfx/proxydfs-agent-examples) — skill files + curl examples for the Agent API

---

## 📰 Artificial Dispatch · [artificialdispatch.vercel.app](https://artificialdispatch.vercel.app)

AI-agent publishing pipeline for a Wired/Engadget-style tech site.

Inbound via Telegram Bot API. A multi-model agent stack handles research, drafting, and editing — different models tuned for different stages. Images generated locally with FLUX.1 on Apple Silicon (MPS), artifacts streamed to Cloudflare R2 for serving. Nothing auto-publishes — every article goes through a human review queue before going live.

**Stack**: Next.js · TypeScript · PostgreSQL · Cloudflare R2 · Telegram Bot API · FLUX.1 (MPS) · Vercel

- [artificialdispatch-overview](https://github.com/dkingfx/artificialdispatch-overview) — architecture diagram + stack notes

---

## 🏢 EntraHub

Enterprise Microsoft 365 lifecycle SaaS. Handles provisioning, deprovisioning, and license management across an org via Microsoft Graph.

Durable execution via Temporal.io — long-running workflows (onboarding, offboarding) survive restarts and failures without losing state. End-to-end type safety with tRPC. Stripe for billing.

**Stack**: Next.js 15 · TypeScript · Temporal.io · tRPC · Prisma · PostgreSQL · Microsoft Graph · Stripe · Clerk

---

## 🤖 Nimtara

AI agent control plane. Organizes agents into departments and reporting lines with a live org chart. Auto-discovery setup wizard walks through connecting and configuring new agents.

**Stack**: Next.js · TypeScript · Convex · Clerk

---

> All four are closed-source. Happy to walk through architecture, tradeoffs, and code in conversation.

---

## Stack

**Languages** · TypeScript · Go · Python · SQL · Bash · PowerShell · Swift  
**Frameworks** · Next.js 15 · React · tRPC · Temporal.io · Prisma · Drizzle · Convex · Clerk · Tailwind · Radix UI  
**Cloud / Edge** · AWS · Azure · Cloudflare · Vercel  
**Data** · PostgreSQL · Cloudflare R2 · Wasabi S3  
**Infra** · VMware · Proxmox · Docker · UniFi  
**AI** · Cursor · Claude · GPT · OpenRouter · OpenClaw · Hermes · Ollama · FLUX.1

---

[LinkedIn](https://linkedin.com/in/dkingfx) · [X @proxydfs](https://twitter.com/proxydfs)
