<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0f172a,100:2563eb&text=Nitesh%20Kumar%20Sah&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20Distributed%20Systems%20%C2%B7%20Event-Driven%20Architecture&descAlignY=60&descSize=17" alt="Nitesh Kumar Sah - Backend Engineer" />

<a href="https://github.com/Nitesh123-Nits/Nitesh123-Nits">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=900&color=2563EB&center=true&vCenter=true&width=720&lines=Java+%C2%B7+Spring+Boot+%C2%B7+Kafka+%C2%B7+Kubernetes;I+build+resilient+microservices+that+scale;SDE+%40+Aditya+Birla+Capital+(ex-Jio+Platforms);Open+to+SDE-2+%2F+Backend+roles+%E2%80%94+Pan-India+or+Remote" alt="Typing intro" />
</a>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://nitesh123-nits.github.io/Nitesh-kumar-sah/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sahnitesh54@gmail.com)
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
| **Languages** | Java 17, JavaScript |
| **Frameworks** | Spring Boot, Spring Cloud (Eureka, Config Server, API Gateway), Spring Security + JWT, Spring Scheduler, Spring AI, AngularJS |
| **Architecture** | Microservices, event-driven architecture, distributed systems, async/parallel execution, distributed locking, retries & graceful degradation, layered clean architecture |
| **Messaging** | Apache Kafka (consumer groups, job dispatch pipelines), RabbitMQ |
| **Data** | MySQL, MongoDB, Redis (caching at critical layers) |
| **Platform** | Docker, Kubernetes, Helm, Ansible, GitHub Actions, AWS (EC2, S3, RDS, IAM) |
| **Observability** | OpenTelemetry, Prometheus, Grafana, Loki, Tempo |
| **AI** | Spring AI, LLM integration, RAG, agentic workflows (LangGraph), Python / FastAPI |

---

## 💼 Experience

### Aditya Birla Capital · SDE · *Aug 2026 – Present* · Navi Mumbai
- Re-architected **3 investment product API flows** (Fixed Deposit, DigiMetal gold/silver, SIP) from sequential DB / third-party calls to **parallel asynchronous execution**, cutting end-to-end latency.
- Introduced **Redis caching** at critical layers to reduce database round-trips and downstream load.
- Built APIs for business-driven **cohort-based banners** and **referral updates**.
- Developed multiple **scheduler APIs** for lead management workflows.
- Refactored legacy modules: broke up God classes, applied **SOLID** principles and a clean layered architecture.

### Jio Platforms · SDE · *Oct 2023 – Aug 2026* · Navi Mumbai
- Improved CRUD performance by **75%** and secured services with **JWT + Spring Security**.
- Achieved **2× throughput at peak load** by containerising services with **Docker + Kubernetes**.
- Improved operational efficiency by **20%** with a configuration & automation engine that generates device configs and IP allocations.
- Designed a **Kafka-based job dispatch pipeline** distributing work across **thousands of enterprise devices**.
- Built **Spring Boot microservices** managing the full lifecycle (provision, modify, delete) of enterprise VPN networking products.
- Built a resilient provisioning service for real-time config / password updates with **retries and graceful failure handling**.
- Diagnosed and resolved numerous **production issues** across backend microservices, keeping customer-facing services stable.

---

## 🚀 Featured work

### Flagship system
**Distributed Device Configuration Backup Scheduler** — *Java 17 · Spring Boot · Kafka · Ansible · Kubernetes*
A scheduler that runs daily per-device backup jobs with **Spring Scheduler** and distributes them through **Kafka consumer groups**, with **Ansible** fetching versioned config snapshots. Uses a **distributed lock** so only one scheduler instance publishes (no duplicate jobs), plus retries, failure alerting and a REST API for per-device status. My personal rebuild of a production problem I worked on, with full observability (OpenTelemetry, Prometheus, Grafana).

### 🌐 Live apps (installable PWAs)

| App | What it is | Links |
|---|---|---|
| **DevTube** | YouTube-style PWA for engineers: developer-only feed, reels, podcasts, notes and watch-later across Java, system design, DevOps, cloud and AI | [Live](https://nitesh123-nits.github.io/Devtube/) · [Code](https://github.com/Nitesh123-Nits/Devtube) |
| **Akshar Aangan** | Ad-free learning site for kids (Nursery to Class 3): Hindi and English letters with sounds, barakhadi, maths, rhymes, colouring and drawing | [Live](https://nitesh123-nits.github.io/akshar-aangan/) · [Code](https://github.com/Nitesh123-Nits/akshar-aangan) |
| **Nanhi Seekh (Kidstube)** | Kid-safe learning-video PWA with whitelisted English and Hindi videos, no search, no outbound links | [Live](https://nitesh123-nits.github.io/Kidstube/) · [Code](https://github.com/Nitesh123-Nits/Kidstube) |
| **Java Backend Field Manual** | Study site for Java concurrency, Spring Boot, microservices, distributed systems, Kafka and Redis | [Live](https://nitesh123-nits.github.io/Java-Field-Manual-Backend/) · [Code](https://github.com/Nitesh123-Nits/Java-Field-Manual-Backend) |
| **FAANG Run 2027** | Interview-prep tracker with a customisable roadmap | [Live](https://nitesh123-nits.github.io/faang-roadmap/) · [Code](https://github.com/Nitesh123-Nits/faang-roadmap) |
| **JobHub** | Every job board in one place | [Live](https://nitesh123-nits.github.io/Job-Hub/) · [Code](https://github.com/Nitesh123-Nits/job-hub) |

### 🧠 Microservices & AI skills

| Skill | Project |
|---|---|
| Event-driven microservices | [Distributed Device Config Backup Scheduler](#flagship-system) · Kafka, Kubernetes, distributed locking |
| Service communication | [Inter-Service-Communication](https://github.com/Nitesh123-Nits/Inter-Service-Communication) · RestTemplate, WebClient, Feign |
| Real-time systems | [chat-service](https://github.com/Nitesh123-Nits/chat-service) · STOMP WebSockets, cursor pagination |
| Full-stack Spring Boot | [Springboot-FullStcak-Ecommerce-Application](https://github.com/Nitesh123-Nits/Springboot-FullStcak-Ecommerce-Application) · JWT roles, Stripe |
| Agentic AI / RAG | [Enterprise-Knowledge-Orchestrator](https://github.com/Nitesh123-Nits/Enterprise-Knowledge-Orchestrator) · LangGraph, FAISS, FastAPI |
| Spring AI | [spring-ai-projects](https://github.com/Nitesh123-Nits/spring-ai-projects) · chat, image, audio, recipe generator |

### Open-source repos

| Project | What it is |
|---|---|
| [**faang-roadmap**](https://github.com/Nitesh123-Nits/faang-roadmap) · [live](https://nitesh123-nits.github.io/faang-roadmap/) | Installable PWA for tracking FAANG-style interview prep, with light/dark mode and a customisable roadmap |
| [**Java-Field-Manual-Backend**](https://github.com/Nitesh123-Nits/Java-Field-Manual-Backend) · [live](https://nitesh123-nits.github.io/Java-Field-Manual-Backend/) | Study site covering Java concurrency, Spring Boot, microservices, distributed systems, Kafka and Redis |
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

I'm open to **SDE-2 / Senior Backend Engineer** opportunities (Java, Spring Boot, distributed systems), Pan-India or remote. See my [portfolio](https://nitesh123-nits.github.io/Nitesh-kumar-sah/) for the full picture; reach me at [sahnitesh54@gmail.com](mailto:sahnitesh54@gmail.com) or on [LinkedIn](https://linkedin.com/in/nitesh--kumar--sah).

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:2563eb,100:0f172a&section=footer" alt="footer" />

</div>
