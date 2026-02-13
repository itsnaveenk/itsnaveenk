# Naveen Kumar
### Backend Engineer | Distributed Systems & AI-Native Search
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/itsnaveenk)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail)](mailto:connect.naveenk@gmail.com)
[![Portfolio](https://img.shields.io/badge/Website-Elevencoder.com-10B981?style=for-the-badge&logo=firefox)](https://elevencoder.com)

---

## 🚀 Engineering Philosophy
I build **fault-tolerant, high-throughput backend systems**. My expertise lies in architecting microservices that scale, optimizing database performance for millions of records, and integrating Large Language Models (LLMs) into production workflows with strict latency SLAs.

**Current Focus:** Java Concurrency, Event-Driven Architectures (Kafka), and Vector Search Optimization.

---

## ⚡ High-Impact Engineering (Production Metrics)

| Metric | Context | Impact |
| :--- | :--- | :--- |
| **2M+ Users** | Shorts/Video Platform | [cite_start]Served high-concurrency traffic for a Reels-style application [cite: 10, 15] |
| **600K+ Queries/Wk** | Global Search API | [cite_start]Reduced latency by **40%** via Elasticsearch optimization [cite: 17] |
| **1.5M+ Vectors** | Hybrid Search Engine | [cite_start]Orchestrated ingestion pipelines for large-scale e-commerce data [cite: 41] |
| **~80% Time Saved** | Internal Tooling | [cite_start]Automated reporting & license generation workflows [cite: 25] |

---

## 🛠 Tech Stack

**Core Infrastructure**
* **Languages:** Java (Core/Advanced), Python, SQL
* **Frameworks:** Spring Boot (MVC, Security, Data), FastAPI
* **Databases:** PostgreSQL, MongoDB, Redis (Caching & Pub/Sub), Elasticsearch
* **Messaging:** Apache Kafka, Redis Streams

**DevOps & Cloud**
* **AWS:** EC2, S3, CloudFront, Lambda, SQS
* **Tooling:** Docker, Kubernetes (Basic), CI/CD (GitHub Actions), Prometheus/Grafana

**AI & Information Retrieval**
* **Search:** Hybrid Retrieval (BM25 + kNN), RAG Pipelines, Vector Embeddings
* **LLMs:** OpenAI API, LangChain concepts, Prompt Engineering Guardrails

---

## 📂 Featured Case Studies

### 1. Enterprise-Grade Hybrid Search & RAG System
**Architecture:** Spring Boot • Elasticsearch • OpenAI • Redis

Designed a production-ready search engine to solve the "zero-result" problem in e-commerce.
* **Challenge:** Standard keyword search failed on vague user queries (e.g., "gifts for summer"), leading to drop-offs.
* **Solution:** Implemented a **Hybrid Search Strategy** combining BM25 (lexical) and kNN (semantic) scores. Built a "Change-Detection" ingestion pipeline to prevent re-embedding unchanged data.
* [cite_start]**Key Engineering Win:** Optimized token usage and API costs by **caching embeddings** and strictly formatting LLM outputs to JSON[cite: 43, 44].

### 2. High-Concurrency Video Feed Architecture
**Architecture:** Microservices • Kafka • CDN • MySQL

Engineered the backend for a high-traffic "Shorts" video platform.
* **Challenge:** serving video metadata and user interaction states (likes, follows) with sub-100ms latency under load.
* **Solution:**
    * [cite_start]Decoupled write-heavy operations (analytics, notifications) using **Apache Kafka**[cite: 18].
    * [cite_start]Implemented **Read-Through/Write-Behind caching** with Redis to protect the primary DB[cite: 20].
    * [cite_start]Integrated **UPI AutoPay** for recurring subscription monetization[cite: 16].

### 3. CodeArena - Distributed Code Execution Platform
**Architecture:** React • Spring Boot • Docker • Redis Streams

A competitive programming platform capable of executing untrusted user code securely.
* **Sandboxing:** Utilized ephemeral Docker containers to isolate user code execution.
* **Async Processing:** Managed submission queues via Redis Streams to handle burst traffic during contests.

---

## 💼 Professional Experience

**SDE 1 (Java Developer) | Adda247**
*Oct 2024 – Present*
* [cite_start]Architected the **GlobalSearch API**, unifying search across eBooks, Videos, and Quizzes, serving **600K+ queries/week**[cite: 17].
* [cite_start]Migrated 700K+ legacy records to Elasticsearch using Logstash ETL pipelines with near real-time synchronization[cite: 23].
* [cite_start]Reduced API error rates by implementing comprehensive unit testing and logging via Kibana[cite: 26].

---

<div align="center">
  <sub><em>"Talk is cheap. Show me the code." — Linus Torvalds</em></sub>
</div>
