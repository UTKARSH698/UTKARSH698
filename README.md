<div align="center">

# Utkarsh Batham

### Cloud · Platform · DevOps · Security Automation

[![Portfolio](https://img.shields.io/badge/Portfolio-utkarsh698.github.io-0a0a0a?style=flat-square&logo=github&logoColor=white)](https://utkarsh698.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-utkarsh--batham-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/utkarsh-batham-531913247)
[![Email](https://img.shields.io/badge/Email-contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:udaydeepak1928@gmail.com)
[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-Remote%20Cloud%20%2F%20Platform%20%2F%20DevOps-brightgreen?style=flat-square)](https://www.linkedin.com/in/utkarsh-batham-531913247)

</div>

---

I design and build **distributed systems and cloud infrastructure** — serverless pipelines, event-driven platforms, security automation, and observability stacks on AWS. Every system I build starts from correctness properties, failure modes, and operational reality — not features.

My work is architecture-first. I document CAP tradeoffs, failure scenarios, and engineering decisions explicitly, because the gap between a working demo and a production system is almost entirely in what you've thought through before writing code.

Open to **remote Cloud / Platform / DevOps / Security Automation** roles, and applying for an **M.Sc. (Fall 2027)** in distributed systems / security.

---

## Engineering Focus

| Domain | What I Build |
|--------|-------------|
| **Distributed Systems** | SAGA orchestration, event sourcing, idempotency, circuit breakers, compensation paths |
| **Cloud Infrastructure** | AWS serverless, Terraform IaC, CDK, multi-stack deployments, Lambda architecture |
| **Security Automation** | CSPM scanning, event-driven auto-remediation, CIS compliance, IAM least-privilege |
| **Observability** | Structured logging, CloudWatch dashboards, X-Ray tracing, Prometheus/Grafana |
| **Data Engineering** | Kinesis streams, Hive-partitioned S3 data lakes, Athena, real-time analytics |
| **CI/CD & DevOps** | GitHub Actions pipelines, Docker, multi-environment deployments, smoke testing |
| **AI Infrastructure** | RAG pipelines, vector search, FAISS, production retrieval systems |

---

## Open Source & Research

**Merged upstream — [grafana/alloy-scenarios #147](https://github.com/grafana/alloy-scenarios/pull/147)**
A CloudWatch-metrics scenario that runs end-to-end against LocalStack with no real AWS account — Grafana Alloy → Prometheus in ~90 seconds. Merged by Grafana DevRel with all 12 CI checks green. [Write-up](https://utkarsh698.github.io/notes.html#alloy-endpoint).

**Formal verification — [security-invariants-rbac](https://github.com/UTKARSH698/security-invariants-rbac)** · [![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20099385-blue?style=flat-square)](https://doi.org/10.5281/zenodo.20099385)
An independent preprint (not peer-reviewed) showing that three role-based access-control invariants — role-permission separation, transaction atomicity under revocation, and gateway policy consistency — each hold per-service but **break under cross-service concurrency**. A TLC-equivalent BFS checker explores the *complete* reachable state space: the buggy design reaches **188,160 distinct states with all three invariants violated**; the fixed design collapses to **4,928 states and holds clean**. Spec, traces, and checker are reproducible. [Write-up](https://utkarsh698.github.io/notes.html#rbac-invariants).

---

## Featured Projects

### [CloudFlow](https://github.com/UTKARSH698/CloudFlow) — Distributed SAGA Orchestration on AWS
Serverless order processing built around the SAGA pattern using Step Functions, DynamoDB, and AWS CDK. Implements idempotency as a security primitive, DynamoDB-backed circuit breakers shared across the Lambda fleet (cold-start safe), event sourcing with full audit trail, and explicit compensation paths. Load-tested at **1,100+ req/min (P99 < 120ms)** on LocalStack. 50+ tests covering all distributed failure modes.

`Python` `AWS Step Functions` `CDK` `DynamoDB` `SQS` `EventBridge` `X-Ray` `LocalStack`

---

### [CSPM](https://github.com/UTKARSH698/CSPM) — Cloud Security Posture Management
Serverless, event-driven AWS security automation with 23 checks mapped to the **CIS AWS Foundations Benchmark v1.5**. Auto-remediates safe misconfigurations (S3 public access, open security group rules), publishes compliance scores to CloudWatch, and alerts via SNS. IPv4 + IPv6 coverage; port-range aware SG checks that catch TCP 0–65535 rules most tools miss. 64 tests with moto mocks.

`Python` `AWS Lambda` `EventBridge` `Terraform` `IAM` `CloudTrail` `boto3`

---

### [Cloud_Pulse](https://github.com/UTKARSH698/Cloud_Pulse) — Serverless Analytics Pipeline
Lambda Architecture (batch + speed layers) on AWS serverless. Kinesis real-time streaming + SQS/S3/Athena batch path, Cognito JWT auth enforced at API Gateway, Hive-partitioned S3 data lake, React dashboard. **15 Terraform files**, full CI/CD pipeline, **~55ms P50 ingest latency**. Fail-open speed layer: Kinesis failure degrades to stale data, not data loss. Operates within AWS Free Tier.

`Python` `Kinesis` `Athena` `DynamoDB` `Terraform` `Cognito` `GitHub Actions`

---

### [agrifuture-platform](https://github.com/UTKARSH698/agrifuture-platform) — AI-Powered Agricultural Intelligence Platform
Production full-stack platform with **6 AI modules** (crop intelligence, disease detection, drone terrain analysis, market forecasting, digital twin simulation, conversational AI), live data feeds, Razorpay payments, OTP auth (email + SMS), and multi-language support across 7 Indian languages. **12,500+ lines** of TypeScript/React, deployed on Render with PostgreSQL.

`TypeScript` `React 19` `Node.js` `PostgreSQL` `Google Gemini` `Razorpay` `Express`

---

### [wikiqa-rag-system](https://github.com/UTKARSH698/wikiqa-rag-system) — Production RAG Pipeline
Full-stack retrieval-augmented generation over Wikipedia. Bi-encoder FAISS retrieval + cross-encoder re-ranking (**P@5 from ~0.60 to ~0.80**), source diversity enforcement, SSE token streaming, multi-LLM support (Groq/OpenAI/Anthropic), faithfulness scoring (LLM-as-judge hallucination detection), Prometheus/Grafana observability. Deployable on EC2 free tier.

`Python` `FastAPI` `FAISS` `React 18` `Prometheus` `Grafana` `Docker`

---

<div align="center">

*Distributed systems · Cloud infrastructure · Security automation · Available for remote roles*

</div>
