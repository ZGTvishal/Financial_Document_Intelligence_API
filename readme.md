A RAG-powered REST API that ingests financial documents (earnings reports, 10-Ks) and answers structured queries against them with source attribution.

Language - Python
API Framework - FastAPI
Vector DB - pgvector (PostgreSQL)
Embeddings - Google Gemini Embeddings
LLM - Gemma via LangChain
Task Queue - Redis + Celery
Storage - Local + S3-compatible (MinIO)
Containerisation - Docker + Docker Compose
Testing - pytest

3-Month Phases

Phase 1 — Weeks 1-4 (Foundation)

FastAPI project scaffold with Docker Compose
PDF upload endpoint + text extraction
Basic chunking + pgvector setup
Embed and store chunks

Phase 2 — Weeks 5-8 (RAG Core)

Query endpoint with semantic search
LangChain RAG chain with Gemma
Source attribution in responses
Async ingestion via Celery + Redis

Phase 3 — Weeks 9-12 (Polish)

Query history + basic caching
API authentication (JWT)
README, architecture diagram, demo script
Deploy via Docker Compose (locally or Railway)