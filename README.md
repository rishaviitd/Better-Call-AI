# Production-Grade Agentic Legal RAG System

A production-grade agentic legal research and reasoning system built using modern AI infrastructure and distributed systems architecture.

---

# Tech Stack

## Frontend

| Layer              | Tech                     |
| ------------------ | ------------------------ |
| Frontend Framework | Next.js                  |
| UI Components      | shadcn/ui + Tailwind CSS |
| Authentication     | Clerk                    |
| Streaming          | SSE + WebSockets         |

---

## Backend

| Layer               | Tech                    |
| ------------------- | ----------------------- |
| Backend API         | FastAPI                 |
| API Validation      | Pydantic                |
| Durable Workflows   | Temporal                |
| Background Workers  | Temporal Workers        |
| Working Memory      | Redis (AWS ElastiCache) |
| Long-Term Memory    | OpenMemory              |
| Relational Database | Postgres (AWS RDS)      |
| File Storage        | AWS S3                  |
| Containerization    | Docker                  |
| Container Registry  | AWS ECR                 |
| Deployment Runtime  | ECS Fargate             |
| Secrets Management  | AWS Secrets Manager     |
| Logs                | CloudWatch Logs         |
| Metrics             | CloudWatch Metrics      |
| Error Monitoring    | Sentry                  |
| CI/CD               | GitHub Actions          |

---

## AI Infrastructure

| Layer               | Tech                     |
| ------------------- | ------------------------ |
| Agent Orchestration | LangGraph                |
| Vector Database     | Qdrant                   |
| Embeddings          | Zembed                   |
| Reranking           | Zembed                   |
| Retrieval Harness   | Custom Python Layer      |
| OCR / Parsing       | LlamaParse               |
| AI Tracing          | LangSmith                |
| Evaluation Layer    | LangSmith + Custom Evals |

---

## AWS Services

| Service Type        | AWS Service     |
| ------------------- | --------------- |
| Compute             | ECS Fargate     |
| Relational Database | RDS Postgres    |
| Redis               | ElastiCache     |
| Object Storage      | S3              |
| Container Registry  | ECR             |
| Logging & Metrics   | CloudWatch      |
| Secrets Management  | Secrets Manager |
