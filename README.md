<p align="center">
  <img src="https://raw.githubusercontent.com/MahdiNavaei/MahdiNavaei/main/assets/profile-banner.png" alt="Mahdi Navaei — Senior AI/ML Engineer" width="100%" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/mahdinavaei/"><img src="https://img.shields.io/badge/LinkedIn-Mahdi%20Navaei-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://orcid.org/0009-0004-1087-0234"><img src="https://img.shields.io/badge/ORCID-0009--0004--1087--0234-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID" /></a>
  <a href="mailto:MahdiNavaei1367@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

I build **production AI systems that are observable, testable, evidence-driven, and safe to automate**.

Senior AI/ML Engineer with 7+ years across applied machine learning, LLM/RAG systems, agentic architectures, AI/ML platforms, and production automation. My strongest work sits at the boundary between **AI research, software engineering, and operational reliability**.

Currently a **Senior Machine Learning Engineer at Picnic** on a part-time, remote basis.

> My sweet spot: turning a promising AI capability into a system that can be reviewed, tested, shipped, operated, debugged, and trusted.

---

## If you only have 90 seconds

| Evaluate | Start here | Signal |
|---|---|---|
| **Production engineering** | [Career Radar](https://github.com/MahdiNavaei/Europe-Visa-Sponsorship-Jobs) | Real ingestion, deterministic decisioning, durable state, CI/CD, Windows releases, post-release hardening |
| **Agent reliability** | [ReproAgent](https://github.com/MahdiNavaei/ReproAgent) | Failure capture, fail-closed replay, deterministic diffing, regression tests, provider boundaries |
| **Agentic architecture** | [ARIA](https://github.com/MahdiNavaei/aria) | Brain/Eye/Hand/Memory/Safety separation, orchestration, HITL, replay-aware contracts, local-first design |
| **LLM governance & HITL** | [InvoiceMind](https://github.com/MahdiNavaei/InvoiceMind) | Evidence-first document AI, quality gates, quarantine, replay, auditability, policy-driven automation |
| **Scientific ML rigor** | [HAI First-Day Risk Prediction](https://github.com/MahdiNavaei/HAI-FirstDay-Risk-Prediction) | Rare-event modeling, frozen held-out evaluation, calibration, uncertainty, alert-budget analysis |

---

## Flagship systems

### [Career Radar — Evidence-Based European Job Intelligence](https://github.com/MahdiNavaei/Europe-Visa-Sponsorship-Jobs)

A production-oriented desktop/web product for non-EU candidates who need **visa-sponsorship and relocation evidence**, not another generic job board.

- Scheduled ingestion from public employer ATS sources with source-health and retry semantics.
- Deterministic sponsorship / eligibility logic with hard-negative handling and evidence provenance.
- Versioned, hash-verified market catalogs with transactional updates and local candidate state.
- FastAPI + Next.js, PostgreSQL/SQLite, browser tests, dependency audits, coverage gates, Windows packaging, and release checks.
- English/Persian UX with real RTL support.

**Signal:** production ownership · data pipelines · product ML · deterministic decisioning · CI/CD · release engineering

---

### [ReproAgent — Flight Recorder for AI Agents](https://github.com/MahdiNavaei/ReproAgent)

An open-source reliability toolkit for preserving agent failures as portable, versioned test artifacts.

`Capture → AgentCase → Mock Replay → Diff → Regression Test`

- Framework-neutral execution capture with redaction and atomic local persistence.
- Fail-closed replay that never silently falls back to live model or tool execution.
- Exact, structural, and normalized deterministic diffs with pytest regression integration.
- Explicit provider instrumentation boundaries, including OpenAI Python SDK integration.
- Contract, unit, integration, security, replay, diff, and regression coverage.

**Signal:** agent reliability · reproducibility · developer tooling · safety boundaries · regression engineering

---

### [ARIA — Adaptive Reasoning & Intelligent Automation](https://github.com/MahdiNavaei/aria)

A contract-first platform for **observable, replay-aware, human-supervised agentic automation**.

- Separates **Brain, Eye, Hand, Memory, Safety, Replay, Learning, Voice, and LLM** concerns into explicit system boundaries.
- Uses structured orchestration instead of hiding control flow inside prompt chains.
- Supports local models, vision-assisted UI understanding, tool execution, HITL routing, memory, and durable traces.
- Includes unit, integration, and E2E test structure plus build/test/docs workflows.
- Public repository is a curated implementation snapshot rather than a claim that every internal capability is public.

**Stack:** Python · LangGraph · FastAPI · Redis · Qdrant · Playwright · VLM/OCR · Docker

---

### [InvoiceMind — Evidence-First Document AI](https://github.com/MahdiNavaei/InvoiceMind)

A local-first invoice-processing platform designed around **quality gates, human review, auditability, and replayable decisions** rather than blind OCR automation.

- End-to-end ingestion, validation, OCR/layout, LLM extraction, post-processing, routing, review, and export.
- Policy-driven gates with reason-coded escalation and quarantine states.
- Replay/cancel lifecycle, audit endpoints, versioned runtime configuration, and model registry.
- Bilingual FastAPI + Next.js/TypeScript product surface.
- CI covers backend unit/integration tests, frontend type checks/tests, dependency audits, and performance smoke scenarios.

**Signal:** local LLMs · document AI · governance · HITL · traceability · production workflows

---

### [TrustTrace — Self-Auditing Web Extraction Agent](https://github.com/MahdiNavaei/AI-Scraper-TrustTrace)

A technical preview of evidence-driven web extraction that **checks its own output instead of treating every scrape as success**.

`Prompt → Validated Task → Bounded Extraction → Evidence Critic → Safe Repair Proposal`

- Detects suspicious outputs such as zero records, field mismatch, invalid URLs, parent-container contamination, and blocked targets.
- Distinguishes success, repair-needed, and blocked states instead of collapsing them into empty results.
- Produces non-executing, human-reviewable repair proposals.
- Includes sanitized success/corruption/blocked demos and focused evaluator, executor, and repair tests.
- Intentionally refuses unsafe access-control bypass and blind retry behavior.

**Signal:** evidence-driven automation · agent evaluation · failure semantics · safe repair planning · human oversight

---

### [HAI First-Day Risk Prediction](https://github.com/MahdiNavaei/HAI-FirstDay-Risk-Prediction)

A reproducible rare-event ML study using first-day EHR data across **119,743 encounters**.

- Leakage-controlled feature construction with a pre-specified frozen held-out evaluation boundary.
- XGBoost primary model under extreme class imbalance.
- Average Precision, AUROC, Brier score, calibration, uncertainty, subgroup analysis, and fixed alert-budget evaluation.
- Public release includes code, frozen configuration, tests, provenance notes, and aggregate reproducibility artifacts without exposing source patient data.
- Weaknesses and limitations remain visible instead of being tuned away after test evaluation.

**Signal:** applied ML research · imbalanced learning · evaluation design · clinical AI · reproducibility

---

## Focused engineering & evaluation work

- [Tool-Memory-Evidence Retrieval Benchmark](https://github.com/MahdiNavaei/agentic-retrieval-evals-qdrant) — dense/sparse/reranked/hybrid retrieval evaluation for agent tools, memory, and evidence with Qdrant + FastEmbed.
- [Google Scholar Scraper V2](https://github.com/MahdiNavaei/Google-Scholar-Scraper) — local Windows research utility with deterministic tests, explicit failure states, installer/portable builds, checksums, and release hardening.
- [DriveShield](https://github.com/MahdiNavaei/DriveShield) — local/offline collision-risk intelligence with BADAS-Open integration, FastAPI, React/TypeScript, and evaluation pipelines.
- [FlowCast](https://github.com/MahdiNavaei/FlowCast) — surge-pricing and ETA optimization with demand forecasting, geospatial routing, APIs, and a realtime dashboard.
- [Pharmaceutical Supply Chain Agentic AI](https://github.com/MahdiNavaei/pharmaceutical-supply-chain-agentic-ai) — multi-agent forecasting, routing, inventory, and monitoring workflows.
- [Hybrid Retail Recommender](https://github.com/MahdiNavaei/hybrid-retail-recommender) — collaborative + content-based recommendation with sparse matrices, cold-start handling, offline ranking metrics, API, UI, and Docker.

Older learning-oriented repositories remain public, but are intentionally not part of the primary showcase.

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

## Research & publications

My work also includes applied machine learning research in healthcare and forecasting.

- **M. Navaei et al.** — [Leveraging Machine Learning for Pediatric Appendicitis Diagnosis](https://doi.org/10.1002/hsr2.70756), *Health Science Reports (Wiley)*.
- **M. Navaei, Z. Doogchi** — [Machine Learning Models for Predicting Heart Failure](https://doi.org/10.33140/ICVPR.04.01.02), *ICVPR*.
- **M. Navaei, M. Pahlevanzadeh** — [Forecasting Forex Market Stock Prices Using Neural Networks](https://doi.org/10.33140/AMLAI.05.02.09), *AMLAI*.

[ORCID →](https://orcid.org/0009-0004-1087-0234)

---

## What I am looking for

I am most interested in roles where **models are only one part of the system** and engineering quality matters just as much as model quality:

**Senior AI/ML Engineer · Generative AI / LLM Engineer · Agentic AI Engineer · AI/ML Platform Engineer · MLOps / LLMOps · Applied AI Engineer · Applied Scientist · Senior Data Scientist**

Open to international teams, remote collaboration, and **relocation opportunities in Europe with visa sponsorship**.

---

<p align="center">
  <strong>Let's build AI systems that survive contact with production.</strong>
</p>

<p align="center">
  <a href="https://linkedin.com/in/mahdinavaei/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:MahdiNavaei1367@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
