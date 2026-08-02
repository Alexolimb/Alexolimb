# Hi, I'm Oleksii 👋

**AI Automation Engineer** — I build systems that run by themselves, and I keep them running.

Based in Seville, Spain (CET) · Working language: English · Open to remote roles and contract work

---

## What I actually run in production

**A self-hosted n8n automation server** on my own Linux VPS — 80+ live workflows and 24 Telegram
bots, 24/7. I built all of it alone and I maintain it: deployment, retries, credential rotation,
and automatic failover between LLM providers when one goes down. Migrating those workloads from
paid APIs onto free tiers cut the running cost to near zero without losing function.

**LLM agents with tool calling and retrieval** over a private knowledge base, so answers cite real
internal documents instead of guessing. Local models served from my own GPU handle the bulk work;
paid models are used only where the quality difference is measurable.

---

## Projects

Some of these are private — client work, or products still in development. Descriptions are here
so you can see the range; happy to walk through any of them on a call.

| Project | What it is | Stack | Status |
|---|---|---|---|
| **[Polaris](https://github.com/Alexolimb/Polaris)** | Investment simulator and academy: virtual $10k portfolio, AI mentor, 30 lessons, 3 languages. Money handled as integer cents, trades atomic by design. **236 tests** | Flutter, Dart | 🟢 public |
| **[Polaris-server](https://github.com/Alexolimb/Polaris-server)** | Its backend — REST market data and an SSE-streaming LLM mentor with **zero external dependencies**. Runs anywhere without `npm install`. **22 tests** | Node.js | 🟢 public |
| **[englishviktoriia](https://github.com/Alexolimb/englishviktoriia)** | Live client site for an English tutor — design, copy, 3D scene, deploy, domain. Built end to end | Next.js, React | 🟢 public, live |
| **Content Factory** | Autonomous content pipeline: trend radar → ideas → script → images and voice-over → video assembly (ffmpeg) → human approval in Telegram → publishing → metrics → weekly self-adjustment. Produced 24 finished videos with no manual editing step | Python, systemd, Linux VPS | 🔒 private |
| **NEXUS** | Learning app that takes someone from zero to competent in code and AI — 100 lessons across 10 chapters, real code execution in a sandbox, spaced repetition, XP and streaks. Built for everyone from kids to pensioners | Electron, JS | 🔒 private |
| **Fluxo** | Personal finance app (Windows + Android): expenses, subscriptions, bills, goals, AI chat, currencies. In daily real use. **110 tests** | Flutter, n8n backend | 🔒 private |
| **Dayo** | Day planner — you speak your day out loud, AI structures it. 1-3-5 method, 60% rule. **51 tests** | Flutter | 🔒 private |
| **Zero** | Voice assistant with a **local** brain (Ollama on my own GPU) — wake word, streaming responses, timers, media, weather. No cloud, no login, 0.3–0.6s response | Python, Ollama | 🔒 private |
| **Evy Panel** | Automation panel inside Adobe Premiere Pro: live subtitle translation, moment finding, multi-camera cutting, audio and markers — 11 of 15 editing steps automated | UXP panel, JS | 🔒 private |
| **Ami Pult** | Desktop app that finds businesses without websites anywhere in the world (OpenStreetMap), scores them, and drafts a personal email to each in its own language using local models. **143 tests** | Electron, TS | 🔒 private |

---

## How I work

I work **agentically**, not by prompting and hoping. Written specs, persistent project context,
several agent tracks in parallel, and verification of output rather than trust in it. Every project
carries its own written handbook — not for the agents, but because it's the only way to pick a
project back up two weeks later.

I write tests because I'm the only person who gets woken up when something breaks.

---

## Stack

**Automation & AI** — n8n (self-hosted, production) · LLM APIs (Anthropic, Gemini, Groq, Cerebras) ·
agents & tool calling · RAG · Ollama · Telegram Bot API

**Web & apps** — TypeScript · JavaScript · Node.js · Next.js · React · Flutter / Dart · Python

**Infrastructure** — Linux VPS · Docker · REST APIs & webhooks · SSE · Git · Vercel · environment
and secret management

---

## Background

Business degree, then years of client-facing work in video production — including editing for a US
studio, remotely and in English. I came to engineering through building things I needed, and I
stayed because I turned out to be good at the part most people skip: keeping it alive after launch.

📫 **worknoworktowork@gmail.com**
