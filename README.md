# Hey, I'm Mathews 👋

I'm a backend engineer who builds distributed systems in Go. I got tired of not knowing when my bus would arrive, so I built [Alebus](https://github.com/MathewM27/alebus-api) — a real-time public transport platform tracking live bus locations across the island. That's the kind of engineer I am: I find a real problem, figure out the architecture, and ship it.

I'm drawn to event-driven backends, high-throughput pipelines, and infrastructure that stays reliable under load. Currently deepening my Go, picking up Kubernetes and Terraform, and writing about what I learn along the way.

**Backend Engineer · Go · Distributed Systems · Real-time Architecture**

[![Portfolio](https://img.shields.io/badge/Portfolio-mathews--mwangi.com-000000?style=flat&logo=safari&logoColor=white)](https://mathews-mwangi.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathews-mwangi-972839219)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mathewsmwangi6927@gmail.com)

---

## Flagship Project — Alebus

**Real-time public transport intelligence platform for Mauritius**

GPS telemetry from bus-mounted devices flows through an EMQX MQTT broker into a Go event-driven backend, fans out via Redis Pub/Sub to WebSocket clients, and surfaces as live bus locations and stop-by-stop ETAs — in under 760ms end-to-end. Designed, built, and deployed to production by a single engineer.

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


## 📚 Currently learning

- **Kubernetes** — container orchestration at scale
- **Terraform** — infrastructure as code
- **gRPC** — high-performance service communication
- Deepening my **Go** — concurrency patterns, performance tuning

---

## 📫 Let's connect

- 🌐 [Portfolio](https://mathews-mwangi.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/mathews-mwangi-972839219/)
- ✍️ [Blog](https://mathews-mwangi.com/blog)
- 📧 mathewsmwangi6927@gmail.com

---

<sub>Open to software engineering roles — especially teams building infrastructure, developer tools, or platforms that matter to real communities.</sub>
