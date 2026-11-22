<div align="center">

<!-- Typing SVG animado -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Senior+Backend+Engineer+%F0%9F%87%A8%F0%9F%87%B4;Software+Architect+%E2%80%94+Go+%26+AWS+Serverless;Fintech+%7C+Distributed+Systems+%7C+AI+Tooling;Building+resilient+systems+at+scale)](https://git.io/typing-svg)

<h1>Kevin Andrey Herrera Silva</h1>
<h3>Senior Backend Engineer & Software Architect</h3>

<p>
  <a href="https://www.linkedin.com/in/kevinandrey96/">
    <img src="https://img.shields.io/badge/LinkedIn-kevinandrey96-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:kahs_kevin@hotmail.com">
    <img src="https://img.shields.io/badge/Email-kahs__kevin%40hotmail.com-D14836?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email" />
  </a>
  <img src="https://img.shields.io/badge/📍_Bogotá,_Colombia-UTC--5-green?style=for-the-badge" alt="Location" />
  <img src="https://img.shields.io/badge/🌐_Remote-Open_to_work-brightgreen?style=for-the-badge" alt="Remote" />
</p>

</div>

---

### 👋 About Me

Senior Backend Engineer and **Software Architect** based in Bogotá, Colombia. Over the past decade I have designed and operated **mission-critical distributed systems** for fintech, retail, and enterprise clients across the Americas.

At **Modak** (US-based family banking fintech), I architected the core transactional backend in **Go and AWS Serverless**, scaling to **250,000+ active users** with:
- ✅ **99.98% uptime** in production
- ✅ **sub-120ms p99 latency** across event-driven microservices
- ✅ **Zero-loss ledger reconciliation** and idempotent money movement

I treat AI as a fundamental engineering utility — I orchestrate advanced agents and tool protocols (Claude Code, Cursor, MCP) daily as a **technical orchestrator**, accelerating feature delivery without compromising architectural rigor or test coverage.

---

### 🛠️ Tech Stack

```text
Languages       Go (Golang) · Python · Java / Kotlin · TypeScript
Cloud           AWS Lambda · API Gateway · EventBridge · DynamoDB · SQS · SNS · S3 · CDK
Architecture    Event-Driven (Pub/Sub) · Hexagonal / Clean · DDD · Serverless Microservices
Databases       DynamoDB (Single-Table Design) · PostgreSQL · MySQL · Redis · MongoDB
Observability   ELK Stack · CloudWatch · Distributed Tracing
Containers      Docker · Kubernetes
AI Tooling      Agent Orchestration · Claude Code · Cursor · MCP Protocols · Local LLMs (MLX)
APIs            RESTful · gRPC · GraphQL
IaC             AWS CDK · CloudFormation
```

<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)

</div>

---

### 🚀 Featured Architecture & Engineering Showcases

| Project | Tech Stack | Architecture & Key Highlights |
| :--- | :--- | :--- |
| **[serverless-events-platform](https://github.com/KevinAndrey96/serverless-events-platform)** | Go · AWS Lambda · DynamoDB · Laravel 9 · Vite | **Full-Stack Polyglot Monorepo.** End-to-end event lifecycle platform: Go AWS Lambda microservices (DynamoDB Single-Table Design, GSI indexing, EventBridge 6h cron worker with TLS SMTP reminders) + Laravel 9/Vite portal with live camera QR entrance validation (`Instascan.js`), automated PDF passes (`DomPDF`), and Hexagonal Architecture. Features formal **Architecture Decision Records (ADRs)** and turnkey Docker Compose / LocalStack orchestration. |
| **[pharmacy-ecommerce-platform](https://github.com/KevinAndrey96/pharmacy-ecommerce-platform)** | Node.js · AdonisJS · MySQL / SQLite · Docker | **Full-Stack Pharmacy E-Commerce Platform & Inventory Backoffice.** End-to-end pharmaceutical store: catalog search with therapeutic category hierarchy, session shopping cart, coupon discount engine, multi-gateway payment redirection, automated email notifications, and an integrated management backoffice (product CRUD, orders tracking, customer CRM, analytics). Features full Docker Compose stack (MySQL 8 + Mailpit SMTP testbed) and automated CI. |
| **[pcp-industrial-wholesale-ecommerce](https://github.com/KevinAndrey96/pcp-industrial-wholesale-ecommerce)** | Laravel 8 · PHP 8.1 · MySQL 8.0 · Docker | **Enterprise B2B Industrial Wholesale Distribution Platform.** Multi-tier supply chain orchestration connecting industrial valve/piping manufacturers, regional master distributors, and local hardware stores (*ferreterías*). Features layered clean architecture with Service Layer (`OrderService`), formal B2B quotation negotiation engine, dynamic print-ready PDF generation (`InvoicePdfService` / `DomPDF`), transactional email alerts, and Docker Compose stack (MySQL 8 + Mailpit). |
| **[go-serverless-notification-rate-limiter](https://github.com/KevinAndrey96/go-serverless-notification-rate-limiter)** | Go · AWS Lambda · DynamoDB · SES | Enterprise-grade event-driven notification rate limiter microservice using Clean Architecture, DynamoDB conditional expressions, and SES delivery. |
| **[go-serverless-calendar-overlap](https://github.com/KevinAndrey96/go-serverless-calendar-overlap)** | Go · AWS Lambda · Google Wire · Concurrency | Concurrent double-booking & calendar interval collision detector with goroutines, mutex synchronization, and compile-time dependency injection. |
| **[adonisjs-cart-pricing-evaluator](https://github.com/KevinAndrey96/adonisjs-cart-pricing-evaluator)** | Node.js · AdonisJS · Docker · MySQL | High-concurrency cart pricing & fulfillment evaluation engine with complex business rules, multi-warehouse allocation, and full containerization. |
| **[laravel-vue-warehouse-management](https://github.com/KevinAndrey96/laravel-vue-warehouse-management)** | Laravel · Vue.js · MySQL · Postman | Full-stack warehouse inventory management system with decoupled REST API, Vue SPA frontend, role-based auth, and automated collection. |

---

### 📚 Open Source Technical Guides & Datasets

| Repository | Domain / Focus | Key Highlights |
| :--- | :--- | :--- |
| **[ciudades-colombia-json](https://github.com/KevinAndrey96/ciudades-colombia-json)** | TypeScript · npm Library · Open Data | Packaged npm library (`ciudades-colombia`) and open dataset of all 32 departments and 1,104 municipalities of Colombia with accent-insensitive search, TypeScript type definitions, and SQL dumps. |
| **[dynamo-battle-royale](https://github.com/KevinAndrey96/dynamo-battle-royale)** | DynamoDB · Python · Boto3 | Comprehensive NoSQL Single-Table Design architectural guide detailing sparse indexes, conditional writes, and relational modeling without JOINs. |
| **[patron-proxy](https://github.com/KevinAndrey96/patron-proxy)** | Java · GoF Design Patterns | Gang of Four (GoF) Structural Proxy pattern guide: virtual proxy lazy loading, smart references, and access control with UML sequence diagrams. |
| **[seguridad-jaas](https://github.com/KevinAndrey96/seguridad-jaas)** | Java EE · Web Security · RBAC | Enterprise Java EE Web Security guide: form-based declarative authentication, JAAS realm integration, and Role-Based Access Control (RBAC). |
| **[react-state-immutability-guide](https://github.com/KevinAndrey96/react-state-immutability-guide)** | React · JavaScript · State Architecture | In-depth React state management guide: state immutability, lifting state up, controlled components, and time-travel debugging. |
| **[angular-reactive-architecture](https://github.com/KevinAndrey96/angular-reactive-architecture)** | Angular · TypeScript · RxJS | Enterprise Angular architecture guide: Dependency Injection (DI), RxJS reactive streams (`debounceTime`, `switchMap`), and declarative SPA routing. |
| **[express-node-architecture-guide](https://github.com/KevinAndrey96/express-node-architecture-guide)** | Node.js · Express · EJS | Node.js & Express backend architecture guide: middleware pipeline (*Chain of Responsibility*), RESTful routing, and SSR with EJS templates. |
| **[dian-nit-validator-python](https://github.com/KevinAndrey96/dian-nit-validator-python)** | Python · PyPI Package · Fintech | Published PyPI package (`pip install dian-nit-validator`) and CLI for calculating and validating Colombian DIAN NIT verification digits (Modulo 11, Estatuto Tributario Art. 375). |
| **[greedy-spatial-allocation-python](https://github.com/KevinAndrey96/greedy-spatial-allocation-python)** | Python · Greedy Algorithms · Systems | Greedy spatial allocation algorithm: iterative midpoint placement across the longest contiguous unoccupied run with complexity analysis and unit tests. |
| **[adonisjs-mvc-architecture](https://github.com/KevinAndrey96/adonisjs-mvc-architecture)** | AdonisJS · Lucid ORM · Node.js | AdonisJS v4 MVC architectural reference: IoC container, service providers, Lucid ORM migrations, and Ace CLI tooling. |
| **[rails-devise-auth-guide](https://github.com/KevinAndrey96/rails-devise-auth-guide)** | Ruby on Rails · Devise · Security | Ruby on Rails user authentication architecture guide with the Devise gem and security filters. |

---

### 💼 Professional Experience

| Company | Role | Period | Highlights |
| :--- | :--- | :--- | :--- |
| **Modak** (US Fintech) | Senior Backend Engineer | 2023 – Present | Core user & financial platform for 250K+ users. Go, AWS Serverless, KYC/IAM, ledger reconciliation, zero-fault money movement. |
| **Merqueo** (Retail Tech) | Technical Leader | 2021 – 2023 | High-concurrency retail engine across CO, MX, BR. Zero downtime during peak traffic. ELK observability rollout. |
| **AB InBev** (Global FMCG) | Senior Backend Developer | 2020 – 2021 | Cloud-native microservices in Go & Python for global commercial operations. |
| **Instance Shape SAS** | Technical Leader | 2018 – 2020 | End-to-end solutions architecture, AWS cloud deployments, multi-client delivery. |
| **Dual Branding Studio** | Software Developer | 2016 – 2018 | Full-stack web & mobile apps (Java, Kotlin, VueJS). |

---

### 🎓 Education & Honors

**Universidad Nacional de Colombia**
B.S. in Systems and Computer Engineering · 2017 – 2022

**Universidad Distrital Francisco José de Caldas**
A.S. in Data Systematization Technology · 2013 – 2017 · *Meritorious Thesis*

<br>

🏅 **Top 1% Bogotá · Top 2% Colombia** — Saber PRO National Exam (2020)
🏅 **Top 1% Bogotá · Top 2% Colombia** — Saber TyT National Exam (2016)
🏅 **Top 5.5% Nationally** — Saber 11 (2012)

---

### 🧭 Core Engineering Principles

```
 ┌─────────────────────────────────────────────────────────────────┐
 │  Speed without stability is a liability — especially in fintech.│
 │  I maintain a strict human-in-the-loop philosophy ensuring      │
 │  robust tests and deterministic logic at every layer.           │
 └─────────────────────────────────────────────────────────────────┘
```

- **Domain-Driven Design** — Bounded contexts, aggregates, and event sourcing for complex business domains
- **Zero-Fault Financial Systems** — Ledger reconciliation, idempotent operations, saga patterns
- **Observability-First** — Proactive alerting, distributed tracing, and RED metrics in production
- **AI as Infrastructure** — Agent orchestration as a multiplier, never a replacement for engineering judgment

---

### 🌐 Languages

| Language | Level |
| :--- | :--- |
| 🇨🇴 Spanish | Native |
| 🇺🇸 English | Full Professional — 4+ years daily with US & international teams |
| 🇧🇷 Portuguese | Professional Working Proficiency |

---

### 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=KevinAndrey96&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KevinAndrey96&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=KevinAndrey96&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

<div align="center">
  <em>"Software engineering is the exact science of transforming complex data flows into resilient, scalable business systems."</em>
</div>
