# Hey, I'm Mathews 👋

**Backend Engineer · Go · Distributed Systems · Real-time Architecture**
 
[![Portfolio](https://img.shields.io/badge/Portfolio-mathews--mwangi.com-000000?style=flat&logo=safari&logoColor=white)](https://mathews-mwangi.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mathews-mwangi-972839219)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mathewsmwangi6927@gmail.com)
 
*Building distributed backend systems designed for scale — event-driven architectures, high-throughput pipelines, and real-time infrastructure that operates reliably under continuous load.*

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
