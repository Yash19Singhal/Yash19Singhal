# Yash Singhal

**Backend · Systems · GenAI** — building production systems that ship fast and hold under load.

Systems Engineer at **Infosys** · ex-**Reliance Jio** · B.Tech CSE, VIT Vellore `8.11 CGPA`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-yashsinghal1909-7B61FF?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashsinghal1909/)
[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio--6kez.vercel.app-7B61FF?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-6kez.vercel.app/)
[![Email](https://img.shields.io/badge/Email-singhalyash340@gmail.com-7B61FF?style=flat-square&logo=gmail&logoColor=white)](mailto:singhalyash340@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-yashsinghal1909-7B61FF?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/Yash19Singhal/)

---

## How my stack connects

```
  [ Telecom APIs / Raw Data ]
           │
           ▼
  ┌─────────────────────────┐
  │  Multi-Agent Orchestration  │  ← Langflow · 4 agent types · branching logic
  │  RAG · OpenAPI Parsing  │
  └─────────┬───────────────┘
            │ grounded answers
            ▼
  ┌──────────────────────┐        ┌──────────────────────┐
  │  LLM Layer           │        │  Vector Store         │
  │  Qwen · Mistral      │◄──────►│  HNSW · KD-Tree       │
  │  Prompt Engineering  │        │  C++17 · O(log N)     │
  └──────────────────────┘        └──────────────────────┘
            │
            ▼
  ┌──────────────────────┐        ┌──────────────────────┐
  │  Backend APIs        │        │  Network Layer        │
  │  Node.js · Flask     │        │  DPI Engine · C++17   │
  │  PostgreSQL · Docker │        │  100K+ pkt/run · TLS  │
  └──────────────────────┘        └──────────────────────┘
            │
            ▼
  [ Langfuse Observability · Prompt Versioning · Latency Tracking ]
```

---

## Experience

**Systems Engineer** — Infosys *(Aug 2026 – Present)*
> Distributed backend systems, AI automation pipelines, Python · C++ · GenAI

**Software Engineer Intern** — Reliance Jio *(Jun 2025 – Jul 2025)*
- `98% ↓` developer query resolution time (2–3 hrs → <1 min) via multi-agent GenAI assistant
- `40% faster` API onboarding across 200+ Telecom APIs — RAG + OpenAPI parsing + code gen pipeline
- `35% ↑` system throughput via fault-tolerant Langflow orchestration across 4 agent types
- `25% ↓` LLM latency — benchmarked Qwen 2.5 vs. Qwen 3.14 on 20+ live production queries
- `50% ↓` troubleshooting effort — Langfuse observability for real-time tracing & prompt versioning

`Python` `Langflow` `Langfuse` `RAG` `Ollama` `Qwen/Mistral` `PostgreSQL` `Docker`

---

## Projects

**[OwnAI — Vector Database Engine](https://github.com/Yash19Singhal/OwnAI-Vector-Database-Engine)** `C++17`

Vector DB from scratch — HNSW, KD-Tree, and Brute Force search over 16D semantic vectors. Full RAG pipeline (Ollama chunking → HNSW retrieval → LLM answers) + 7 REST endpoints via custom C++ HTTP server + real-time 2D PCA visualization of 768D embeddings.

```
O(log N) similarity search · Zero external DB dependencies · Sub-ms queries
```

---

**[Deep Packet Inspection Engine](https://github.com/Yash19Singhal/Deep-Packet-Inspection-Engine)** `C++17`

High-throughput DPI engine parsing full network stacks (Ethernet → IP → TCP/UDP). Extracts TLS SNI fields for encrypted traffic classification. 4-stage multi-threaded pipeline with 5-tuple flow hashing; configurable blocking rules across 10+ app types.

```
100K+ packets/run · O(1) per-flow lookup · Zero lock contention
```

---

**[Personal Finance Tracker](https://fj-be-r2-yashsinghal-vitvellore-h9q3.onrender.com/)** `Node.js · PostgreSQL`

Production RESTful backend — JWT + Google OAuth 2.0, Z-score anomaly detection across 30+ days of financial data, AI spending summaries via Gemini API, automated budget alerts via Nodemailer.

```
10+ secured endpoints · 50+ parameterized queries · 80%+ budget alert automation
```

---

## Stack

```
Languages     C · C++ · Python · JavaScript · SQL
Backend       Node.js · Express.js · Flask · REST APIs · PostgreSQL · Docker
AI/GenAI      RAG Pipelines · Multi-Agent Systems · LLMs (Qwen · Mistral · Gemini)
              Prompt Engineering · Langflow · Langfuse · Vector Stores
Systems       TCP/IP · TLS/SNI · PCAP · Multithreading · CMake · Linux
Cloud         AWS (EC2 · S3) · Docker · Git
```

---

## Certifications

- **Generative AI with Large Language Models** — DeepLearning.AI × Coursera
- **HTML, CSS, JavaScript for Web Developers** — Johns Hopkins × Coursera

---

*Open to Backend / Systems / GenAI engineering roles · singhalyash340@gmail.com*
