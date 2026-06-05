# Hey, I'm Mathews 👋

I'm a full-stack engineer with a backend core — I build distributed systems in Go, then take them all the way to the screen. I got tired of not knowing when my bus would arrive, so I built [Alebus](https://github.com/MathewM27/alebus-api): a real-time public transport platform with a Go event-driven backend, a React Native mobile app, and an operator dashboard — designed, built, and shipped end-to-end by one person. That's the kind of engineer I am: I find a real problem, architect the system, and own it from database to UI.

I'm strongest in event-driven backends, high-throughput pipelines, and infrastructure that stays reliable under load — and just as comfortable building the React/Next.js front ends that sit on top. Currently deepening my Go and picking up Kubernetes and Terraform.

**Full-Stack Engineer · Go · Distributed Systems · React / Next.js · Real-time Architecture**

[![Portfolio](https://img.shields.io/badge/Portfolio-mathews--mwangi.com-000000?style=flat&logo=safari&logoColor=white)](https://mathews-mwangi.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathews-mwangi-972839219)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mathewsmwangi6927@gmail.com)

---

## What I build

- **Backend & distributed systems** — Go, event-driven architecture, real-time pipelines, PostgreSQL/PostGIS, Redis, MQTT
- **Front end & product** — React, Next.js, React Native, TypeScript — turning the systems above into things people actually use
- **Infrastructure** — Docker, GitHub Actions, observability with Prometheus & Grafana

---

## Flagship Project — Alebus

**Real-time public transport intelligence platform for Mauritius**

GPS telemetry from bus-mounted devices flows through an EMQX MQTT broker into a Go event-driven backend, fans out via Redis Pub/Sub to WebSocket clients, and surfaces as live bus locations and stop-by-stop ETAs — in under 760ms end-to-end. The full stack — backend, React Native mobile app, and Next.js operator dashboard — designed, built, and deployed to production by a single engineer.

| Metric | Value |
|---|---|
| End-to-end latency | ~760ms median (GPS ping → client render) |
| Concurrent WebSocket connections | 10,000 (load tested) |
| Architecture | DDD · 5 bounded contexts · Hexagonal |
| Runnable Go binaries | 7 (sharing one module) |
| Observability | Prometheus · Grafana · Dozzle |

**Stack:** `Go (stdlib)` `PostgreSQL + PostGIS` `Redis` `MQTT / EMQX` `WebSockets` `Docker` `GitHub Actions` `React Native` `Next.js`

→ ***[Backend API](https://github.com/MathewM27/alebus-api)** · **[Mobile App](https://github.com/MathewM27/alebus)** · **[Operator Dashboard](https://github.com/MathewM27/v0-operators-dashboard-app)** · **[GPS Tracker](https://github.com/MathewM27/alebus-gps-tracker)***

---

## Other projects

- **[Lakazhub](https://github.com/MathewM27/lakazhub.v1)** — two-sided long-term rental marketplace (PWA, React + Supabase)
- **[PostForge](https://github.com/MathewM27/PostForge)** — AI content generation tool (LangChain, GPT-4)
- **[Lifestyle Aviation](https://github.com/MathewM27/LifestyleAviation-Website)** — production site for a private aviation company

---

## 📚 Currently learning

- **Kubernetes** — container orchestration at scale
- **Terraform** — infrastructure as code
- **gRPC** — high-performance service communication
- Deepening my **Go** — concurrency patterns, performance tuning

---

## 📫 Let's connect

- 🌐 [Portfolio](https://mathews-mwangi.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/mathews-mwangi-972839219/)
- 📧 mathewsmwangi6927@gmail.com

---

<sub>Open to full-stack and backend engineering roles — especially teams building infrastructure, developer tools, or products that matter to real communities.</sub>
