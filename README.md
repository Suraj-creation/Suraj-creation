# Suraj Kumar

**Founder & Architect — The Inevitable · Cortex Lab** | AI/ML Research · Multi-Agent Systems · Agentic RAG · Deep Learning · Full-Stack · MLOps · Edge AI

BTech Computer Science Engineering (4th Year) — Vidyashilp University, Bangalore, India · Based in Patna, Bihar

---

## What I'm Building

Two research-grade AI platforms with ambitions to disrupt education, healthcare, knowledge work, and the examined life itself.

### [Cortex Lab](https://github.com/Suraj-creation/Cortex-Lab) · [Live →](https://cortex-frontend-t53t.onrender.com/) · [Vision →](https://cortex-extends.vercel.app/)

A fully local, privacy-first **personal autonomous intelligence runtime** — your second mind. Not a chatbot. Not a wrapper around a cloud API. A system designed to know one person deeply over years and compound in value with every session.

**Architecture:**
- 5-plane hierarchical memory: P0 working context → P1 event plane (DuckDB + FAISS HNSW) → P2 atomic claim plane → P3 canonical wiki plane → P4 entity-relation knowledge graph (NetworkX)
- 17-agent orchestration runtime across three layers: L0 Master Orchestrator, L1 Runtime Orchestrator, L2 15 specialized domain agents (Timeline, Causal, Reflection, Planning, Arbitration, Academic, Journaling, Wellbeing, Cognitive Patterns, Decision Log, Emotional, Behavioral, Social, Goal, Meta-Learning) + always-on Wiki Agent + Presence Agent
- 5-tier intelligent retrieval routing: T0 cache (50ms) → T1 wiki-fast (200ms) → T2 standard RAG (1.5s) → T3 deep multi-agent (6s) → T4 frontier (20s)
- 3-layer quality assurance: CRAG + Self-RAG + FLARE active retrieval
- Base model: Google Gemma-4-E2B-it, fine-tuned via 15-stage progressive curriculum (QLoRA NF4 4-bit), 162,373 curated training examples across SFT, DPO, and ORPO stages
- Stage A complete: eval loss 0.6791, RAGAS Faithfulness 0.84 (0.23 above baseline)
- Full monorepo: backend (FastAPI/Python), frontend (Next.js 15/TypeScript), mobile, pi-mono (Raspberry Pi edge), infra, docs
- Apache 2.0 · 100% local · zero cloud dependency for inference

**10 Deep Applications:** Session Memory Forge · Life Chronicle · Deep Self Mirror · Presence Agent · Gap Intelligence System · Relationship Memory Engine · Life OS Dashboard · Dream Diary · Decision Oracle · Personal Knowledge Amplifier

**Sectors being disrupted:** Education → Mental Health → Research & Knowledge Work → Healthcare → Creativity → Organizational Intelligence → Spiritual Practice

---

### [The Inevitable](https://github.com/Suraj-creation/The-inevitable-)

A **Knowledge Operating System** — research-grade multi-agent AI platform whose singular purpose is not to teach, but to produce brilliant scientists, researchers, doctors, and engineers who generate original contributions to human knowledge.

Knowledge is not a list of topics. It is a **dynamic, living, multidisciplinary dependency graph** — every concept a node with prerequisite edges, successor edges, cross-domain bridge edges, depth layers (0–6), and a research frontier indicator. Learners don't progress through a curriculum. They navigate the graph.

**Core Architecture:**
- 18 specialized agents across four layers: Core Intelligence · Delivery · Research-Innovation · Life-Ecosystem
- All agents communicate through a shared Central Learner State — never through direct API calls
- Recursive Prerequisite Discovery: decomposes any concept to its zero-knowledge entry point, rebuilds understanding layer by layer
- Research-Grade Knowledge Pipeline: real-time positional awareness — exactly where each learner stands in the landscape of human knowledge, what prerequisites are verified or missing, where the research frontier lies
- Constraint Engine: personalizes graph navigation without modifying the underlying graph itself
- Knowledge backbone: sourced from top-tier research publications, elite curricula, peer-reviewed literature
- Designed to survive decades: modular, observable, reasoning-based, privacy-by-architecture

**Measure of success:** the number of human beings who, having navigated the knowledge graph through The Inevitable, produced a research contribution or breakthrough that would not have existed without them.

---

## Technical Profile

### Research & AI Systems
- Multi-agent system design with shared state orchestration (LangGraph, PydanticAI, custom orchestration runtimes)
- Retrieval-Augmented Generation: 9-layer Agentic RAG, 5-channel hybrid retrieval (dense BGE + sparse BM25/SPLADE + GraphRAG + temporal SQL + proposition indexing), RRF fusion, BGE cross-encoder reranking
- LLM fine-tuning: LoRA / QLoRA on Gemma-4-E2B-it, DeepSeek-R1, curriculum-structured 15-stage pipelines, 4-bit quantization for edge deployment
- Self-corrective generation: Self-RAG · CRAG · FLARE · Chain-of-Retrieval · RAPTOR hierarchical indexing
- Knowledge graph construction, belief evolution detection, long-horizon memory consolidation
- Computer vision: YOLOv8n object detection, ByteTrack multi-object tracking, CLAHE image enhancement
- STT/TTS pipeline integration, ambient capture architectures, wake-word systems
- RAGAS / RAGChecker evaluation frameworks
- Research synthesis from NeurIPS, ICLR, EMNLP, ACL (2023–2025)

### Deep Learning
- Transformer architectures (attention mechanisms, fine-tuning, PEFT)
- CNN architectures: ResNet-50, DenseNet-121, custom CNNs for medical imaging
- YOLO family for real-time detection, INT8/FP16 quantization for edge inference
- Cancer detection ML pipelines (carcinome project)
- TFLite / ONNX / TensorRT export for edge deployment
- Curriculum-based progressive fine-tuning (15-stage, catastrophic forgetting mitigation)

### Full-Stack Engineering
- Frontend: Next.js 15, React, TypeScript, TailwindCSS
- Backend: FastAPI (Python), Node.js, WebSocket, REST API design
- Auth & cloud: Google OAuth, Supabase, Google Drive integration
- Vector databases: Qdrant, FAISS (HNSW/IVF-PQ), DuckDB
- State management: Redis, PostgreSQL
- Semantic retrieval: LlamaIndex, PageIndex
- Deployment: Vercel, Render, Docker, systemd edge (Raspberry Pi 4, Jetson Nano)

### MLOps & Infrastructure
- CI/CD pipeline design, containerization, model versioning
- Production optimization: multi-level semantic caching, async parallel retrieval, vector quantization
- Observability: structured logging, agent decision tracing, SSE real-time frontend observability, performance benchmarking
- Edge AI deployment: ONNX/TFLite export, INT8 quantization, on-device inference
- Cloud: Google Cloud Platform, HuggingFace Hub
- MQTT-based event-driven systems for IoT/edge

---

## Selected Projects

| Project | Domain | Stack | Status |
|---------|--------|-------|--------|
| [Cortex-Lab](https://github.com/Suraj-creation/Cortex-Lab) | Personal AI · Agentic RAG · 5-plane memory | TypeScript · Python · Next.js · FastAPI · FAISS · DuckDB · Gemma-4 QLoRA | 🟢 Live — Active |
| [The-inevitable-](https://github.com/Suraj-creation/The-inevitable-) | Knowledge OS · 18-agent EdTech | Python · LangGraph · Multi-agent | 🔵 In Progress |
| [CrossSafe-EdgeAI](https://github.com/Suraj-creation/CrossSafe-EdgeAI) | Edge AI · Pedestrian Safety | YOLOv8n · ByteTrack · PaddleOCR · TFLite · TensorRT · MQTT | 🟢 Complete |
| [Reinforced-Cortex_Lab](https://github.com/Suraj-creation/Reinforced-Cortex_Lab) | Reinforcement Learning on Cortex | TypeScript | 🔵 Research |
| [carcinome](https://github.com/Suraj-creation/carcinome) | Medical AI · Cancer Detection | Python · CNN · ResNet-50 · DenseNet-121 | 🟢 Deployed |
| [OpenMAIC](https://github.com/Suraj-creation/OpenMAIC) | Multi-Agent Classroom | TypeScript (forked THU-MAIC) | 🟢 Extended |
| [Robothon-S0-101](https://github.com/Suraj-creation/Robothon-S0-101) | Robotics · Automation | Shell | 🟢 Complete |
| [Innerlog](https://github.com/Suraj-creation/Innerlog) | Personal journaling PWA | HTML | 🟢 Live |

---

## Deployed Production

- **[cortex-extends.vercel.app](https://cortex-extends.vercel.app/)** — Cortex Lab marketing & vision site (Core.OS Runtime)
- **[cortex-frontend-t53t.onrender.com](https://cortex-frontend-t53t.onrender.com/)** — Cortex Lab AI chat interface (Eva memory OS)
- **[fintech-sigma-nine.vercel.app](https://fintech-sigma-nine.vercel.app)** — Fintech platform
- **[carcinome-ten.vercel.app](https://carcinome-ten.vercel.app)** — Cancer detection AI
- **[shabbeer-basha.vercel.app](https://shabbeer-basha.vercel.app)** — Deep Learning course
- **[vidyashilp-university-shabbeer-dl.vercel.app](https://vidyashilp-university-shabbeer-dl.vercel.app)** — University DL curriculum

---

## The Disruption Thesis

Every major AI company is building a better general-purpose assistant. That is not the work.

The work is what happens when AI genuinely knows one person deeply over years (Cortex Lab) — and what happens when AI can take any mind from zero to original research contribution (The Inevitable).

The sectors being entered: **Education · Mental Health · Research & Knowledge Work · Healthcare · Creative Practice · Organizational Intelligence · Spiritual Practice & Self-Examination**.

The architectural innovations that make this different:
- **Compounding over time** — no AI system currently compounds personal knowledge over years. Cortex Lab is the first designed not to reset.
- **Hierarchical memory with wiki-quality canonical knowledge** — gets more precise with every session, not noisier.
- **Intelligent routing** — never over-resourcing simple questions, never under-resourcing complex longitudinal ones.
- **Total privacy** — the most intimate data a person generates runs locally or doesn't run at all.
- **Knowledge graph navigation** — not curriculum delivery. The Inevitable treats understanding as a topology to explore.

---

## GitHub Stats

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Suraj-creation&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true)](https://github.com/Suraj-creation)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Suraj-creation&layout=compact&theme=github_dark&hide_border=true)](https://github.com/Suraj-creation)

---

## Contact

[LinkedIn](https://www.linkedin.com/in/surajkumarvu) — Open to research collaborations, senior engineering roles, and discussions on agentic AI systems, knowledge architecture, and the future of how humans learn and understand themselves.

Building the infrastructure for the examined life and the examined mind — and the systems that take any person from zero to original contribution. Everything else is a means to that end.
