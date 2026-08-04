# MLOps & LLM Engineering

**Secure-by-default AI deployment for organizations handling sensitive data**

---

## The Problem I Solve

Organizations handling sensitive data — NGOs, civil society groups, mission-driven teams — are adopting LLMs without a security-first foundation. I bridge that gap: building RAG pipelines, MLOps workflows, and model-serving infrastructure that are secure by default, auditable from day one, and designed for resource-constrained environments where a breach isn't just a technical failure — it's a human one.

Four years running production IT infrastructure and security for an international NGO in Cambodia (Microsoft 365/Entra, DLP, network hardening, data-lifecycle automation), now applying those same principles to machine learning deployment.

---

## Portfolio

| Project | What it demonstrates | Stack | Status |
|---|---|---|---|
| [`secure-rag`](https://github.com/kroeungcyber/secure-rag) | RAG document Q&A for civil society orgs — offline-capable, denied-by-default auth, PII redaction, full audit logging | Python · LangChain · Chroma · FastAPI · Ollama · Docker | 🚧 In progress |
| [`mlops-pipeline`](https://github.com/kroeungcyber/mlops-pipeline) | End-to-end CI/CD for ML: test → train → version → containerize → deploy → automated retraining | scikit-learn · MLflow · GitHub Actions · Docker | 🚧 In progress |
| [`model-monitoring`](https://github.com/kroeungcyber/model-monitoring) | Post-deployment reliability: prediction logging, data/prediction drift detection, automated alerts | Evidently AI · Python · Docker | 📋 Planned |
| [`llm-quantization-bench`](https://github.com/kroeungcyber/llm-quantization-bench) | Throughput / latency / quality trade-offs of quantized open-source LLMs on commodity hardware | llama.cpp · GGUF · Python | 📋 Planned |
| [`k8s-deploy`](https://github.com/kroeungcyber/k8s-deploy) | Kubernetes deployment of the RAG stack with infrastructure-as-code | k3s · Terraform | 📋 Planned |

Earlier security & infrastructure work: [`nonprofit-security-toolkit`](https://github.com/kroeungcyber/nonprofit-security-toolkit) · [`m365-portfolio`](https://github.com/kroeungcyber/m365-portfolio) · [`kh-infra-care`](https://github.com/kroeungcyber/kh-infra-care)

---

## Core Stack

**LLM Engineering** — RAG pipelines · LangChain · Hugging Face Transformers · prompt engineering · open-source model serving (Ollama, llama.cpp) · quantization (GGUF)

**MLOps & DevOps** — Docker & Docker Compose · GitHub Actions CI/CD · MLflow · Evidently AI drift detection · FastAPI microservices

**Databases** — Chroma · Qdrant · PostgreSQL

**Security & Governance** — Microsoft Entra ID (Conditional Access, MFA) · Microsoft Purview (DLP, sensitivity labels) · Zero-Trust architecture · audit-log design · threat modeling for LLM systems (prompt injection, data leakage)

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

Phnom Penh, Cambodia · [LinkedIn](https://linkedin.com/in/kroeungcyber) · [Email](mailto:kroeungcyber@proton.com)
