

# Armand Junior Dongmo Notue

**GenAI / LLM Engineer · ML Engineer · Data Scientist**
Arlington, TX (DFW) ·  no sponsorship needed

I build and ship production LLM systems end-to-end: RAG pipelines with eval-driven quality loops, multi-agent platforms, and real-time inference APIs. 18 months of RLHF/SFT data work on frontier LLMs at Outlier (Scale AI). MS Data Science.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

---

## 🚀 Pinned projects

### [IntelliCast AI](https://intellicast.news) — news-to-podcast GenAI platform
Production app converting breaking news into dual-voice podcasts (Conversational + Debate mode). LLaMA-3-70B for script generation, Cartesia TTS for low-latency speech. 6 REST endpoints behind FastAPI with async job queue, SQLite inference cache, and Grafana p50/p95/p99 latency + cost dashboard.
`LLaMA-3-70B` `Cartesia TTS` `FastAPI` `React + TypeScript` `Docker` `Grafana` · **[live →](https://intellicast.news)**

### RAG Document Intelligence API — production retrieval service
Async PDF/HTML ingestion, BGE-reranker-v2 on top of dense retrieval, SSE streaming on FastAPI + LangChain + ChromaDB. RAGAS evals for context recall, faithfulness, and answer relevancy.
**Recall@5: 0.71 → 0.86 · MRR: 0.58 → 0.74** on a held-out 200-query eval set. Deployed on AWS EC2 with persistent vector-store volume.
`LangChain` `ChromaDB` `BGE-reranker-v2` `RAGAS` `sentence-transformers` `Docker` `AWS EC2`

### Atlas — autonomous multi-agent research platform
LangGraph + Claude Sonnet 4.5 (GPT-4o fallback) multi-agent system: parallelized researcher agents, critic-driven self-correction loop, live agent-graph visualization streamed over SSE. Self-hosted Langfuse tracks every LLM call (cost, latency, token usage, trace replay). 50-trace regression eval suite with a CI gate that blocks merges on >2% category regression.
`LangGraph` `Langfuse` `Next.js 15` `React Flow` `pgvector` `Redis` `Celery` `MCP` `AWS EC2`

### Real-time fraud detection — ensemble deep learning
PyTorch Autoencoder + Isolation Forest + XGBoost over 44 engineered features on 280K transactions. **ROC-AUC 0.9834 · Recall 85.71% at 0.16% FPR · p99 inference latency 86 ms.** Focal loss + threshold calibration for class imbalance. SHAP explainability surfaced via FastAPI scoring endpoint.
`PyTorch` `scikit-learn` `XGBoost` `SHAP` `FastAPI` `Docker`

---

## 📬 Get in touch

[🌐 intellicast.news](https://intellicast.news) · [💼 LinkedIn](https://linkedin.com/in/notue250) · [✉️ notuearmand250@gmail.com](mailto:notuearmand250@gmail.com)
