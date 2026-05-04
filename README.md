<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1a2e,100:f73626&height=200&section=header&text=Nishchal%20Vekariya&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=I%20don't%20just%20write%20code%20%E2%80%94%20I%20ship%20solutions%20that%20scale.&descSize=16&descAlignY=58&descColor=c9d1d9" width="100%" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nishchal-vekariya/)
[![Portfolio](https://img.shields.io/badge/Portfolio-f73626?style=for-the-badge&logo=vercel&logoColor=white)](https://nishchalvekariya.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nishchalvekariya0@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-1a1a2e?style=for-the-badge&logo=readthedocs&logoColor=white)](https://nishchalvekariya.com)

</div>

---

## 🎯 Who I Am

```
M.S. Computer Engineering @ UT Dallas  |  Full-Stack · AI/ML · Distributed Systems
```

I build **production-grade systems** that solve real problems — not just demos that break under load. Every project I ship is engineered with scale, observability, and business impact in mind.

> **If you're a recruiter**: scroll to [Featured Projects](#-featured-projects) to see exactly what I build and the problems I solve.

---

## 💼 What I'm Ready For

| Role | What I Bring |
|------|-------------|
| **Software Engineer (Backend/Full-Stack)** | Event-driven systems, microservices, REST/GraphQL APIs, distributed architectures |
| **AI/ML Engineer** | LLM pipelines, RAG systems, NLP, production AI feature integration |
| **Data Engineer** | High-throughput ingestion (10K+ events/sec), ETL pipelines, real-time analytics |
| **Platform/Infrastructure Engineer** | Docker, Kubernetes, AWS, observability with OpenTelemetry, CI/CD |

---

## 🚀 Featured Projects

> **5 production-ready systems. Each one solving a real problem.**

---

### 🧠 [AlphaMind](https://github.com/Nishchal45/alphamind) — Agentic Equity Research Platform
**Problem solved:** Equity research is slow, hallucination-prone, and rarely backed by primary-source filings — analysts waste days on what AI can ground in seconds.

- **Multi-agent system** built on **LangGraph** — planner, retriever, analyst, and critic agents collaborate to produce institutional-grade research reports
- **Hybrid RAG** over `pgvector` — combines dense embeddings with BM25 reranking; every claim is grounded in **SEC EDGAR** filings (10-K, 10-Q, 8-K)
- **LoRA-fine-tuned SLM** for cost-efficient inference on financial reasoning tasks (vs. raw GPT-4 calls)
- **Backtest-validated** investment theses — outputs aren't just summaries, they're testable signals
- FastAPI service layer with async pipelines for parallel filing ingestion

`Python` `LangGraph` `pgvector` `FastAPI` `LoRA` `SEC EDGAR` `RAG`

---

### 📱 [SpendLense AI](https://github.com/Nishchal45/spendlense-ai) — Intelligent Receipt Scanner
**Problem solved:** Manual expense tracking is tedious; OCR alone fails on messy real-world receipts.

- Uses **GPT-4 Vision** to extract line items, totals, dates, and merchant names from any receipt photo
- Automatic category classification and spend trend analytics
- React Native mobile app with offline capture + async sync
- Node.js backend with structured storage and export to CSV/PDF

`GPT-4V` `React Native` `Node.js` `OCR` `PostgreSQL` `AWS S3`

---

### 🤖 [QueryMate AI](https://github.com/Nishchal45/querymate-ai) — Natural Language → SQL Engine
**Problem solved:** Non-technical teams waste analyst hours translating business questions into SQL.

- Converts plain English to production-safe SQL with **92% accuracy** on complex queries
- Schema-aware context injection — handles JOINs, aggregates, CTEs, and window functions
- FastAPI backend with query validation layer to prevent destructive operations
- Supports PostgreSQL, MySQL; extensible to any SQL dialect

`Python` `LLM` `FastAPI` `PostgreSQL` `LangChain` `React`

---

### ⚡ [OrderFlow](https://github.com/Nishchal45/orderflow) — Distributed Order Processing System
**Problem solved:** Monolithic order systems fail under high concurrency and partial failures cascade.

- Built event-driven microservices with **Saga orchestration** for distributed transaction management
- Guarantees **exactly-once delivery** via Kafka with dead-letter queue handling
- Full observability stack — **OpenTelemetry + distributed tracing** across services
- Containerized with Docker Compose; production-ready with gRPC inter-service comms

`Kafka` `gRPC` `Docker` `OpenTelemetry` `PostgreSQL` `Go`

---

### 📊 [PulseBoard](https://github.com/Nishchal45/pulseboard) — Real-Time Analytics Engine
**Problem solved:** Most analytics dashboards are stale — businesses need live insight at scale.

- Ingests and processes **10,000+ events/second** with sub-100ms query response time
- ClickHouse columnar storage for OLAP workloads; WebSocket push for live UI updates
- Aggregation pipelines with time-series rollups and custom metric definitions
- React dashboard with real-time charts, zero-polling architecture

`Go` `ClickHouse` `WebSocket` `React` `Redis` `Docker`

---

## 🧰 Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & APIs**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Data & Streaming**

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Nishchal45&show_icons=true&hide_border=true&bg_color=0a0a0a&title_color=f73626&icon_color=f73626&text_color=c9d1d9" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=Nishchal45&show_icons=true&hide_border=true&bg_color=ffffff&title_color=f73626&icon_color=f73626&text_color=4e4e4e" />
  <img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=Nishchal45&show_icons=true&hide_border=true&bg_color=ffffff&title_color=f73626&icon_color=f73626&text_color=4e4e4e" height="165" />
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Nishchal45&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=f73626&text_color=c9d1d9" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Nishchal45&layout=compact&hide_border=true&bg_color=ffffff&title_color=f73626&text_color=4e4e4e" />
  <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nishchal45&layout=compact&hide_border=true&bg_color=ffffff&title_color=f73626&text_color=4e4e4e" height="165" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=Nishchal45&hide_border=true&background=0a0a0a&ring=f73626&fire=f73626&currStreakLabel=f73626&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=666666" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=Nishchal45&hide_border=true&background=ffffff&ring=f73626&fire=f73626&currStreakLabel=f73626&sideLabels=1e1e1e&currStreakNum=1e1e1e&sideNums=1e1e1e&dates=4e4e4e" />
  <img alt="GitHub Streak" src="https://github-readme-streak-stats.herokuapp.com/?user=Nishchal45&hide_border=true&background=ffffff&ring=f73626&fire=f73626&currStreakLabel=f73626&sideLabels=1e1e1e&currStreakNum=1e1e1e&sideNums=1e1e1e&dates=4e4e4e" height="165" />
</picture>

</div>

---

<div align="center">

**Open to full-time roles starting Summer/Fall 2025**

*Building things that matter. Let's connect.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f73626,50:1a1a2e,100:0a0a0a&height=120&section=footer" width="100%" />

</div>
