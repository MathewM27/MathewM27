# Hey, I'm Mathews 👋

I'm a full-stack engineer who thinks in systems. Give me a real problem and I'll take it from first principles to a shipped product — architecture, backend, front end, infrastructure, and the AI tooling that gets me there faster. I don't specialize in one layer of the stack; I specialize in owning the whole thing.

That's shown up as a real-time transport platform built solo end-to-end ([Alebus](https://github.com/MathewM27/alebus-api)), a two-sided rental marketplace ([Lakazhub](https://github.com/MathewM27/lakazhub.v1)), and an ongoing freelance practice building production systems for clients across aviation, automotive, and other industries. Different problems, same approach: understand the system, design it properly, build it, and own the outcome.

I use AI deliberately as part of how I build — from architecture exploration to implementation — because it lets me move faster without lowering the bar on what I ship.

**Full-Stack Engineer · Systems Thinking · Go / React / Next.js · AI-Augmented Delivery**

BSc Computer Systems Engineering (First Class Honours), Middlesex University Mauritius (2026) · Open to remote or relocation

[![Portfolio](https://img.shields.io/badge/Portfolio-mathews--mwangi.com-000000?style=flat&logo=safari&logoColor=white)](https://mathews-mwangi.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathews-mwangi-972839219)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mathewsmwangi6927@gmail.com)

---

## How I work

- **System design** — turning an ambiguous problem into an architecture, then building it: data model, service boundaries, the trade-offs in between
- **Full-stack execution** — Go on the backend, React/Next.js/React Native on the front end, comfortable owning either side or both
- **AI-augmented delivery** — using AI tooling deliberately across architecture exploration, implementation, and iteration to move faster on real client timelines
- **Infrastructure** — Docker, GitHub Actions, observability with Prometheus & Grafana

---

## Projects & client work

Each of these started as a real problem, not a tech-stack exercise. The systems thinking is the constant; the stack is whatever the problem called for.

**[Alebus](https://github.com/MathewM27/alebus-public)** — Mauritius has no reliable way to know when a bus is coming, so I built the missing infrastructure: GPS telemetry from bus-mounted devices flows through MQTT into a Go backend, fans out via Redis Pub/Sub, and reaches riders as live locations and ETAs in under 760ms end-to-end. Backend, React Native rider app, and Next.js operator dashboard — designed, built, and deployed to production solo.
| Metric | Value |
|---|---|
| End-to-end latency | ~760ms median (GPS ping → client render) |
| Concurrent WebSocket connections | 10,000 (load tested) |
| Architecture | DDD · 5 bounded contexts · Hexagonal |
* [Mobile App](https://github.com/MathewM27/alebus) · [Operator Dashboard](https://github.com/MathewM27/v0-operators-dashboard-app) · [GPS Tracker](https://github.com/MathewM27/alebus-gps-tracker)*

**Freelance client work** — I run an independent practice end to end: scoping, requirements, pricing, and delivery, not just implementation.
- **Lifestyle Aviation Jet Limited** — multi-phase engagement for a private aviation charter company: Next.js website redesign shipped, with a companion React Native/Expo mobile app for bookings and services currently in development
- **AQMS (Automotive Quotation Management System)** *(in progress)* — a Go/Gin + Next.js system replacing a manual Excel-based vehicle estimating process for an auto re-finishing workshop client. Includes a conversational entry mode (Claude Haiku) that lets the owner describe a job in plain text — AI structures the input, the backend handles all pricing logic and calculation, and a branded PDF quotation is generated automatically, cutting a multi-step manual process down to under a minute

**[Lakazhub](https://github.com/MathewM27/lakazhub.v1)** — two-sided long-term rental marketplace (PWA, React + Supabase). Deployed and ran a live pilot in Mauritius with real landlords and tenants before pausing for business registration — evidence I can take a product from build to real users, not just to a repo.

**[PostForge](https://github.com/MathewM27/PostForge)** — AI content generation pipeline (LangChain, GPT-4) exploring orchestration patterns for multi-step generation — article, SEO metadata, and social carousel from a single input.

---

## 📫 Let's connect

- 🌐 [Portfolio](https://mathews-mwangi.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/mathews-mwangi-972839219/)
- 📧 mathewsmwangi6927@gmail.com

---

<sub>Open to full-stack engineering roles, remote or relocation — I bring the same problem-first, systems-thinking approach to a team that I bring to my own projects and clients.</sub>
