# Hey, I'm Anubhab 👋

I build **production LLM systems** and **evaluation infrastructure**. Currently an Applied AI Engineer at **Hasprana Health Care Solutions**, working on clinical-grade ML pipelines. Final-year student at CMR Institute of Technology.

I'm focused on things that actually work in production: microservices that scale, RAG systems with measurable retrieval quality, LLM evaluation frameworks that catch real problems, and ML models that pass clinical validation.

**Currently looking for:** Full-time AI/ML engineering roles starting June 2027. Interested in startups, FAANG, and research orgs where the focus is system design, evaluation rigor, and shipping things that matter.

---

## What I've Built

Here's what's in my GitHub:

---

### 🏥 Clinical ML at Hasprana (Current)
Retraining medical vision models and shipping them to edge devices. The fun part: getting a U-Net from 88.8% to 97% IoU on real clinical data. The hard part: making sure it actually works on unseen patient images.

- **U-Net Retrain:** 0.888 → 0.970 IoU (+9.2%), ~70% error reduction on limbus localization
- **Confidence Scoring Audit:** Proved geometric confidence beats learned softmax confidence (statistical correlation analysis)
- **Production Inference:** ONNX + INT8 quantization, 75% model size reduction, clinical validation on 251 test cases
- **Tech Stack:** PyTorch, ONNX, OpenCV, clinical validation pipelines

### 🤖 Agentic Systems at Lamatic (Jan–May 2026)
Built agent pipelines for workflow automation. Traced why agents fail in production. Fixed them.

- **Failure Analysis:** Mapped agentic execution patterns → identified hallucinations, routing errors, stuck reasoning loops
- **Remediation:** A/B tested prompt engineering, routing logic, planning algorithms; deployed winners to production
- **Infrastructure:** Multi-step agents with tool-use + REST/GraphQL orchestration + multi-hop reasoning
- **Tech Stack:** LangChain, LangGraph, FastAPI, observability tooling

---

## My Projects

**[Kairos](https://github.com/ANUBprad/Kairos)** — RAG evaluation workbench that actually tells you what's working  
Full-stack platform for RAG experimentation. 12+ IR metrics, confidence intervals, observability pipeline. Built with Go + Python + Next.js microservices. The goal: stop guessing at retrieval quality and measure it properly.

**[MukhdaX](https://github.com/ANUBprad/MukhdaX)** — Face provenance & blockchain verification  
End-to-end pipeline: detect faces → generate embeddings → reverse-image search → deterministic fingerprinting → anchor on Ethereum. Integrated real Google Lens (no hardcoded results). Validates image authenticity on-chain.

**[APEXiq](https://github.com/ANUBprad/APEXiq)** — Natural language to SQL on F1 telemetry  
Agents write queries, validate them, report results. No human oversight. Built for real F1 strategy data.

**[LocalBench](https://github.com/ANUBprad/LocalBench)** — Offline LLM benchmarking  
Privacy-first model selection. Hardware-aware constraints (accuracy threshold + memory/latency budget). Runs entirely on your machine via Ollama. No cloud APIs. Built because sometimes you need to benchmark without shipping data anywhere.

**[RedOps](https://github.com/ANUBprad/RedOps)** — LLM red-teaming & evaluation  
Production framework for benchmarking LLM safety, groundedness, relevance. Semantic judging, forensic evidence tracking, full observability. Built to catch real failure modes.

---

## Research & Open Source

**Published Research**  
Co-authored "Benchmarking Instruction-Tuned Small Language Models on Extractive QA" at **ICAC2N 2026**. Compared Phi-3-mini, Mistral-7B, and Gemma-2 on identical QA datasets. Found that metric choice literally determines which model "wins" — important for real-world deployments where you need to pick the right tradeoff.

**Open Source Contributions**
- LangChain: PR #31802 (merged), PR #38465 (submitted) — bug fixes in eval and file tool callbacks
- Metaflow: Distributed ML pipeline optimization
- AOSSIE/OpenVerifiableLLM: LLM verification framework improvements

**Competitions**
- Smart India Hackathon 2024 — National Finalist
- Gen AI Exchange 2025 — National Finalist  
- EY Tecathon 6.0 — Technical Lead
- Hacker House Goa 2026 — Prepping on LangGraph + agentic systems

---

## What I Actually Know

**Core:** Python, TypeScript/JavaScript, SQL, Go  
**LLM Stuff:** Claude API, Groq, Ollama, LangChain, LangGraph, agentic systems, tool-use patterns  
**ML:** PyTorch, scikit-learn, XGBoost, SHAP, computer vision (OpenCV, InsightFace, RetinaFace, ArcFace)  
**Production:** ONNX, INT8/FP16 quantization, A/B testing, inference optimization, model versioning  
**Backend:** FastAPI, Flask, gRPC, PostgreSQL, ChromaDB, vector search, Redis  
**DevOps:** Docker, Kubernetes, GitHub Actions, CI/CD, observability (Prometheus, OpenTelemetry)

---

## What I Do Differently

**I audit large codebases.** 62K+ LOC analysis, god node detection, coupling analysis, architectural debt assessment. I find what's broken before it breaks in production.

**I build for reliability.** Kairos has 12+ IR metrics with confidence intervals. RedOps has semantic judging, forensic evidence, full observability. Not just "does it work"—I measure *how well* and *why it fails*.

**I ship clinical-grade systems.** My ML models get validated on real patient data. My inference pipelines get quantized, tested, and benchmarked. The code actually runs in production without exploding.

**I trace agentic failures.** I don't just build agents—I trace execution patterns, identify hallucinations and routing errors, and fix them systematically with A/B testing.

---

## Get in Touch

Want to talk about LLM systems, production ML, evaluation rigor, or anything in between?

📧 **Email:** [pradhananubhab25@gmail.com](mailto:pradhananubhab25@gmail.com)  
💼 **LinkedIn:** [linkedin.com/in/anubhabpradhan](https://www.linkedin.com/in/anubhabpradhan)  
💻 **LeetCode:** [leetcode.com/u/Anubhab25](https://leetcode.com/u/Anubhab25)

---
