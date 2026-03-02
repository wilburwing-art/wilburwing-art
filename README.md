# AI & Data Engineer

Building data-intensive systems that connect AI capabilities to real-world workflows — from healthcare RAG pipelines to multi-model fitness coaching to MCP-based creative tooling.

## What I Build

**Data Pipelines + AI Integration** — End-to-end systems where raw data (audio recordings, user logs, 3D scenes) flows through processing pipelines into AI-powered interfaces. I care about the plumbing as much as the model layer: async processing, vector search, job queues, multi-tenant isolation.

**MCP Servers** — Extending Claude's reach into desktop applications (Blender, Apple Notes) through the Model Context Protocol. Building the bridge between LLMs and the tools people already use.

**Multi-Model Orchestration** — Routing to the right model for the right task. Claude Opus for deep reasoning, Sonnet for conversation, GPT for cheap extraction, Gemini for million-token context. 

## Featured Projects

### [TherapyRAG](https://github.com/wilburwing-art/therapy-session-rag)
Production backend for therapy providers: upload recordings with consent, auto-transcribe via Deepgram with speaker diarization, embed into pgvector, serve a patient-facing chatbot with session citations. HIPAA-aware multi-tenant architecture with 407 passing tests under strict mypy.

`FastAPI / PostgreSQL + pgvector / Redis + RQ / Deepgram / OpenAI Embeddings / Claude`

### [Fit Agent](https://github.com/wilburwing-art/fit-AI)
AI fitness tracker using a multi-model strategy — Claude Opus for periodized program design, Sonnet for coaching, GPT-5-mini for NL data extraction, Gemini 2.5 Pro for long-context analysis over 2+ years of history. Server-rendered with HTMX for zero-JS-framework simplicity.

`FastAPI / PydanticAI / Claude + GPT + Gemini / PostgreSQL / HTMX + Alpine.js`

### [MCP Apple + Blender](https://github.com/wilburwing-art/mcp-apple-blender)
MCP server integrations connecting Claude to Blender 3D and Apple Notes. AI-assisted 3D modeling (object manipulation, Poly Haven assets, Hyper3D model generation) and programmatic note management via AppleScript IPC.

`Python / FastMCP / Blender API / AppleScript / PolyHaven + Sketchfab + Hyper3D`

### [Throwform](https://github.com/wilburwing-art/throwform)
Parametric pottery rib tool generator — compute bowl profiles from clay science, generate manufacturing-ready SVGs, and run business economics on production runs. Where domain modeling meets creative tooling.

`React / TypeScript / Parametric Design / SVG Generation`

## Stack

**Languages**: Python, TypeScript, SQL

**AI/ML**: Claude API, OpenAI Embeddings, PydanticAI, Deepgram ASR, pgvector, RAG pipelines, MCP servers

**Backend**: FastAPI, PostgreSQL, Redis, SQLAlchemy/SQLModel, Alembic, Docker

**Frontend**: HTMX, Alpine.js, React, Tailwind CSS

**Infrastructure**: Docker Compose, Fly.io, MinIO (S3), GitHub Actions CI
