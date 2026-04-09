# 👋 Hi, I'm Rushikesh Bawaskar

🚀 **Software Engineer | Agentic AI Systems | Backend & Infra**

Building **production-grade Agentic AI systems (RAG, MCP, Tool Calling)** with async Python at scale.

Google Certified **Professional Cloud Architect** & **Associate Cloud Engineer** with 2+ years of experience designing distributed systems, AI platforms, and real-time data pipelines.


[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/rushibawaskar) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:theofficialrushi@gmail.com) [![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?logo=leetcode&logoColor=white)](https://leetcode.com/Rushi_Bawaskar)

---

## 🚀 What I Build

### 🧠 Enterprise AI Agent Platform

An extensible platform where organizations deploy **stateful AI agents** with dynamic tool access, RBAC, and long-running memory.

#### 🔹 Key Highlights
- Built on **Letta (stateful agents)** with dynamic personas & toolsets
- Designed **runtime tool discovery system (MCP-compatible)** — no redeployments required
- Implemented **secure IAM layer (OAuth2 + PKCE + RBAC)** using Zitadel & Azure AD
- Developed **Redis-based streaming architecture** ensuring **zero message loss**
- Built **RAG pipeline (Docling + pgvector)** with hybrid search (30% keyword / 70% vector)
- Integrated **Vision LLMs** for chart/image understanding
- Full observability using **OpenTelemetry → Loki + Tempo + Prometheus**

#### 📊 Key Achievements
- ⚡ **50% faster document ingestion**
- 🔍 Hybrid search improved retrieval relevance significantly
- 🛡️ Zero message loss even during client disconnects
- 🔄 Eliminated redeployments via dynamic tool registration

#### 🧠 Architecture Overview

  User → Middleware (FastAPI)
→ Agent (Letta)
→ Tool Server (FastAPI)
→ MCP Servers / External APIs
→ Redis Stream (async response handling)
→ UI (SSE streaming)
 
#### ⚙️ Tech Stack
`Python` `Quart` `FastAPI` `Letta` `MCP` `PostgreSQL (pgvector)`  
`Redis` `Celery` `Docker` `GCP` `OpenTelemetry`

### 📊 AI Sports Analytics System

A Generative AI platform where users ask questions in natural language and get **real-time analytics & charts from BigQuery**.

#### 🔹 Key Highlights
- Built **Text-to-SQL agents** using Google Agent ADK + Gemini
- Designed **MCP-based tool calling system** for real-time BigQuery access
- Implemented **self-correcting SQL generation loop** (validation + retry)
- Developed **secure Python execution sandbox (Docker-based)**
- Generated **interactive Plotly charts via SSE streaming**
- Built **multimodal RAG pipeline** (text + charts + screenshots)

#### 📊 Key Achievements
- ⚡ Reduced response latency from **30s → 3s (90% improvement)**
- 🎯 Achieved **95%+ SQL query accuracy**
- 🔐 Enforced **dataset-level RBAC** (Coaches vs Data Scientists)

#### 🧠 Architecture Overview


User Query → Agent (ADK + Gemini)
→ Text-to-SQL Engine
→ Query Validator + Retry Loop
→ BigQuery
→ Python Sandbox (Chart Generation)
→ SSE → UI (Real-time charts)


#### ⚙️ Tech Stack
`Google Agent ADK` `Gemini` `FastAPI` `BigQuery`  
`Docker Sandbox` `Plotly` `SSE` `OpenTelemetry`

---


## 🧠 Core Expertise

- **Agentic AI Systems** (Letta, Agent ADK, MCP)
- **RAG Pipelines** (Hybrid Search, Multimodal Retrieval)
- **Async Python Backends** (FastAPI, Quart, SQLAlchemy)
- **Distributed Systems** (Streaming, Queues, SSE)
- **System Design** (Tool Discovery, RBAC, Observability)
- **Cloud & Infra** (GCP, Docker, CI/CD)

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frameworks**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

**AI & Agents**

![Letta](https://img.shields.io/badge/Letta-5A2D82?style=for-the-badge&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-FF6F00?style=for-the-badge&logoColor=white)
![Google Agent ADK](https://img.shields.io/badge/Agent_ADK-4285F4?style=for-the-badge&logo=google&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(pgvector)-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)

**Infrastructure & Observability**

![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 🏅 Certifications

- [**Google Professional Cloud Architect**](https://www.credly.com/badges/e481bac7-4115-4ee5-abbb-0a16985e4033/public_url) — Jan 2026
- [**Google Associate Cloud Engineer**](https://www.credly.com/badges/f9cd8943-6e43-41e5-869b-2f799cdffc8b/linked_in?t=ss4uqd) — Feb 2025

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=RushikeshBawaskar&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=RushikeshBawaskar&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=RushikeshBawaskar&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=RushikeshBawaskar&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=RushikeshBawaskar&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=RushikeshBawaskar&icon=0&color=0)](https://visitcount.itsvg.in)
