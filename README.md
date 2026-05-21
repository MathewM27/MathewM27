# Hey, I'm Mathews 👋

Software engineer & founder based in Mauritius. I build software that solves real problems — starting with the ones I live with every day.

Currently focused on [**Alebus**](https://your-alebus-link.com) — a real-time bus tracking and fleet operations platform I built out of years of daily frustration with unpredictable public transport on the island. I went from frustrated commuter to founder.

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

## ✍️ Writing

I write about distributed systems, building in emerging markets, and lessons from shipping real products.

→ [mathews-mwangi.com/blog](https://mathews-mwangi.com/blog)

---

## 📚 Currently learning

- **Kubernetes** — container orchestration at scale
- **Terraform** — infrastructure as code
- **gRPC** — high-performance service communication
- Deepening my **Go** — concurrency patterns, performance tuning

---

## 📫 Let's connect

- 🌐 [Portfolio](https://mathews-mwangi.com)
- 💼 [LinkedIn](https://linkedin.com/in/your-handle)
- ✍️ [Blog](https://mathews-mwangi.com/blog)
- 📧 your@email.com

---

<sub>Open to software engineering roles — especially teams building infrastructure, developer tools, or platforms that matter to real communities.</sub>
