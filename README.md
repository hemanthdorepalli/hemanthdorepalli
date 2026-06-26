# Hemanth Dorepalli
**Full Stack Product Engineer**  
Specializing in High-Throughput Distributed Systems, Zero-Trust Architectures, and Intelligent Business Automation.

---

## 💡 Executive Summary

I architect and engineer resilient, multi-tenant enterprise software systems. With a strong engineering foundation, my focus centers on designing high-performance backend pipelines, secure authentication layers, real-time IoT ecosystems, and optimized AI context-assembly architectures. I specialize in building deterministic infrastructure that solves complex data concurrency, security, and latency challenges.

---

## 🛠️ Technology Matrix

| Layer | Core Technologies | Focus Areas |
| :--- | :--- | :--- |
| **Backend Architecture** | Python, Django, FastAPI, Node.js, Express, TypeScript, AsyncIO, Java, Spring Boot | Distributed Systems, Scalable RESTful APIs, Resource Optimization |
| **Data Architecture** | PostgreSQL, Redis, RabbitMQ, Celery, BullMQ, Supabase, Prisma, MySQL, Pandas | Queue Concurrency, Cache Strategies, High-Availability Storage |
| **Security & Identity** | OAuth2, OpenID Connect (OIDC), JTI Token Rotation, Zero-Trust Auth, RBAC, SSO | Session Hijacking Mitigation, Deep Device Fingerprinting |
| **DevOps & Cloud** | AWS (S3, Cloud Infrastructures), Docker, GitHub Actions, Linux, Render, Vercel | Containerized Workflows, Automated CI/CD Pipelines |
| **Intelligent Systems** | Groq LLM, Retrieval-Augmented Generation (RAG), Streaming APIs, n8n, MCP | Context Optimization, Hard-Token Budget Enforcement |

---

## 🚀 Enterprise Implementations & Core Projects

### 🔒 FACT.Safe — Multi-Tenant Document Vault
> **Core Focus:** Enterprise Document Security & Query Optimization

*   **Architecture:** Designed an isolated multi-tenant system utilizing application-level encryption and dynamic, expiring access tokens via AWS S3. Built a structured Role-Based Access Control (RBAC) engine integrated with PostgreSQL full-text search.
*   **Key Metrics & Impact:**
    > ⚡ **70% Reduction** in API response latency by offloading non-blocking I/O operations to Celery background workers.
    > 🔑 **60% Efficiency Gain** in security auditing through a deterministic, granular permission delegation model.
    > 📊 Achieved deterministic **sub-100ms** metadata retrieval times on optimized indexed queries.

`Django` `PostgreSQL` `AWS S3` `JWT` `Redis` `Celery` `Zero-Trust` `RBAC`

---

### 🔑 FACT.Login — Centralized Identity Provider (IdP)
> **Core Focus:** Zero-Trust Single Sign-On (SSO) Federation

*   **Architecture:** Implemented an enterprise SSO platform compliant with OAuth2 and OIDC standards. Engineered a strict multi-layered security middleware parsing IP binding, device fingerprinting, and behavioral geographic anomalies.
*   **Key Metrics & Impact:**
    > 🛡️ **Zero Token-Theft Vectors** achieved by implementing strict HTTP-Only, SameSite cookies alongside cryptographic JTI token rotation.
    > ⚡ **< 200ms Threat Mitigation** to detect and block active session-hijacking anomalies.
    > 🔄 Built a dual-layer distributed blocklist engine (Redis cache + PostgreSQL persistence) ensuring session revocation state survives cache invalidation.

`Django` `OAuth2` `OIDC` `JWT` `JTI Rotation` `Zero-Trust` `SSO` `Redis` `PostgreSQL`

---

### 📡 Weewa — Real-Time IoT Monitoring Infrastructure
> **Core Focus:** High-Throughput Telemetry & Event-Driven Pipelining

*   **Architecture:** Developed an event-driven ingestion engine capable of aggregating real-time data from cellular and LoRaWAN environmental sensors across more than 20 distinct geographic sites.
*   **Key Metrics & Impact:**
    > 📉 Ingestion latency dropped from **5 minutes to under 2 seconds** via optimized WebSocket pipelines and FastAPI.
    > 🚨 **80% Faster Mean-Time-To-Detect (MTTD)** hardware anomalies through reactive Celery Beat heartbeat checking.
    > 📦 **Zero Message Loss** during high-concurrency spikes by implementing persistent RabbitMQ message brokers.

`FastAPI` `React` `WebSocket` `PostgreSQL` `Celery` `RabbitMQ` `Pandas`

---

### 🧠 BRAHMO — Clinical AI Context Engine
> **Core Focus:** Token-Efficient Context-Assembly for Large Language Models

*   **Architecture:** Engineered an intelligent composition layer aggregating structured data feeds from 27 disparate clinical knowledge nodes to feed analytical LLM layers.
*   **Key Metrics & Impact:**
    > 🧠 Strict enforcement of a **4,000-token operational ceiling** utilizing priority-scoring compression algorithms.
    > 🛑 **Zero-Exception Safety Execution** by designating immutable protocol rules (such as drug interactions) as uncompressed context nodes.
    > ⚡ Low-latency delivery of clinical insights powered by Groq-accelerated `llama-3.3-70b` streaming pipelines.

`FastAPI` `Next.js` `Supabase` `Groq LLM` `RAG` `Streaming` `Tailwind`

---

### 📋 Software Leads — Automated SaaS CRM Pipeline
> **Core Focus:** High-Volume Webhook Processing & Multi-Core Vertical Scaling

*   **Architecture:** Programmed an asynchronous lead intake and onboarding ecosystem natively handling real-time Meta Graph API and Instagram webhooks.
*   **Key Metrics & Impact:**
    > 🔄 Orchestrated automated PDF estimation generation, bulk record parsing, and notification dispatches through BullMQ queue clusters.
    > ⚡ Maximized single-node compute resources by decoupling long-running processes via the **Node.js Cluster Module**.

`Node.js` `Express` `TypeScript` `Next.js` `Prisma` `Supabase` `Redis` `BullMQ`

---

## 💼 Professional Experience

### **Full Stack Developer** | Station-S Technology
*FactOps Private Limited & ZDotApps Private Limited*  
**November 2024 — Present**
*   Architected enterprise-grade multi-tenant web systems, custom single sign-on mechanisms, and critical security systems across corporate initiatives.
*   Designed highly concurrent event processing architecture using asynchronous worker pools, cutting critical platform infrastructure costs.
*   Configured robust continuous integration/continuous deployment (CI/CD) patterns ensuring frictionless containerized distribution.

### **Full Stack Engineering Intern** | SocialTek Solutions
**October 2022 — July 2024**
*   Completed an intensive full-stack engineering track, transitioning a foundational mechanical engineering background into robust systems programming.
*   Built and maintained over 15 distinct functional micro-architectures as reference baselines covering React, Spring Boot, and enterprise SQL databases.
*   Guided technical alignment initiatives, evaluating system architecture mechanics and reviewing software engineering fundamentals for over 50 internal technical associates.

---

## 📊 Technical Performance & Metrics

<table border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td width="50%" valign="top">
      <img src="https://github-readme-stats.vercel.app/api?username=hemanthdorepalli&show_icons=true&theme=neutral&include_all_commits=true&count_private=true&hide_border=true&show_icons=true&icon_color=0052CC&title_color=0052CC" width="100%" alt="Hemanth's GitHub Metrics"/>
    </td>
    <td width="50%" valign="top">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hemanthdorepalli&layout=compact&theme=neutral&hide_border=true&title_color=0052CC" width="100%" alt="Hemanth's Language Distribution"/>
    </td>
  </tr>
</table>

---

## 🎓 Academic Credentials

*   **Bachelor of Technology (B.Tech.) in Mechanical Engineering**  
    *Jawaharlal Nehru Technological University, Kakinada (JNTUK)* | **2018 — 2022**  
    *   **Cumulative GPA:** 8.38 / 10.0  
    *   **Core Systems Competencies:** Data Structures & Algorithms, Object-Oriented Programming (OOP), Computational Logic.

---

## 🤝 Get In Touch

I am open to discuss professional opportunities regarding **Senior Backend Developer**, **Full Stack Product Engineer**, or **Systems Architect** roles specializing in highly secure environments, SaaS systems, industrial IoT, or advanced AI platforms.

*   **Professional Identity:** [Connect on LinkedIn](https://www.linkedin.com/in/hemanth-3b7a26295/)
*   **Interactive Demonstrations:** [Explore Portfolio](https://hemanth-labs.netlify.app/)
*   **Direct Communications:** [hemanthd0916@gmail.com](mailto:hemanthd0916@gmail.com)
