# Suyash Singh

CS (Data Science) Student @ MIT Bengaluru · Published AI Researcher (ICDDS 2025) · AI/ML & Backend Engineering

Building production-grade AI systems and backend infrastructure — focused on LLM pipelines, fault-tolerant distributed systems, ML-driven AIOps, and infrastructure tuned for ultra-low latency, scale, and high availability.

## Featured Projects

**Semantic LLM Gateway & Routing Proxy** — Production-grade OpenAI-compatible router & cache for Groq LLMs
Semantic caching with Qdrant + Hugging Face Sentence-Transformers (sub-50ms cache-hit latency), cost-aware routing between Llama 3.1 8B and Llama 3.3 70B based on prompt complexity, and an Ollama-based fallback circuit breaker for upstream rate-limits or downtime. Ships with a real-time observability dashboard tracking cost savings and latency.
`FastAPI` `Qdrant` `Hugging Face` `Groq` `Ollama` `Redis`

**AIOps Auto-Remediation Platform (The Watcher)** — Self-healing infra modeled on IRCTC-scale booking systems
11+ microservices on Kubernetes validated under 5,000+ RPS, an edge-deployed ONNX anomaly detector via WebAssembly (sub-15s failure detection), and NATS-driven self-healing with zero manual intervention.
`Python` `FastAPI` `Kubernetes` `ONNX` `Prometheus` `NATS` `KEDA`

[Vidhived.ai](https://github.com/anothercodingguy/vidhived-ai) — AI-powered legal document analyzer
OCR → clause extraction → LLM risk classification, fully decoupled with BullMQ. Plain-English output for non-lawyers.
`React` `Next.js` `Python` `Flask` `Groq LLMs` `Docker` ★ v1.0.0 released

[KnowledgeBridge](https://github.com/anothercodingguy/KnowledgeBridge) — Intelligent knowledge management with semantic search
Natural language Q&A over technical documents using Haystack pipelines and dense vector retrieval.
`Python` `Haystack` `Streamlit` `Vector Search` `RAG`

[JanSahayak (hackblr)](https://github.com/anothercodingguy/hackblr) — Multilingual welfare benefits navigator
Voice-first (Hindi/Kannada/English) government scheme navigator with Qdrant RAG and Vapi voice integration.
`Next.js` `TypeScript` `Qdrant` `RAG` `Voice AI`

**Self-Erasing Neural Networks (SENNs)** — Published at ICDDS 2025
Co-authored peer-reviewed publication on GDPR-compliant machine unlearning frameworks; built pipelines to visualize weight-magnitude shifts and per-class accuracy trade-offs from gradient-based erasure.
`Python` `PyTorch` · DOI: [link to be added upon publication]

## Experience

**AI Intern — Stealth Startup** · Dec 2025 – May 2026 · Bengaluru, India
Built backend systems for a Mistral-powered conversational AI platform with memory-augmented agentic workflows and multi-turn dialogue. Integrated NLP-based entity/intent extraction and designed REST APIs and AWS-based inference services handling conversation state, routing, and session management at scale.

**R&D Intern — IEEE Computer Society, Bangalore Chapter** · Apr 2025 – Sep 2025
Authored technical workshop documentation on AI and systems topics for 100+ students across multiple cohorts; distilled recent research papers into beginner-accessible write-ups used as official onboarding material.

## Leadership

**Project Head — Manipal Bengaluru Open-Source Community (MBOSC)** · 2024 – 2025
Led code reviews and technical workshops for 200+ student developers; mentored contributors on system design and Git workflows.

**Project Head — Electrovista (Electronics Club)** · 2025
Managed end-to-end hackathon execution and cross-team engineering coordination across technical projects.

## Writing & Research

- ICDDS 2025 — Machine Unlearning: Gradient-based approaches for selective knowledge removal in neural networks
- Building blog post: How I built Vidhived.ai — a legal AI from scratch using Groq, PyMuPDF, and Next.js (coming soon on Medium)

## Currently Building

**LLM Evaluation Pipeline** — An open-source framework combining Databricks, LangSmith-style evals, and a RAG system with a Knowledge Graph backend. Filling the data engineering gap in AI tooling.
`Python` `Databricks` `Neo4j` `LangChain` `FastAPI` `Grafana`

## Skills

**Languages:** TypeScript · JavaScript (ES6+) · Python · C++ · Java · SQL
**AI / ML:** PyTorch · LLM Pipelines · RAG · Vector Databases (Qdrant, ChromaDB) · Machine Unlearning · Groq · Haystack
**Backend:** Node.js · Express.js · FastAPI · Flask · REST APIs · Microservices · BullMQ
**Frontend:** React.js · Next.js · Tailwind CSS
**Infra:** Docker · Kubernetes · Prometheus · Grafana · GCP · AWS
**Databases:** PostgreSQL · MongoDB · Redis · SQLite
**Data Engineering:** Databricks · Neo4j · Vector Search

## Education

**B.Tech, Computer Science Engineering (Data Science)** — Manipal Institute of Technology, Bengaluru
2023 – 2027 · CGPA: 8.51/10

Reach me: [suyashs787@gmail.com](mailto:suyashs787@gmail.com) · Bengaluru, Karnataka, India
