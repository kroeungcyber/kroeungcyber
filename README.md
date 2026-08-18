# MLOps & LLM Engineering

**Secure-by-default AI deployment for organizations handling sensitive data**

---

## The Problem I Solve

Organizations handling sensitive data — NGOs, civil society groups, mission-driven teams — are adopting LLMs without a security-first foundation. I bridge that gap: building RAG pipelines, MLOps workflows, and model-serving infrastructure that are secure by default, auditable from day one, and designed for resource-constrained environments where a breach isn't just a technical failure — it's a human one.

Four years running production IT infrastructure and security for an international NGO in Cambodia (Microsoft 365/Entra, DLP, network hardening, data-lifecycle automation), now applying those same principles to machine learning deployment.

---

## Portfolio

Six public repositories, all with live CI and v0.1.0 releases:

| Project | What it demonstrates | Stack | CI |
|---|---|---|---|
| [secure-rag](https://github.com/kroeungcyber/secure-rag) | RAG document Q&A for civil society orgs: denied-by-default auth, PII redaction, full audit logging, offline-capable | FastAPI · SQLite vec0/FTS5 · Ollama · Docker | [![CI](https://github.com/kroeungcyber/secure-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/secure-rag/actions/workflows/ci.yml) |
| [langchain-chroma-rag](https://github.com/kroeungcyber/langchain-chroma-rag) | The framework-stack comparison build of secure-rag: LCEL chain, hybrid EnsembleRetriever, persistent Chroma | LangChain · Chroma · Ollama | [![CI](https://github.com/kroeungcyber/langchain-chroma-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/langchain-chroma-rag/actions/workflows/ci.yml) |
| [k8s-deploy](https://github.com/kroeungcyber/k8s-deploy) | Kubernetes deployment of the RAG stack: default-deny NetworkPolicies, cert-manager TLS, infrastructure-as-code | k3s/k3d · Terraform · cert-manager | [![CI](https://github.com/kroeungcyber/k8s-deploy/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/k8s-deploy/actions/workflows/ci.yml) |
| [mlops-pipeline](https://github.com/kroeungcyber/mlops-pipeline) | End-to-end CI/CD for ML: test → train → version → promote → containerize → retrain | scikit-learn · MLflow · GitHub Actions · Docker | [![CI](https://github.com/kroeungcyber/mlops-pipeline/actions/workflows/train.yml/badge.svg)](https://github.com/kroeungcyber/mlops-pipeline/actions/workflows/train.yml) |
| [model-monitoring](https://github.com/kroeungcyber/model-monitoring) | Post-deployment reliability: prediction logging, data/prediction drift detection, automated alerts | Evidently AI · FastAPI | [![CI](https://github.com/kroeungcyber/model-monitoring/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/model-monitoring/actions/workflows/ci.yml) |
| [llm-quantization-bench](https://github.com/kroeungcyber/llm-quantization-bench) | Throughput/latency/quality trade-offs of quantized open-source LLMs on commodity hardware | llama.cpp · GGUF · Python | [![CI](https://github.com/kroeungcyber/llm-quantization-bench/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/llm-quantization-bench/actions/workflows/ci.yml) |

Earlier security & infrastructure work: [nonprofit-security-toolkit](https://github.com/kroeungcyber/nonprofit-security-toolkit) · [m365-portfolio](https://github.com/kroeungcyber/m365-portfolio)

---

## Core Stack

**LLM Engineering** — RAG pipelines (hand-rolled ReAct loop and LangChain LCEL) · hybrid retrieval (RRF over vec0/FTS5, EnsembleRetriever) · prompt engineering · open-source model serving (Ollama, llama.cpp) · quantization (GGUF, F16 → Q4_K_M)

**MLOps & DevOps** — Docker & Docker Compose · GitHub Actions CI/CD (including a k3d end-to-end smoke) · Terraform · MLflow (tracking, model registry, promotion gates) · Evidently AI drift detection · FastAPI microservices · Kubernetes (k3s)

**Databases** — Chroma · SQLite (vec0 + FTS5) · PostgreSQL

**Security & Governance** — Microsoft Entra ID (Conditional Access, MFA) · Microsoft Purview (DLP, sensitivity labels) · Zero-Trust architecture · default-deny Kubernetes NetworkPolicies · cert-manager TLS · audit-log design · threat modeling for LLM systems (prompt injection, data leakage)

**Automation & Cloud** — Python · PowerShell · Microsoft 365 administration · Power Automate · SD-WAN

---

## How I Work

**Guardrails first, not bolted on.** Every pipeline ships with authentication denied by default, structured audit logging, and a documented data-handling policy.

**Architectural thinking over tool collecting.** Each repo's README includes a design-decisions section: why this vector store, this chunk size, this quantization level — with the latency, cost, and scalability trade-offs measured, not guessed.

**Built for the field.** Offline-capable, lightweight, observable, and recoverable — because the organizations I build for don't run on hyperscaler budgets.

---

## Credentials

| Microsoft SC-900 | Microsoft MS-900 | Google Cybersecurity | CompTIA Security+ |
|---|---|---|---|
| Security Fundamentals | M365 Fundamentals | Completed | Completed |

**In progress:** Azure AI Fundamentals (AI-900) · DeepLearning.AI MLOps · AWS Cloud Practitioner

---

## Contact

Open to MLOps engineering roles, LLM deployment work, and AI governance consulting with mission-driven organizations.

Phnom Penh, Cambodia · [LinkedIn](https://linkedin.com/in/kroeungcyber) · [Email](mailto:kroeungcyber@proton.me)
