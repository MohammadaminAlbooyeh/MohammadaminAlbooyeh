# 👋 Hi, I'm Amin

**Senior Backend Engineer · Python & Java · Distributed Systems · 10+ years**  
📍 Turin, Italy · Open to backend roles (remote or Italy-based)

I build backend systems that hold up under real production load: event-driven microservices, async task pipelines,
high-throughput APIs, and the cloud infrastructure that runs them.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat&logo=openjdk&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)

---

## 🏆 Highlights

- **Tech lead of a 5-engineer team** at Quera (largest EdTech platform in Iran, 2M+ users): ran architecture reviews, owned code review, and introduced PR conventions that cut post-merge regressions by ~40%.
- **Architected an async task pipeline** (FastAPI + Celery + RabbitMQ) processing 500k+ background jobs/day, decoupling ingestion from execution across distributed workers.
- **Cut p95 read latency by ~60%** under peak traffic by tuning PostgreSQL query plans, Redis caching, and platform-wide Elasticsearch search.
- **Owned cloud infrastructure** on AWS and DigitalOcean: containerised every service, orchestrated with Kubernetes, and automated releases via GitHub Actions and GitLab CI, bringing manual release steps to zero.
- **Rebuilt a monolith into independently deployable REST services**, raising deploy frequency from monthly to weekly.
- **Java backend experience**: Spring Boot and Spring Data JPA in production, plus current Java 17 / Spring Boot 3 work with Kafka sagas and the transactional outbox pattern.

---

## 🚀 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| 🛒 **[scalable-ecommerce-platform](https://github.com/MohammadaminAlbooyeh/scalable-ecommerce-platform)** | E-commerce backend of 14 microservices with Kong gateway, Kafka event flows, and Kubernetes + Terraform deployment | Python/FastAPI, Java/Spring Boot, Kafka, Kong, Kubernetes, Terraform |
| 📦 **[order-service](https://github.com/MohammadaminAlbooyeh/order-service)** | Order lifecycle microservice: Kafka saga orchestration with compensation, transactional outbox, idempotent consumers, dead-letter topics | Java 17, Spring Boot 3, Kafka, PostgreSQL |
| ⏱️ **[rate-limiter-service](https://github.com/MohammadaminAlbooyeh/rate-limiter-service)** | Multi-tenant rate limiting with 5 algorithms (Token Bucket, Sliding Window, Leaky Bucket…) on Redis + atomic Lua scripts; sustains 10k+ req/s in load tests | Python, FastAPI, Redis, Lua |
| 🔄 **[streaming-data-processor](https://github.com/MohammadaminAlbooyeh/streaming-data-processor)** | Kafka event streaming pipeline: parallel consumer groups for enrichment, windowed aggregation, fraud detection at 50k+ events/min, WebSocket dashboard | Python, Kafka, WebSocket |
| ⚙️ **[distributed_task_queue](https://github.com/MohammadaminAlbooyeh/distributed_task_queue)** | Distributed task queue with async workers, priority queues, automatic retries, and fault isolation | Python, FastAPI, Redis, PostgreSQL |
| 🏦 **[banking-core](https://github.com/MohammadaminAlbooyeh/banking-core)** | Core banking backend with accounts, transactions, and ledger consistency | Java, Spring Boot, Spring Data JPA, PostgreSQL |

<details>
<summary><b>📂 More projects</b></summary>

<br>

**Java / Spring Boot**
- 🧾 [telecom-billing-system](https://github.com/MohammadaminAlbooyeh/telecom-billing-system) — Telecom billing backend
- 📦 [inventory-service](https://github.com/MohammadaminAlbooyeh/inventory-service) — Inventory microservice
- 🛒 [cart-service](https://github.com/MohammadaminAlbooyeh/cart-service) — Shopping cart microservice
- 🔎 [product-search-engine](https://github.com/MohammadaminAlbooyeh/product-search-engine) — Product search service
- 📚 [digital-library-platform](https://github.com/MohammadaminAlbooyeh/digital-library-platform) — Digital library backend

**Python backend & infrastructure**
- 🏗️ [microservices_orchestrator](https://github.com/MohammadaminAlbooyeh/microservices_orchestrator) — Multi-service orchestration with fault isolation
- 🌐 [api_gateway_with_rate_limiting](https://github.com/MohammadaminAlbooyeh/api_gateway_with_rate_limiting) — API gateway with Redis-backed rate limiting and routing
- 🔐 [user_authentication_API](https://github.com/MohammadaminAlbooyeh/user_authentication_API) — JWT auth with role-based access control
- 🛍️ [order_processing_system](https://github.com/MohammadaminAlbooyeh/order_processing_system) — Order processing microservices with JWT auth and async notifications
- 💬 [real_time_chat_app](https://github.com/MohammadaminAlbooyeh/real_time_chat_app) — WebSocket chat with Redis Pub/Sub fan-out
- 🔔 [real_time_notification_system](https://github.com/MohammadaminAlbooyeh/real_time_notification_system) — Real-time notification infrastructure
- 📡 [uptime_monitor](https://github.com/MohammadaminAlbooyeh/uptime_monitor) — Production uptime monitoring

**Data & ETL**
- 🏭 [Data-Warehouse-for-E-Commerce](https://github.com/MohammadaminAlbooyeh/Data-Warehouse-for-E-Commerce) — End-to-end data warehouse and ETL pipeline
- 🌦️ [weather_ETL_project](https://github.com/MohammadaminAlbooyeh/weather_ETL_project) — Automated weather data ETL

**Web apps**
- 🎨 [Showcase Website](https://showcase-website-cql3.vercel.app/) — Portfolio site
- 💰 [Salary Calculator](https://salary-calculator-five-ecru.vercel.app/) — Interactive salary calculator

</details>

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **Languages** | Python (advanced), Java 17, SQL, Bash |
| **Frameworks** | FastAPI, Django, Flask, Spring Boot 3, Spring Data JPA |
| **Databases & search** | PostgreSQL, MySQL, MongoDB, Redis, Elasticsearch |
| **Async & messaging** | Kafka, Celery, RabbitMQ, Amazon SQS |
| **Cloud & DevOps** | AWS, Azure, DigitalOcean, Docker, Kubernetes, Terraform, GitHub Actions, GitLab CI, Linux |
| **Architecture** | Microservices, Event-Driven Architecture, Saga / Outbox patterns, Clean Architecture, REST API design |
| **Testing & observability** | Pytest, JUnit, integration testing, Prometheus, Grafana, Jaeger |

---

## 📊 GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MohammadaminAlbooyeh&show_icons=true&theme=default&hide_border=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohammadaminAlbooyeh&layout=compact&hide_border=true" alt="Top languages" />
</p>

---

## 📫 Let's Connect

- 📧 [amin.albooyeh@gmail.com](mailto:amin.albooyeh@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/amin-a-95a541176/)
- 🌐 [Portfolio](https://showcase-website-cql3.vercel.app/)

Happy to talk about system design, event-driven architecture, or a backend role where reliability actually matters.
