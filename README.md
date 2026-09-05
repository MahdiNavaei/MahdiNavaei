<div align="center">

# Mahdi Navaei

### Senior AI/ML Engineer · LLM & Agentic Systems · AI/ML Platform Engineering

**I build production AI systems that are observable, testable, evidence-driven, and safe to automate.**

7+ years across applied machine learning, production AI, LLM/RAG systems, agentic architectures, and ML platform engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mahdi%20Navaei-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mahdinavaei/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0004--1087--0234-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0004-1087-0234)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:MahdiNavaei1367@gmail.com)

</div>

---

## What I build

I work at the boundary between **AI research, software engineering, and production systems**.

My recent work is centered on:

- **Agentic AI systems** with explicit planning, tool boundaries, memory, replay, safety gates, and human oversight.
- **LLM/RAG systems** with measurable retrieval quality, deterministic evaluation, grounding, and failure analysis.
- **Local-first AI** for privacy-sensitive or infrastructure-constrained environments, including consumer-GPU deployment.
- **Production ML platforms** with APIs, CI/CD, observability, reproducible evaluation, data-quality controls, and safe rollout paths.
- **Evidence-driven automation** where decisions, failures, and approvals remain inspectable instead of disappearing behind a model response.

Currently working as a **Senior Machine Learning Engineer at Picnic** on a part-time, remote basis.

> My sweet spot is taking an AI capability from a promising prototype to a system that can actually be reviewed, tested, shipped, operated, and trusted.

---

## If you only have 90 seconds

| What you want to evaluate | Start here | What it demonstrates |
|---|---|---|
| **Agent reliability & debugging** | [ReproAgent](https://github.com/MahdiNavaei/ReproAgent) | Portable failure capture, safe mock replay, deterministic diffing, regression testing, provider integration boundaries |
| **Agentic platform architecture** | [ARIA](https://github.com/MahdiNavaei/aria) | Brain/Eye/Hand/Memory/Safety separation, HITL, replay-aware contracts, orchestration, local-first design |
| **Production product engineering** | [Career Radar](https://github.com/MahdiNavaei/Europe-Visa-Sponsorship-Jobs) | Real data ingestion, deterministic ranking, bilingual product UI, CI, Windows packaging, release governance |
| **Scientific ML rigor** | [HAI First-Day Risk Prediction](https://github.com/MahdiNavaei/HAI-FirstDay-Risk-Prediction) | Leakage-controlled rare-event modeling, frozen held-out evaluation, calibration, alert-budget analysis |

---

## Selected systems

### [ReproAgent — Flight Recorder for AI Agents](https://github.com/MahdiNavaei/ReproAgent)

An open-source reliability toolkit for preserving agent failures as portable, versioned test artifacts.

`Capture → AgentCase → Mock Replay → Diff → Regression Test`

- Framework-neutral execution capture with redaction and atomic local persistence.
- Fail-closed replay that never silently falls back to live model or tool execution.
- Deterministic exact / structural / normalized diffs and pytest regression integration.
- Explicit OpenAI Python SDK instrumentation without global monkeypatching or hidden credential discovery.
- CI across modern Python versions, strict typing, packaging, and offline compatibility testing.

**Focus:** Agent reliability · reproducibility · regression testing · safety boundaries · developer tooling

---

### [ARIA — Adaptive Reasoning & Intelligent Automation](https://github.com/MahdiNavaei/aria)

A contract-first agentic AI engineering platform for **observable, replay-aware, human-supervised automation**.

- Separates **Brain, Eye, Hand, Memory, Safety, and Event/Replay** into explicit system boundaries.
- Uses structured orchestration instead of hiding control flow inside prompt chains.
- Supports local models, vision-assisted UI understanding, tool execution, HITL routing, and durable traces.
- Public v0.2 documents the architecture through Phase 12 and includes a curated replay-contract implementation with unit and integration coverage.

**Stack:** Python · LangGraph · FastAPI · Redis · Qdrant · Playwright · VLM/OCR · Docker

---

### [Career Radar — Evidence-Based European Job Intelligence](https://github.com/MahdiNavaei/Europe-Visa-Sponsorship-Jobs)

A production-oriented desktop/web product for non-EU candidates who need **visa-sponsorship or relocation evidence**, not another generic job board.

- Deterministic sponsorship and eligibility rules with hard-negative handling and evidence provenance.
- Scheduled ingestion from a large registry of public employer ATS sources.
- Versioned, hash-verified market catalogs with transactional client updates and local candidate state.
- English/Persian UX with true RTL support.
- FastAPI + Next.js product stack, PostgreSQL/SQLite support, browser tests, dependency audits, coverage gates, Windows packaging, and release checks.

**Focus:** Data pipelines · product ML · deterministic ranking · CI/CD · release engineering · full-stack delivery

---

### [InvoiceMind — Evidence-First Document AI](https://github.com/MahdiNavaei/InvoiceMind)

A local-first invoice-processing platform designed around **quality gates, human review, auditability, and replayable decisions** rather than blind OCR automation.

- Structured ingestion, validation, OCR/layout handling, LLM extraction, post-processing, routing, review, and export.
- Policy-driven gates with reason-coded escalation and quarantine states.
- Run lifecycle, replay/cancel controls, audit endpoints, versioned configuration, and model registry.
- Bilingual product surface with a FastAPI backend and Next.js/TypeScript frontend.

**Focus:** Document AI · local LLMs · governance · HITL · traceability · production workflows

---

### [Tool-Memory-Evidence Retrieval Benchmark](https://github.com/MahdiNavaei/agentic-retrieval-evals-qdrant)

A local-first benchmark for measuring retrieval quality inside **agentic workflows**, where the system may need the right tool, memory, and evidence — not only the right document.

- Evaluates dense, sparse, reranked, and hybrid retrieval with Qdrant + FastEmbed.
- Reports Tool@K, Memory@K, Evidence@K, mean latency, and P95 latency.
- Requires no external LLM API at runtime.
- Keeps weak results visible instead of tuning labels until the benchmark looks good.

**Focus:** RAG evaluation · agent memory · retrieval systems · Qdrant · reproducibility

---

### [Early Prediction of Hospital-Acquired Infection](https://github.com/MahdiNavaei/HAI-FirstDay-Risk-Prediction)

A reproducible rare-event ML study using first-day EHR data across **119,743 encounters**.

- Leakage-controlled feature construction and a pre-specified frozen held-out evaluation boundary.
- XGBoost primary model under extreme class imbalance.
- Average Precision, AUROC, Brier score, calibration, uncertainty, subgroup analysis, and fixed alert-budget evaluation.
- Public release contains code, frozen configuration, tests, provenance notes, and aggregate reproducibility artifacts without exposing source patient data.

**Focus:** Applied ML research · imbalanced learning · evaluation design · clinical AI · reproducibility

---

## Engineering signature

| Area | How I approach it |
|---|---|
| **Reliability** | Explicit state, replayable artifacts, regression tests, bounded retries, failure-visible workflows |
| **Evaluation** | Task-specific metrics, baselines, frozen test boundaries, retrieval evals, calibration, quality gates |
| **Safety** | Human approval for sensitive actions, deterministic policy boundaries, redaction, fail-closed defaults |
| **Observability** | Structured events, trace IDs, decision evidence, audit trails, reproducible failure cases |
| **Local-first AI** | Local LLM/VLM inference when privacy, cost, network reliability, or hardware constraints matter |
| **Delivery** | APIs, frontend surfaces, Docker, migrations, CI/CD, packaging, release gates, checksums, reproducible builds |

---

## Core stack

**AI / ML**  
Python · PyTorch · scikit-learn · XGBoost · Transformers · OpenAI APIs · Ollama · local LLMs/VLMs · RAG · embeddings · reranking · CV · NLP · time series

**Agent & Retrieval Systems**  
LangGraph · tool orchestration · memory systems · Qdrant · FastEmbed · human-in-the-loop workflows · agent evaluation · replay/regression tooling

**Platforms & Data**  
FastAPI · PostgreSQL · SQLite · Redis · Kafka/Redpanda · SQLAlchemy · Alembic · MLflow · data-quality and drift monitoring

**Production & Delivery**  
Docker · GitHub Actions · CI/CD · pytest · mypy · Ruff · dependency/security checks · release automation · Windows packaging

**Product Engineering**  
Next.js · React · TypeScript · REST/WebSocket APIs · bilingual English/Persian interfaces · RTL

---

## More systems

- [TrustTrace](https://github.com/MahdiNavaei/AI-Scraper-TrustTrace) — self-auditing, evidence-first web extraction with safe repair planning.
- [DriveShield](https://github.com/MahdiNavaei/DriveShield) — local computer-vision platform for real-time collision-risk intelligence.
- [FlowCast](https://github.com/MahdiNavaei/FlowCast) — surge-pricing and ETA optimization platform.
- [Pharmaceutical Supply Chain Agentic AI](https://github.com/MahdiNavaei/pharmaceutical-supply-chain-agentic-ai) — multi-agent supply-chain decision system.
- [Google Scholar Scraper](https://github.com/MahdiNavaei/Google-Scholar-Scraper) — packaged research-data collection utility with release hardening and integrity checks.

Older learning and classical ML repositories are intentionally left out of the main showcase so the profile stays focused on current senior-level work.

---

## Research & publications

My work also includes applied machine learning research in healthcare and forecasting.

- **M. Navaei et al.** — [Leveraging Machine Learning for Pediatric Appendicitis Diagnosis](https://doi.org/10.1002/hsr2.70756), *Health Science Reports (Wiley)*.
- **M. Navaei, Z. Doogchi** — [Machine Learning Models for Predicting Heart Failure](https://doi.org/10.33140/ICVPR.04.01.02), *ICVPR*.
- **M. Navaei, M. Pahlevanzadeh** — [Forecasting Forex Market Stock Prices Using Neural Networks](https://doi.org/10.33140/AMLAI.05.02.09), *AMLAI*.

[ORCID →](https://orcid.org/0009-0004-1087-0234)

---

## What I am interested in

I am most interested in roles where **models are only one part of the system** and engineering quality matters just as much as model quality.

Relevant role families include:

**Senior AI/ML Engineer · Generative AI / LLM Engineer · Agentic AI Engineer · AI/ML Platform Engineer · MLOps / LLMOps · Applied AI Engineer · Applied Scientist · Senior Data Scientist**

I am open to international teams, remote collaboration, and **relocation opportunities in Europe with visa sponsorship**.

---

<div align="center">

### Let's build AI systems that survive contact with production.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mahdinavaei/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:MahdiNavaei1367@gmail.com)

</div>
