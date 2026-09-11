# Anubhab Pradhan

Building production LLM systems and evaluation infrastructure. Final-year AI/Data Science student at CMR Institute of Technology. Currently interning at Hasprana Health Care Solutions on clinical ML pipelines.

**What I ship:** Full-stack systems (backend + frontend + DevOps). Microservices architectures. Statistical evaluation frameworks. Code audits at scale. Production ML on clinical-grade validation pipelines.

---

## Status

**Education:** B.E. Artificial Intelligence & Data Science | CMR Institute of Technology, Bengaluru  
**CGPA:** 8.1 | **Graduation:** June 2027 | **Student ID:** 1CR23AD019

**Placement Status:** Actively seeking full-time AI/ML engineering roles, starting June 2027. Open to startups, FAANG, and research positions emphasizing system design, evaluation rigor, and production optimization.

---

## Current Work

**Hasprana Health Care Solutions** — Applied AI Engineer  
*Aug 2026 – Present*

- Retrained U-Net segmentation model on clinical ophthalmic data: improved mean IoU from 0.888 to 0.970 (+9.2%), reduced limbus localization error by ~70%
- Conducted technical audit of confidence-scoring system; discovered geometric confidence was statistically superior to learned confidence via correlation analysis
- Productionized vision pipeline with PyTorch, ONNX, INT8 quantization; validated on 12 clinical images and 251 automated test cases achieving clinical-grade reliability

**Lamatic.ai** — Applied AI Engineer  
*Jan – May 2026*

- Traced agentic execution patterns in user workflows; identified hallucinated plans, tool-routing errors, and stuck reasoning loops as primary failure modes
- Designed and validated remediation strategies across prompt engineering, routing logic, and planning algorithms using A/B testing
- Built multi-step agent pipelines integrating tool-use, REST/GraphQL API orchestration, and multi-hop reasoning

---

## Projects

### Kairos — RAG Evaluation & Observability Workbench
Full-stack RAG experimentation platform with hybrid retrieval, multi-hop reasoning, and statistical evaluation.

- Engineered microservices architecture: Go gateway + Python services + Next.js portal
- Implemented 12+ IR metrics with confidence intervals and reproducible experiment tracking
- Built end-to-end observability pipeline capturing retrieval traces, chunk selections, scoring decisions
- **Tech:** Go, Python, TypeScript/Next.js, gRPC, PostgreSQL, ChromaDB, Prometheus, Docker, GitHub Actions

### MukhdaX — Face Image Provenance & Blockchain Verification
End-to-end verification pipeline: face detection → ArcFace representation → reverse-image discovery → deterministic fingerprinting → on-chain Ethereum anchoring.

- Integrated SerpApi for genuine Google Lens visual search (no hardcoded results)
- Implemented on-chain read-back verification without private keys
- Enforced exactly-one-face constraint; extracted metadata from all discovered public sources
- **Tech:** Python, FastAPI, InsightFace, RetinaFace, ArcFace, Web3.py, Solidity, Ethereum Sepolia

### APEXiq — F1 Strategy & BI Pipeline
Natural language to SQL pipeline for F1 telemetry and business intelligence. Agents write queries, validate them, report results. No human in the loop.

- End-to-end NL-to-SQL orchestration with validation layers
- Automated query generation and error recovery
- Deployed on real F1 telemetry datasets
- **Tech:** Python, LangChain, PostgreSQL, FastAPI

### LocalBench — Local LLM Benchmarking Platform
Privacy-first, offline-first benchmarking for open-source LLMs via Ollama. Hardware-aware model selection enabling cost-performance tradeoff decisions.

- Implemented hardware-aware model selection: accuracy threshold + memory/latency budget constraints
- Hardened structured generation with Pydantic validation and bounded retry logic
- Built CLI interface (Typer + Rich); no cloud API dependencies
- **Tech:** Python, PyTorch, Hugging Face, Ollama, Pydantic, Typer, JSONL

### RedOps — Autonomous LLM Red-Teaming & Evaluation Platform
Production-grade LLM evaluation framework benchmarking safety, groundedness, relevance with reproducible evaluation runs.

- Engineered durable evaluation workflows with provider-independent execution and semantic LLM judging
- Built full observability: metric confidence scores, reasoning traces, token usage, cost breakdown
- Designed evaluation metrics: safety scoring, hallucination detection, agent-based attack generation
- **Tech:** Python, FastAPI, PostgreSQL, Docker, Redis Streams, TypeScript

---

## Competitions & Recognition

- **Smart India Hackathon 2024** — National Finalist
- **Gen AI Exchange 2025** — National Finalist
- **EY Tecathon 6.0** — Participant & Technical Lead
- **Hacker House Goa 2026** — Preparing focus on LangGraph and agentic systems

---

## Publications & Open Source

**Research**  
Co-authored "Benchmarking Instruction-Tuned Small Language Models on Extractive QA" — *ICAC2N 2026* (published). Systematic evaluation of Phi-3-mini, Mistral-7B, and Gemma-2 on identical extractive QA datasets under controlled conditions. Quantified accuracy-efficiency tradeoffs across model sizes; demonstrated metric choice determines model ranking. Findings inform real-world model selection decisions.

**Open Source**
- LangChain: PR #31802 (merged) — Fixed missing else branch in evaluate in project() method
- LangChain: PR #38465 (submitted) — KeyError fix in file tool callback for rename operations
- Metaflow: Workflow optimization contributions
- AOSSIE/OpenVerifiableLLM: LLM verification framework improvements

---

## Technical Stack

**Languages:** Python, TypeScript/JavaScript, SQL, Go, Java, C/C++

**LLM & Agentic Systems:** Claude API, Groq, Ollama, LangChain, LangGraph, multi-agent orchestration, tool-use patterns, prompt engineering

**Machine Learning:** PyTorch, scikit-learn, XGBoost, SHAP, model evaluation, statistical testing, computer vision (OpenCV, InsightFace, RetinaFace, ArcFace)

**Production ML:** ONNX inference, INT8/FP16 quantization, model versioning, A/B testing, inference optimization

**Data & Databases:** PostgreSQL, ChromaDB, vector search, Redis, Celery, MongoDB

**Full-Stack & DevOps:** FastAPI, React/Next.js, Docker, Kubernetes, GitHub Actions, CI/CD

**Specializations:** Code audit & architecture analysis, system design, reliability engineering, evaluation methodology, agentic systems

**Team Leadership:** ML Lead, Data Voyagers (university ML club) — coordinated technical strategy, mentored teammates on model selection and data preprocessing.

**Certifications:** Data Science Job Simulation (Forage), Introduction to Machine Learning (NPTEL-SWAYAM), Full Stack Development (Infosys Springboard)

---

## Key Differentiators

**System Design.** Full-stack ownership of multi-service architectures. Kairos spans Go gateway + Python services + TypeScript frontend with production-grade infrastructure.

**Evaluation Rigor.** Statistical evaluation methodology, reproducible experiments, systematic metric design. 12+ IR metrics with confidence intervals; comprehensive LLM safety evaluations.

**Production ML.** End-to-end ownership from research prototype to deployment. Clinical validation on real medical data; inference optimization reducing model size by 75% while maintaining accuracy.

**Code Audit & Architecture.** 62K+ LOC analysis, god node detection, coupling analysis, complexity assessment, architectural debt assessment, refactoring roadmapping. Identified critical failure points and validated remediation strategies.

**Agentic AI.** Multi-agent orchestration, tool integration, reasoning chains, failure analysis and remediation at scale.

---

## Connect

📧 **Email:** [pradhananubhab25@gmail.com](mailto:pradhananubhab25@gmail.com)  
🔗 **GitHub:** [github.com/ANUBprad](https://github.com/ANUBprad)  
💼 **LinkedIn:** [linkedin.com/in/anubhabpradhan](https://www.linkedin.com/in/anubhabpradhan)  
💻 **LeetCode:** [leetcode.com/u/Anubhab25](https://leetcode.com/u/Anubhab25)
