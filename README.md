<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0f172a,100:2563eb&text=Nitesh%20Kumar%20Sah&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20Distributed%20Systems%20%C2%B7%20Event-Driven%20Architecture&descAlignY=60&descSize=17" alt="Nitesh Kumar Sah - Backend Engineer" />

<a href="https://github.com/Nitesh123-Nits/Nitesh123-Nits">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=900&color=2563EB&center=true&vCenter=true&width=720&lines=Java+%C2%B7+Spring+Boot+%C2%B7+Kafka+%C2%B7+Kubernetes;I+build+resilient+microservices+that+scale;SDE+%40+Aditya+Birla+Capital+(ex-Jio+Platforms);Open+to+SDE-2+%2F+Backend+roles+%E2%80%94+Pan-India+or+Remote" alt="Typing intro" />
</a>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://nitesh123-nits.github.io/Nitesh-kumar-sah/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nitesh--kumar--sah)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Nitesh123-Nits/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@devcookies)
[![DEV.to](https://img.shields.io/badge/DEV.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/devcorner)

</div>

---

## 👋 About me

I'm a **backend engineer with 3+ years of experience** designing and shipping Java / Spring Boot microservices, event-driven pipelines and platform tooling. I like the unglamorous parts of production systems: retries that actually converge, idempotent consumers, caches that don't lie, and rollouts that don't page anyone at 3 AM.

- 🏦 **Now:** SDE at **Aditya Birla Capital**, building the backend for wealth products (Fixed Deposits, DigiMetal gold/silver, SIPs)
- 📡 **Before:** SDE at **Jio Platforms**, on the lifecycle platform for enterprise VPN networking products
- 🎓 B.Tech, Electronics & Communication, **NIT Silchar** (2023)
- 🧠 **Exploring:** LLM / RAG / Spring AI for backend engineers, observability, and system design at scale
- 🎯 **Looking for:** SDE-2 / Senior Backend roles at product and fintech companies, Pan-India or fully remote

---

## 🧰 Tech stack

<div align="center">

**Languages & Frameworks**

<img src="https://skillicons.dev/icons?i=java,spring,js,angular,html,css&perline=10" alt="Languages and frameworks" />

**Messaging, Data & Caching**

<img src="https://skillicons.dev/icons?i=kafka,rabbitmq,redis,mysql,mongodb&perline=10" alt="Messaging and data" />

**Cloud, DevOps & Infra**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,ansible,github,githubactions,linux,git&perline=10" alt="Cloud and DevOps" />

**Observability**

<img src="https://skillicons.dev/icons?i=prometheus,grafana,opentelemetry&perline=10" alt="Observability" />

</div>

| Area | What I work with |
|---|---|
| **Backend** | Java 17, Spring Boot, Spring Cloud (Eureka, Config Server, API Gateway), Spring Security + JWT, Spring Scheduler |
| **Architecture** | Microservices, event-driven design, async/parallel execution, distributed locking, retries & graceful degradation, layered clean architecture |
| **Messaging** | Apache Kafka (consumer groups, job dispatch pipelines), RabbitMQ |
| **Data** | MySQL, MongoDB, Redis (caching at critical layers) |
| **Platform** | Docker, Kubernetes, Helm, Ansible, GitHub Actions, AWS (EC2, S3, RDS, IAM) |
| **Observability** | OpenTelemetry, Prometheus, Grafana, Loki, Tempo |
| **AI** | Spring AI, LLM integration, RAG, agentic workflows (LangGraph), Python / FastAPI |

---

## 💼 Experience

### Aditya Birla Capital · SDE · *Aug 2026 – Present* · Navi Mumbai
- Re-architected API flows for **Fixed Deposit, DigiMetal (gold/silver) and SIP** from sequential DB / third-party calls to **parallel async execution**, cutting end-to-end latency.
- Introduced **Redis caching** at critical layers to reduce DB round-trips and downstream load.
- Refactored legacy code: broke up God classes, applied SOLID, moved to a clean layered architecture.

### Jio Platforms · SDE · *Oct 2023 – Aug 2026* · Navi Mumbai
- Built **Spring Boot microservices** for the provision / modify / delete lifecycle of enterprise VPN networking products.
- Designed a **Kafka-based job dispatch pipeline** operating across **thousands of enterprise devices**.
- Built a config & automation engine that generates device configs and IPs, giving a **20% operational efficiency gain**.
- Delivered a resilient provisioning service for real-time config / password updates with **retries and graceful failure handling**.
- Secured services with **JWT + Spring Security**; tuned CRUD paths for a **75% performance improvement**.
- Containerised services with **Docker + Kubernetes**, reaching **2× throughput at peak load**.

---

## 🚀 Featured work

### Flagship system
**Distributed Device Configuration Backup Scheduler** — *Java 17 · Spring Boot · Kafka · Ansible · Kubernetes*
A scheduler that triggers daily per-device config backups through **Kafka consumer groups**, with **Ansible** fetching versioned config snapshots. Uses a **distributed lock** so only one scheduler instance publishes (no duplicate jobs), plus retries, failure alerting and a REST API for per-device status. My personal rebuild of a production problem I worked on, with full observability (OpenTelemetry, Prometheus, Grafana).

### Open-source repos

| Project | What it is |
|---|---|
| [**faang-roadmap**](https://github.com/Nitesh123-Nits/faang-roadmap) · [live](https://nitesh123-nits.github.io/faang-roadmap/) | Installable PWA for tracking FAANG-style interview prep, with light/dark mode and a customisable roadmap |
| [**Java-Field-Manual-Backend**](https://github.com/Nitesh123-Nits/Java-Field-Manual-Backend) | Study site covering Java concurrency, Spring Boot, microservices, distributed systems, Kafka and Redis |
| [**Springboot-FullStcak-Ecommerce-Application**](https://github.com/Nitesh123-Nits/Springboot-FullStcak-Ecommerce-Application) | Multi-role e-commerce platform: Spring Boot 3 + PostgreSQL + React, JWT with user / seller / admin roles, Stripe payments, OpenAPI docs |
| [**Enterprise-Knowledge-Orchestrator**](https://github.com/Nitesh123-Nits/Enterprise-Knowledge-Orchestrator) | Agentic AI platform: a LangGraph supervisor routes questions between a SQL agent and a FAISS-based RAG agent; FastAPI + React |
| [**spring-ai-projects**](https://github.com/Nitesh123-Nits/spring-ai-projects) | Spring AI + OpenAI apps: chat, image generation, recipe generator and audio transcription, with React front-ends |
| [**chat-service**](https://github.com/Nitesh123-Nits/chat-service) | One-to-one chat over REST and STOMP WebSockets with stable cursor-based pagination and authorisation checks |
| [**Inter-Service-Communication**](https://github.com/Nitesh123-Nits/Inter-Service-Communication) | Blog series on service-to-service calls in Spring Boot: RestTemplate, RestClient, WebClient, Feign, HTTP Exchange |
| [**Kubernetes-helm**](https://github.com/Nitesh123-Nits/Kubernetes-helm) · [**helm-chart**](https://github.com/Nitesh123-Nits/helm-chart) | Kubernetes and Helm deployment practice |

### Engineering notes & guides
Writing things down is how I learn. These repos are my public notebooks:
[Distributed-system-concepts](https://github.com/Nitesh123-Nits/Distributed-system-concepts) ·
[Distributed-system-tracker](https://github.com/Nitesh123-Nits/Distributed-system-tracker) ·
[distributed-transaction](https://github.com/Nitesh123-Nits/distributed-transaction) ·
[database-scaling-guide](https://github.com/Nitesh123-Nits/database-scaling-guide) ·
[observability-guide](https://github.com/Nitesh123-Nits/observability-guide) ·
[springboot-app-optimization](https://github.com/Nitesh123-Nits/springboot-app-optimization) ·
[spring-boot-lifecycle](https://github.com/Nitesh123-Nits/spring-boot-lifecycle) ·
[production-issue](https://github.com/Nitesh123-Nits/production-issue) ·
[interview-ready-multithreading](https://github.com/Nitesh123-Nits/interview-ready-multithreading) ·
[LLD-Guide](https://github.com/Nitesh123-Nits/LLD-Guide) ·
[Design_Pattern](https://github.com/Nitesh123-Nits/Design_Pattern) ·
[master-system-design](https://github.com/Nitesh123-Nits/master-system-design) ·
[deployment-strategy](https://github.com/Nitesh123-Nits/deployment-strategy) ·
[cron-schedular-hld](https://github.com/Nitesh123-Nits/cron-schedular-hld)

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Nitesh123-Nits&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nitesh123-Nits&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=Nitesh123-Nits&theme=tokyonight&hide_border=true" alt="Contribution streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Nitesh123-Nits&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" />

</div>

---

## 🤝 Let's connect

I'm open to **SDE-2 / Senior Backend Engineer** opportunities (Java, Spring Boot, distributed systems), Pan-India or remote. See my [portfolio](https://nitesh123-nits.github.io/Nitesh-kumar-sah/) for the full picture; the fastest way to reach me is [LinkedIn](https://linkedin.com/in/nitesh--kumar--sah).

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:2563eb,100:0f172a&section=footer" alt="footer" />

</div>
