# Article Digest — Mahesh Paka
# Proof points from full resume library (61 variants)
# Last updated: 2026-06-01

## Top Proof Points (use in evaluations)

### UnitedHealth Group (Optum) — Houston TX | Jan 2024–Present
- GraphRAG pipeline (Neo4j + FAISS): latency 240ms → 110ms
- LangGraph multi-agent orchestration over millions of claims records
- HIPAA-compliant PHI guardrails — zero incidents in 18 months production
- LangSmith + pytest-llm golden dataset eval — caught 3 prompt regressions before prod
- FastAPI microservices on AWS EKS: sub-200ms latency at 1,000 RPS
- Azure AI Foundry + LangChain agents for claims-denial explainability
- Fine-tuned GPT-4o in Azure ML secure enclaves for triage accuracy
- Kore.ai virtual nurse: 50+ intents, HIPAA-compliant eligibility + symptom guidance
- Snowflake Snowpark: 3TB historical claims joined with social determinants
- Medicaid T-MSIS / PERM / MARS federal reporting, CMS-compliant
- XGBoost hospital readmission prediction with feature importance for care teams
- 4-billion-row claim table PostgreSQL partitioning — freed 1.2TB cold storage
- AWS KMS envelope encryption on all outbound service calls

### NC Department of Transportation — Raleigh NC | Sep 2020–Dec 2023
- PySpark Structured Streaming at 2,000 QPM sensor streams
- ETL run time cut 60% (AWS Glue, Parquet, S3)
- Weaviate HNSW vector store — sub-second queries over 3 years of incident embeddings
- FAISS IVF-PQ vs Weaviate benchmark — cut retrieval CPU 28%
- Lane-closure ML recommendation engine (gradient-boost)
- 85%+ branch coverage with pytest + Mutmut mutation testing
- AWS Lex V2 migration from Avaya IVR — reduced recognition errors
- Prophet time-series models for traffic congestion (monthly SageMaker retraining)
- ONNX Runtime edge scoring on roadside IoT devices
- k6 load tests: 5,000 RPS sustained for vector search APIs

### Fiserv — Alpharetta GA | Jun 2018–Aug 2020
- Kafka Streams fraud-signal pipeline: sub-second propagation
- PCI-DSS tokenization via Vault APIs
- Reconciliation window reduced by 2 hours (gRPC bidirectional streaming)
- FAISS IVF-Flat for near-duplicate fraud pattern detection (40ms)
- CQRS + Azure Service Bus: halved resource contention on payment auth
- Delta Lake on Azure Databricks for ACID-compliant reconciliations
- LightGBM fraud classifiers inside Azure ML endpoints
- CDC via Debezium: nightly exports 400GB → 30GB

## Key Differentiators
- Production RAG + GraphRAG at healthcare enterprise scale
- HIPAA-compliant multi-agent systems with PHI guardrails
- Multi-cloud MLOps: AWS + Azure + GCP
- Open source: agent-skills-kit (2.4K GitHub stars, TLDR AI + Ben's Bites)
- 10+ years Python, daily production use
- Taught AI Engineering (6 cohorts, 38 lectures, 16 graded projects)

## Tech Breadth (for ATS matching)
LangChain, LangGraph, LlamaIndex, Haystack, OpenAI GPT-4o, Claude 3, AWS Bedrock, Azure OpenAI,
RAG, GraphRAG, FAISS, ChromaDB, Neo4j, Pinecone, Weaviate, pgvector, Sentence-BERT,
FastAPI, Flask, Django REST, Node.js, GraphQL, gRPC, Python 3.11, TypeScript, React 18,
AWS EKS/Lambda/Glue/Fargate/Bedrock, Azure AKS/DevOps/ML/Synapse/Fabric/AI Foundry,
GCP Vertex AI, Snowflake, Snowpark, dbt, Databricks, Delta Lake, PySpark, Kafka, Airflow,
PostgreSQL, Redis, Elasticsearch, Kafka Streams, RabbitMQ,
Terraform, Docker, Kubernetes, Argo Rollouts, Helm, GitHub Actions,
OpenTelemetry, Grafana, Prometheus, LangSmith, MLflow, SageMaker,
pytest, pytest-llm, Great Expectations, Schemathesis, Mutmut, k6, Locust,
Kore.ai, AWS Lex V2, Amazon Connect, Azure Bot Service, Semantic Kernel,
Hyperexponential Canvas SDK, Charles River IMS, FIX protocol, IBOR,
T-MSIS, PERM, MARS, Ab Initio, Informatica PowerCenter
