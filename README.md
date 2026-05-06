<div align="center">

# Utkarsh Batham

### Cloud · Platform · DevOps · Security Automation

[![Portfolio](https://img.shields.io/badge/Portfolio-utkarsh698.github.io-0a0a0a?style=flat-square&logo=github&logoColor=white)](https://utkarsh698.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-utkarsh--batham-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/utkarsh-batham)
[![Email](https://img.shields.io/badge/Email-contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:utkarsh698@gmail.com)

</div>

---

I build distributed systems and cloud infrastructure — serverless pipelines, security automation, and event-driven platforms on AWS. My work is architecture-first: every project is designed around correctness properties, failure modes, and operational reality before features.

Open to remote Cloud / Platform / DevOps / Security Automation roles and engineering internships.

---

## Engineering Focus

| Domain | What I Build |
|---|---|
| **Distributed Systems** | SAGA orchestration, event sourcing, idempotency, circuit breakers |
| **Cloud Infrastructure** | AWS serverless, Terraform IaC, CDK, Lambda architecture |
| **Security Automation** | CSPM scanning, auto-remediation, CIS compliance, IAM least-privilege |
| **Observability** | Structured logging, CloudWatch dashboards, X-Ray tracing, Prometheus/Grafana |
| **Data Engineering** | Kinesis streams, Athena/S3 data lakes, DynamoDB, real-time analytics |
| **CI/CD & DevOps** | GitHub Actions pipelines, Docker, EC2, multi-env deployments |
| **AI Infrastructure** | RAG pipelines, vector search, FAISS, production LLM systems |

---

## Projects

### [CloudFlow](https://github.com/UTKARSH698/CloudFlow) — Distributed SAGA Orchestration on AWS
Serverless order processing system built around the SAGA pattern using Step Functions, DynamoDB, and AWS CDK. Implements idempotency as a security primitive, DynamoDB-backed circuit breakers, event sourcing, and explicit compensation paths. Load-tested at 1,100+ req/min (P99 < 120ms) on LocalStack. 50+ tests covering all distributed failure modes.

`Python` `AWS Step Functions` `CDK` `DynamoDB` `SQS` `EventBridge` `X-Ray`

---

### [CSPM](https://github.com/UTKARSH698/CSPM) — Cloud Security Posture Management
Serverless, event-driven AWS security scanner with 23 checks mapped to the CIS AWS Foundations Benchmark. Auto-remediates safe misconfigurations (S3 public access, open security group rules), publishes compliance scores to CloudWatch, and alerts via SNS. IPv4 + IPv6 coverage; port-range aware SG checks. 64 tests with moto mocks.

`Python` `AWS Lambda` `EventBridge` `Terraform` `IAM` `CloudTrail` `boto3`

---

### [CloudPulse](https://github.com/UTKARSH698/Cloud_Pulse) — Serverless Analytics Pipeline
Lambda Architecture (batch + speed layers) built on AWS serverless. Kinesis real-time streaming + SQS/S3/Athena batch path, Cognito JWT auth, Hive-partitioned S3 data lake, and a React dashboard. 15 Terraform files, full CI/CD pipeline, ~55ms P50 ingest latency. Operates within AWS Free Tier.

`Python` `Kinesis` `Athena` `DynamoDB` `Terraform` `Cognito` `GitHub Actions`

---

### [AgriFuture Platform](https://github.com/UTKARSH698/agrifuture-platform) — AI-Powered Agricultural Intelligence Platform
Production full-stack platform with 6 AI modules (crop intelligence, disease detection, drone terrain analysis, market forecasting, digital twin simulation, conversational AI), live data feeds, Razorpay payments, OTP auth, and multi-language support across 7 Indian languages. 12,500+ lines of TypeScript/React, deployed on Render.

`TypeScript` `React 19` `Node.js` `PostgreSQL` `Google Gemini` `Razorpay` `Terraform`

---

### [WikiQA RAG System](https://github.com/UTKARSH698/wikiqa-rag-system) — Production RAG Pipeline
Full-stack retrieval-augmented generation system over Wikipedia. Bi-encoder FAISS retrieval + cross-encoder re-ranking (P@5 from ~0.60 to ~0.80), source diversity enforcement, SSE token streaming, multi-LLM support (Groq/OpenAI/Anthropic), faithfulness scoring, Prometheus/Grafana observability. Deployable on EC2 free tier.

`Python` `FastAPI` `FAISS` `React 18` `Prometheus` `Grafana` `Docker`

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=UTKARSH698&show_icons=true&theme=github_dark&hide_border=true&count_private=true&rank_icon=github)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=UTKARSH698&layout=compact&theme=github_dark&hide_border=true&langs_count=6)

</div>

---

<div align="center">

*Distributed systems · Cloud infrastructure · Security automation · Available for remote roles*

</div>
