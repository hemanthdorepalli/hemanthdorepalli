<h1 align="center">Hemanth Dorepalli</h1>

<p align="center">
  <strong>Backend-focused Full Stack Engineer</strong> &nbsp;·&nbsp; Python · Node.js · Secure & Scalable Systems
</p>

<p align="center">
  Vijayawada, India &nbsp;·&nbsp; Available for full-time roles
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hemanth-3b7a26295/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://hemanth-labs.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-1A1A1A?style=flat&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:hemanthd0916@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/hemanthdorepalli"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

---

## Introduction

Backend-focused Full Stack Engineer with 3+ years of experience building secure, scalable production systems — authentication platforms, distributed task pipelines, real-time data services, and AI/LLM integrations.

I work primarily in **Python** (Django, FastAPI) and **Node.js / TypeScript**, with **React** on the frontend. My core strengths are **authentication & API security**, **system design**, and translating complex backend requirements into reliable, well-architected services. I care about clean boundaries, predictable performance under concurrency, and code that holds up in production.

---

## Tech Stack

| Domain | Technologies |
|---|---|
| **Backend** | `Python` `Django` `FastAPI` `Node.js` `Express` `TypeScript` `REST APIs` `Microservices` |
| **Frontend** | `React` `Next.js` `Vite` `WebSocket` |
| **Databases** | `PostgreSQL` `MySQL` `Supabase` `Prisma` `Redis` |
| **Async & Messaging** | `Celery` `RabbitMQ` `BullMQ` `Redis` `AsyncIO` `Cluster` |
| **DevOps & Cloud** | `AWS (S3)` `Docker` `GitHub Actions` `CI/CD` `Gunicorn` `Daphne` `Render` `Vercel` `Linux` |
| **Security & Auth** | `OAuth2` `OIDC` `JWT / JTI Rotation` `RBAC` `SSO` `Zero-Trust` |
| **AI / LLM** | `Groq LLM` `RAG` `Streaming` `Context Engineering` `n8n` `MCP` |
| **Tools** | `Git` `Postman` `Pandas` |

> [!NOTE]
> Every technology listed is backed by production or project work — happy to go deep on any of it in an interview.

---

## Featured Projects

### FACT.Login — Centralized Authentication & SSO Platform
Single sign-on hub unifying authentication across four products, built around a Zero-Trust security model.

**Stack:** `Django` · `OAuth2` · `OIDC` · `JWT / JTI Rotation` · `Redis` · `PostgreSQL`

- OAuth2 / OIDC flows with short-lived access tokens and rotating refresh tokens
- Three-layer Zero-Trust enforcement: IP binding, device fingerprinting, location-anomaly detection
- Dual-layer token revocation (Redis + PostgreSQL) so logout and force-revoke survive a cache failure
- HTTP-only cookie strategy to mitigate XSS-based token theft

<sub>Proprietary — built at FactOps (Member Venture, Station-S)</sub>

---

### FACT.Safe — Multi-Tenant Secure Document Platform
Encrypted, multi-tenant document vault with fine-grained access control and audited delegation.

**Stack:** `Django` · `AWS S3` · `PostgreSQL` · `Celery` · `Redis` · `RBAC`

- Row-level tenant isolation enforced at the data-access layer
- Encrypted AWS S3 storage with server-side and application-level encryption
- Per-user, per-category RBAC with an auditable delegation workflow
- Heavy document processing offloaded to Celery workers to keep the API responsive

<sub>Proprietary — built at FactOps (Member Venture, Station-S)</sub>

---

### BRAHMO — Healthcare AI Context-Assembly Agent
A composition agent that assembles structured clinical context for LLM sessions under a strict token budget.

**Stack:** `FastAPI` · `Python` · `Next.js` · `Supabase` · `Groq LLM (llama-3.3-70b)` · `RAG`

- Assembles 27 hospital knowledge nodes into a structured 8-block context string
- Hard 4,000-token ceiling with priority-based budget fitting
- CONSTRAINT-node protection ensures safety-critical rules (drug interactions, contraindications) are never dropped under compression
- Streaming responses with per-patient context filtering

<sub>Repository: <a href="https://github.com/hemanthdorepalli">github.com/hemanthdorepalli</a></sub>

---

### Software Leads — Client & Project Management CRM
SaaS CRM covering the full client lifecycle — from automated lead capture to proposal generation.

**Stack:** `Node.js` · `Express` · `TypeScript` · `Next.js` · `Prisma` · `Supabase` · `Redis` · `BullMQ`

- Meta (Facebook & Instagram) Lead Ads API + Webhooks for automated lead capture and onboarding
- Lifecycle workflows: requirement gathering, cost estimation, developer assignment, payment tracking
- Redis + BullMQ background jobs for PDF proposals, email notifications, and bulk imports with retry and queue management
- Node.js Cluster Module for multi-core scaling, with JWT auth and role-based access

<sub>Client project — Dunga Technologies</sub>

---

### Weewa — Real-Time IoT Monitoring Platform
Real-time ingestion, analytics, and alerting for environmental sensors across distributed sites.

**Stack:** `FastAPI` · `React` · `WebSocket` · `Celery` · `RabbitMQ` · `PostgreSQL` · `Pandas`

- Processes sensor readings from LoRaWAN and cellular devices across 20+ remote locations
- WebSocket streaming to React dashboards, cutting refresh lag from minutes to seconds
- Pandas/ML analytics on Celery workers, with RabbitMQ ensuring zero task loss on restart
- Automated health alerts (WhatsApp / email) on data gaps

<sub>Proprietary — built at ZdotApps (Member Venture, Station-S)</sub>

---

## Professional Experience

| Role | Organization | Period | Focus |
|---|---|---|---|
| **Full Stack Developer** | FactOps Pvt. Ltd. <sub>(Station-S)</sub> | May 2025 – Present | Authentication platforms, secure multi-tenant systems, RBAC |
| **Full Stack Developer** | ZdotApps Pvt. Ltd. <sub>(Station-S)</sub> | Nov 2024 – May 2025 | Real-time IoT data pipelines, WebSockets, async processing |
| **Technical Trainer** | SocialTek Solutions | Oct 2022 – Jul 2024 | Taught full-stack development; built 15+ demo applications; mentored 50+ students |

---

## GitHub Statistics

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=hemanthdorepalli&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=github_dark&title_color=58a6ff&icon_color=58a6ff">
  <img src="https://github-readme-stats.vercel.app/api?username=hemanthdorepalli&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=default&title_color=0969da&icon_color=0969da" width="48%" alt="GitHub Stats"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=hemanthdorepalli&hide_border=true&theme=github-dark-blue">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hemanthdorepalli&hide_border=true&theme=default" width="48%" alt="GitHub Streak"/>
</picture>

</div>

---

## Coding Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=hemanthdorepalli&layout=compact&hide_border=true&langs_count=8&theme=github_dark&title_color=58a6ff">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hemanthdorepalli&layout=compact&hide_border=true&langs_count=8&theme=default&title_color=0969da" width="50%" alt="Top Languages"/>
</picture>

</div>

---

## Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=hemanthdorepalli&hide_border=true&theme=github-compact">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=hemanthdorepalli&hide_border=true&theme=minimal" width="100%" alt="Contribution Graph"/>
</picture>

</div>

---

## Contact

| | |
|---|---|
| **Email** | [hemanthd0916@gmail.com](mailto:hemanthd0916@gmail.com) |
| **LinkedIn** | [linkedin.com/in/hemanth-3b7a26295](https://www.linkedin.com/in/hemanth-3b7a26295/) |
| **Portfolio** | [hemanth-labs.netlify.app](https://hemanth-labs.netlify.app/) |
| **Location** | Vijayawada, India |

<p align="center"><sub>Open to backend engineering, secure platforms, SaaS, and AI product roles.</sub></p>
