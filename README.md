**Senior Software Engineer — AI & ML Systems**

Senior software engineer with 10+ years building production AI/ML systems for creative software, automotive SaaS, and enterprise networking. I work on production LLM agent systems, multimodal generative AI pipelines, and the evaluation frameworks that make them safe to ship.

---

## What I work on

- **Production LLM agents** — LangGraph, ReAct, tool-using agents, hierarchical state machines, stateful multi-step workflows, short-term / semantic / episodic memory
- **Multimodal generative AI** — Anthropic Claude API (tool use, prompt caching, extended thinking), Adobe Firefly Services, Stable Diffusion, CLIP, hybrid vector search
- **Evaluation & safety** — prompt-injection defense, red-team eval suites, brand-safety and IP-leakage classifiers, NSFW filtering, regression scorecards, structured outputs
- **Retrieval** — pgvector, Pinecone, Milvus, Chroma, Weaviate; hybrid + semantic chunking
- **Knowledge graphs** — Neo4j, AWS Neptune, Google Spanner, GraphRAG, schema evolution, supernode mitigation
- **Data & infra** — Kafka, Spark Structured Streaming, Airflow, dbt, Snowflake, ClickHouse, PostgreSQL, Redis
- **Cloud & MLOps** — AWS (SageMaker, Lambda, EKS), Azure (AKS, OpenAI, Cosmos DB), GCP (GKE, Vertex AI), Docker, Kubernetes, Terraform, MLflow

Languages: Python, TypeScript, JavaScript, SQL, Go, C++, Cypher.

---

## Selected impact

- **+28%** end-to-end AI task completion at Adobe by replacing single-prompt LLM calls with a LangGraph agent runtime
- **+22%** top-3 multimodal retrieval relevance across enterprise creative-asset libraries via hybrid CLIP + text vector index
- Drove prompt-injection success on red-team suites to **near zero** with an evaluation + guardrails framework integrated into CI
- Ingestion pipelines processing **tens of millions** of unstructured multimodal assets for vector search and Firefly Custom Model training
- Architected a knowledge graph spanning **1M+ entities**, designed to scale to **10M+** at sub-100ms traversal

---

## Featured side work

**GraphRAG Knowledge Graph for 1M+ Listings (designed for 10M+)**
Production-scale alternative to traditional RAG for queries that need both structured filters and semantic similarity. Neo4j Aura, AWS Neptune Serverless, Google Spanner, pgvector, Redis. Schema strategy distinguishing nodes from properties to avoid supernode bottlenecks. Cost framework comparing Neptune Serverless vs. Neo4j Aura vs. self-hosted EKS/GKE for read-heavy workloads with bursty overnight ingestion.

**Multi-Agent Local AI Workstation with Claude + MCP**
Local multi-agent system with role-specialized Claude agents for research, writing, browser automation, and asset management — coordinated through natural-language commands. Custom MCP servers wrapping internal APIs and SaaS tools, persistent cross-session memory, secure credential management. A testbed for the same agent patterns I ship at Adobe.

**Edge ML RL for Real-Time Motor Control**
R&D study of how far reinforcement learning can be pushed under hard real-time embedded constraints. PPO/SAC agents as a supervisory neural controller for a 6H, 15kW industrial motor. SIL Digital Twin calibrated against 20kHz telemetry. Benchmarked MLP/LSTM/GRU against a hard 150 microsecond inference budget on STM32F405 at 168MHz, with INT8 PTQ thresholds and reward functions hardened against reward hacking under stall conditions.

