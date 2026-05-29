# Hi, I'm Daniel 👋

🤖 Agent-native builder &nbsp;·&nbsp; ⚡ Ships in production &nbsp;·&nbsp; 🛠️ Builds solo

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

## Start Here

- 🏈 **[ProxyDFS](https://proxydfs.vercel.app)** — DraftKings lineup optimizer for humans and AI agents. Public REST API + Claude/GPT skill files. Stripe-billed tiers.
- 📰 **[Artificial Dispatch](https://artificialdispatch.vercel.app)** — AI-agent publishing pipeline. Telegram → research → draft → image gen → human review → publish.
- 🌅 **[Afterglow Infinite](https://afterglow-experience.vercel.app)** — Immersive web companion for an EDM album.

<br>

---

## Projects

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

Control plane for the agentic editorial team behind Artificial Dispatch. Manages agents in an org-chart hierarchy with departments, reporting lines, and an auto-discovery setup wizard. Primary runtime is OpenClaw — working on compatibility with Hermes Agent and other harnesses.

**Stack:** Next.js · TypeScript · Convex · Clerk · OpenClaw

---

## 🌅 Afterglow Infinite &nbsp;·&nbsp; [afterglow-experience.vercel.app](https://afterglow-experience.vercel.app)

Immersive web companion for an EDM album. A chapter-based journey — from neon ignition through the full album arc to the afterglow. Designed as a visual and interactive counterpart to the music, not a static promo page.

**Stack:** Next.js · TypeScript · Tailwind · Framer Motion · Vercel

---

## 🥁 PEDRUM

MIDI drum humanizer VST/AU plugin — built with zero prior C++ or audio DSP knowledge to test how far AI-assisted development could reach outside a familiar stack. Genre presets, per-voice TIME/VEL/SWING/FEEL controls, loads in Logic Pro, Ableton, any DAW.

**Stack:** C++ · JUCE · MIDI

---

## ⚡ Flux Generator

Local FLUX.1-schnell and FLUX.1-dev image generation pipeline on Apple Silicon. Runs entirely offline via MPS acceleration — no API keys needed. Powers the image pipeline in Artificial Dispatch.

**Stack:** Python · Hugging Face Diffusers · MPS (Apple Silicon) · Gradio

---

## 🔨 Client Work

- **Louis V Handyman** — business site for a local handyman service
- **Swim For It FTL** — site for a Fort Lauderdale swim school

**Stack:** Astro · Tailwind

---

> Source for the above is private. Happy to walk through architecture, tradeoffs, and code in conversation.

---

[LinkedIn](https://linkedin.com/in/dkingfx) &nbsp;·&nbsp; [X @proxydfs](https://twitter.com/proxydfs)

