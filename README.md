# Practical AI Implementation — Built, Documented, Trained, Handed Over

**I turn AI from a demo into a maintainable workflow — then teach the people who will run it.**

---

## What I Do

I find repetitive, high-volume processes inside an organization, map them, build
low-risk AI and automation on top of them, document the whole thing, train staff
to use it, and hand ownership back to the team that runs it. The goal is
institutional capability — not dependence on one specialist.

That discipline comes from six years running production IT infrastructure and
security for an international NGO in Cambodia (Microsoft 365/Entra, DLP, network
hardening, data-lifecycle automation). The same principles — secure by default,
auditable, built for resource-constrained environments — now shape how I ship AI.

My technical work spans RAG pipelines, workflow automation, and MLOps. My
differentiator is the other half of the job: **documentation, training, and
responsible-use guardrails**, built for organizations where a data leak isn't a
technical failure — it's a human one.

---

## Portfolio

Ten public repositories.

### AI workflow automation & implementation

| Project | What it demonstrates | Stack | CI |
|---|---|---|---|
| [m365-portfolio](https://github.com/kroeungcyber/m365-portfolio) | **Low-code/no-code digital transformation**: Power Automate leave-request workflow (multi-stage approvals), Power Apps UI, SharePoint governance, security & compliance lab | Power Automate · Power Apps · SharePoint · Microsoft 365 | [![CI](https://github.com/kroeungcyber/m365-portfolio/actions/workflows/security-lab-ci.yml/badge.svg)](https://github.com/kroeungcyber/m365-portfolio/actions/workflows/security-lab-ci.yml) |
| [secure-rag](https://github.com/kroeungcyber/secure-rag) | RAG document Q&A for sensitive orgs: denied-by-default auth, PII redaction, full audit logging, role-based onboarding, offline-capable | FastAPI · SQLite vec0/FTS5 · Ollama · Docker | [![CI](https://github.com/kroeungcyber/secure-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/secure-rag/actions/workflows/ci.yml) |
| [it-kb](https://github.com/kroeungcyber/it-kb) | Local IT knowledge base with a **central-control approval gate** (`PROGRAM.md`): path/URL whitelists, command execution off-by-default, hybrid BM25+vector retrieval, agent tooling | FastAPI · SQLite · Ollama · Docker | [![CI](https://github.com/kroeungcyber/it-kb/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/it-kb/actions/workflows/ci.yml) |
| [langchain-chroma-rag](https://github.com/kroeungcyber/langchain-chroma-rag) | Framework-stack comparison build of secure-rag: LCEL chain, hybrid EnsembleRetriever, persistent Chroma | LangChain · Chroma · Ollama | [![CI](https://github.com/kroeungcyber/langchain-chroma-rag/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/langchain-chroma-rag/actions/workflows/ci.yml) |

### MLOps & model reliability

| Project | What it demonstrates | Stack | CI |
|---|---|---|---|
| [mlops-pipeline](https://github.com/kroeungcyber/mlops-pipeline) | End-to-end CI/CD for ML: test → train → version → promote → containerize → retrain | scikit-learn · MLflow · GitHub Actions · Docker | [![CI](https://github.com/kroeungcyber/mlops-pipeline/actions/workflows/train.yml/badge.svg)](https://github.com/kroeungcyber/mlops-pipeline/actions/workflows/train.yml) |
| [model-monitoring](https://github.com/kroeungcyber/model-monitoring) | Post-deployment reliability: prediction logging, data/prediction drift detection, automated alerts | Evidently AI · FastAPI | [![CI](https://github.com/kroeungcyber/model-monitoring/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/model-monitoring/actions/workflows/ci.yml) |
| [llm-quantization-bench](https://github.com/kroeungcyber/llm-quantization-bench) | Throughput/latency/quality trade-offs of quantized open-source LLMs on commodity hardware | llama.cpp · GGUF · Python | [![CI](https://github.com/kroeungcyber/llm-quantization-bench/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/llm-quantization-bench/actions/workflows/ci.yml) |
| [k8s-deploy](https://github.com/kroeungcyber/k8s-deploy) | Kubernetes deployment of the RAG stack: default-deny NetworkPolicies, cert-manager TLS, infrastructure-as-code | k3s/k3d · Terraform · cert-manager | [![CI](https://github.com/kroeungcyber/k8s-deploy/actions/workflows/ci.yml/badge.svg)](https://github.com/kroeungcyber/k8s-deploy/actions/workflows/ci.yml) |

### Teaching & education

| Project | What it demonstrates | Stack |
|---|---|---|
| [university-ai-mapping](https://github.com/kroeungcyber/university-ai-mapping) | Scored AI opportunity map for a university process, plus a hands-on staff workshop ("draft, don't grade") | Markdown · prompt design · change management |

Earlier security & infrastructure work: [nonprofit-security-toolkit](https://github.com/kroeungcyber/nonprofit-security-toolkit)

---

## Teaching & Capability Building

- **Workshop** — ["Using AI to draft, not to grade"](https://github.com/kroeungcyber/university-ai-mapping/blob/main/workshop-ai-draft-not-grade.md) — 60–90 min hands-on session for non-technical staff, with prompt library and one-page handout.
- **AI opportunity map** — [scored prioritization of student enrollment](https://github.com/kroeungcyber/university-ai-mapping/blob/main/ai-opportunity-map.md) for AI-assisted improvement (value / simplicity / risk / sustainability / readiness).
- **Video demonstration** — 3–5 min walkthrough of `secure-rag` for a non-specialist audience *(in progress)*.

---

## Core Stack

**LLM Engineering** — RAG pipelines (hand-rolled agent loop and LangChain LCEL) · hybrid retrieval (RRF over vec0/FTS5, EnsembleRetriever) · prompt engineering · open-source model serving (Ollama, llama.cpp) · quantization (GGUF, F16 → Q4_K_M)

**Automation & No-Code/Low-Code** — Power Automate · Power Apps · workflow automation · webhooks · APIs · authentication services · AI agents

**MLOps & DevOps** — Docker & Docker Compose · GitHub Actions CI/CD (including a k3d end-to-end smoke) · Terraform · MLflow (tracking, model registry, promotion gates) · Evidently AI drift detection · FastAPI microservices · Kubernetes (k3s)

**Databases** — Chroma · SQLite (vec0 + FTS5) · PostgreSQL

**Security & Governance** — Microsoft Entra ID (Conditional Access, MFA) · Microsoft Purview (DLP, sensitivity labels) · Zero-Trust architecture · default-deny Kubernetes NetworkPolicies · cert-manager TLS · audit-log design · threat modeling for LLM systems (prompt injection, data leakage)

**Automation & Cloud** — Python · PowerShell · Microsoft 365 administration · SD-WAN

---

## How I Work

**Guardrails first, not bolted on.** Every pipeline ships with authentication denied
by default, structured audit logging, and a documented data-handling policy.

**Design → document → teach → transfer.** I don't hand over a script; I hand over a
runbook, a training session, and a named owner. Each repo's README includes
design-decisions and operating guidance, because the measure of success is whether
the team can run it after I'm gone.

**Built for the field.** Offline-capable, lightweight, observable, and recoverable —
because the organizations I build for don't run on hyperscaler budgets.

---

## Credentials

| Microsoft SC-900 | Microsoft MS-900 | Google Cybersecurity | CompTIA Security+ |
|---|---|---|---|
| Security Fundamentals | M365 Fundamentals | Completed | Completed |

**In progress:** Azure AI Fundamentals (AI-900) · DeepLearning.AI MLOps · AWS Cloud Practitioner

---

## Contact

Open to **AI implementation, digital-transformation, and capability-building roles** in
education and mission-driven organizations — where the goal is to build institutional
capability, not dependence on a specialist.

Phnom Penh, Cambodia · [LinkedIn](https://linkedin.com/in/kroeungcyber) · [Email](mailto:kroeungcyber@proton.me)
