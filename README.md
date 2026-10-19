# Hi, I'm Naveen 👋

Fresher building in public across LLM apps, ML pipelines, data analysis and full-stack web. Every project below has CI on GitHub Actions and a live demo on GitHub Pages.

## Projects

| Project | What it is | Stack | Demo |
|---|---|---|---|
| [agentops-mcp](https://github.com/naveecode/agentops-mcp) | Tool-calling LangGraph agent exposed via REST and an MCP server, with RAG ingest, Redis cache and a RabbitMQ worker (retries + DLQ) | FastAPI, LangGraph, MCP SDK, Redis, MongoDB, RabbitMQ, Next.js, K8s (kind) | [live](https://naveecode.github.io/agentops-mcp/) |
| [llm-evalkit](https://github.com/naveecode/llm-evalkit) | LLM evaluation toolkit (exact match, JSON-schema validity, LLM-as-judge, latency/cost) over OpenAI-compatible endpoints, plus a QLoRA recipe | Python async, Pydantic, Typer, SQLite, Next.js/TS, HF TRL/PEFT | [leaderboard](https://naveecode.github.io/llm-evalkit/) |
| [ml-serving-pipeline](https://github.com/naveecode/ml-serving-pipeline) | Churn model from training to serving: Optuna-tuned XGBoost (ROC AUC 0.846 held-out), MLflow registry, FastAPI scoring, Evidently drift reports | XGBoost, Optuna, MLflow, FastAPI, MongoDB, Evidently, Docker, K8s | [live](https://naveecode.github.io/ml-serving-pipeline/) |
| [nyc-taxi-insights](https://github.com/naveecode/nyc-taxi-insights) | SQL + pandas analysis of NYC TLC taxi trips with a published dashboard and business insights | DuckDB, SQL, pandas, Plotly | [dashboard](https://naveecode.github.io/nyc-taxi-insights/) |
| [jobtrackr](https://github.com/naveecode/jobtrackr) | Full-stack job tracker with auth and per-user data | Next.js 14, TypeScript, Auth.js, Prisma/Postgres | [demo](https://naveecode.github.io/jobtrackr/) |
| [orderflow-api](https://github.com/naveecode/orderflow-api) | Order-management REST API with JWT auth, transactional order workflows and idempotent writes | Java 21, Spring Boot 3, Spring Security, JPA/PostgreSQL, Flyway, Testcontainers | [API docs](https://naveecode.github.io/orderflow-api/) |
| [upabode](https://github.com/naveecode/upabode) | Rental listing finder with client-side search, filters and sort over sample homes, shipped as a static export | Next.js, TypeScript, Tailwind, Vitest | [demo](https://naveecode.github.io/upabode/) |
| [ticketdesk-api](https://github.com/naveecode/ticketdesk-api) | Helpdesk REST API with JWT auth, Celery + Redis background jobs and LLM ticket triage | Python, Django, DRF, Celery, Redis, PostgreSQL | [live](https://naveecode.github.io/ticketdesk-api/) |
| [vision-detect](https://github.com/naveecode/vision-detect) | Object detection pipeline: fine-tuned detector, ONNX export, FastAPI inference and an in-browser demo | PyTorch, OpenCV, ONNX, FastAPI | [demo](https://naveecode.github.io/vision-detect/) |

## Open source

- **Merged:** [huggingface/transformers#49652](https://github.com/huggingface/transformers/pull/49652), a torch>=2.8 guard for distributed checkpointing.
- More open PRs: [my contributions](https://github.com/pulls?q=is%3Apr+author%3Anaveecode+is%3Apublic).

## Skills

Python · TypeScript · Java · SQL · FastAPI · LangGraph · MCP · RAG · Hugging Face · PyTorch · OpenCV · XGBoost · MLflow · Next.js · Django · Spring Boot · Docker · Kubernetes · GitHub Actions
