<div align="center">

# Hi, I'm Adarsh Kumar

**AI Agents · Payments Infrastructure · Backend · iOS**

Final year CS student at SRM who builds AI agents and payment-grade backend systems, and ships iOS apps. B.Tech CSE (2027), India.

[![App Store](https://img.shields.io/badge/My_live_app-Orately-blue?logo=apple&logoColor=white)](https://apps.apple.com/in/app/articulation-coach-ai-orately/id6765478314)
[![LeetCode](https://img.shields.io/badge/LeetCode-CoderBuddie-orange?logo=leetcode&logoColor=white)](https://leetcode.com/u/CoderBuddie)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-adk28-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adk28)

</div>

---

## What I build

Most of my products are commercial, so their source is private. Each repository below is an **architecture showcase**: what the product does, how it is designed, and the engineering decisions behind it.

| Project | What it is |
|---|---|
| **[Recovery Agent](https://github.com/TechVoyagerr/recovery-agent)** | Autonomous AI agent that detects failed Razorpay payments, diagnoses the failure reason, chooses channel and timing, sends Payment Links, and learns from outcomes. Built for the Razorpay AI Builder Internship 2026: Next.js 15, Prisma, Razorpay SDK, deterministic rule engine with LLM copy polish, HMAC-verified webhooks, 56 tests |
| **[Orately](https://github.com/TechVoyagerr/orately)** | AI speech-coaching app: 40+ edge functions, 180+ DB migrations, fault-tolerant AI pipeline, Apple Watch and widgets. Live on the [App Store](https://apps.apple.com/in/app/articulation-coach-ai-orately/id6765478314) with paid subscriptions and server-verified webhooks |
| **[Lane Battler](https://github.com/TechVoyagerr/lane-battler)** | Real-time 1v1 lane battler for iOS and Android: deterministic pure C# battle simulation, Unity 6 URP client, Colyseus TypeScript authoritative match server |
| **[Fall Line](https://github.com/TechVoyagerr/fall-line)** | 3D downhill racing game in TypeScript and Three.js: deterministic simulation core, input-only bot opponents, procedural tracks, iOS via Capacitor |
| **[Surfaced](https://github.com/TechVoyagerr/surfaced-aso)** | App Store Optimization analytics platform: FastAPI data plane, TimescaleDB time series, ingestion workers, keyword scoring engine, Next.js dashboard |
| **[DSA in C++](https://github.com/TechVoyagerr/dsa-cpp)** | My data structures and algorithms practice, organized by pattern rather than by problem list |

Also public: **[ZenPlay](https://github.com/TechVoyagerr/zenplay-platform)**, a distraction-free learning platform (MERN and Next.js 15) with a streaming AI presentation generator, and **[Cadence](https://github.com/TechVoyagerr/cadence)**, an on-device AI meeting note-taker for iOS with 14-language local transcription and semantic search.

Plus 15+ additional apps and prototypes across iOS, macOS, web, and Unity.

## How I work

- **Webhooks and idempotency first**: HMAC-verified events, idempotent writes, atomic job claims, so a replayed or duplicated event never charges or messages twice
- **Retries with stopping rules**: explicit retry contracts, backoff, caps, and a clear condition for when the system stops trying
- **Consent and auditability**: opt-outs respected, quiet hours honored, and every decision and outcome written to an audit trail
- **Deterministic cores, graceful AI fallbacks**: rule engines decide, models polish, and the system still works correctly when the model is unavailable

## Stack

`C#` `TypeScript` `Python` `Swift` `C++` `SQL` · `Unity 6` `Three.js` `SwiftUI` `React` `Next.js` `Node.js` `FastAPI` `Prisma` · `PostgreSQL` `SQLite` `TimescaleDB` `MongoDB` `Redis` · `Razorpay` `Colyseus` `Supabase` `Docker` `CI/CD` `fastlane`

---

**adk08644@gmail.com**. Happy to walk through any of these systems in depth.
