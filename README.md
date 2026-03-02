# AI & Data Engineer

Building data-intensive systems that connect AI capabilities to real-world workflows — from healthcare RAG pipelines to AI-powered fitness coaching to MCP-based creative tooling.

## What I Build

**Data Pipelines + AI Integration** — End-to-end systems where raw data (audio recordings, user logs, 3D scenes) flows through processing pipelines into AI-powered interfaces. I care about the plumbing as much as the model layer: async processing, vector search, job queues, multi-tenant isolation.

**MCP Servers** — Extending Claude's reach into desktop applications (Blender, Apple Notes) through the Model Context Protocol. Building the bridge between LLMs and the tools people already use.

**AI Agent Design** — Structuring LLM interactions as typed, testable agents with PydanticAI and Google ADK. Structured outputs, dependency injection, multi-agent coordination.

## Featured Projects

### [TherapyRAG](https://github.com/wilburwing-art/therapy-session-rag)
Production backend for therapy providers: upload recordings with consent, auto-transcribe via Deepgram with speaker diarization, embed into pgvector, serve a patient-facing chatbot with session citations. HIPAA-aware multi-tenant architecture with 660 passing tests under strict mypy.

`FastAPI / PostgreSQL + pgvector / Redis + RQ / Deepgram / OpenAI Embeddings / Claude`

### [Fit Agent](https://github.com/wilburwing-art/fit-AI)
AI fitness tracker using Claude Sonnet via PydanticAI agents for workout programming, nutrition planning, and progress analysis. Server-rendered with HTMX for zero-JS-framework simplicity. Multi-model orchestration (GPT, Gemini) planned for Phase 2.

`FastAPI / PydanticAI / Claude Sonnet / PostgreSQL / HTMX + Alpine.js`

### [MCP Apple + Blender](https://github.com/wilburwing-art/mcp-apple-blender)
MCP server integrations connecting Claude to Blender 3D and Apple Notes. AI-assisted 3D modeling (object manipulation, Poly Haven assets, Hyper3D model generation) and programmatic note management via AppleScript IPC.

`Python / FastMCP / Blender API / AppleScript / PolyHaven + Sketchfab + Hyper3D`

### [Throwform](https://github.com/wilburwing-art/throwform)
Parametric pottery rib tool generator — compute bowl profiles from clay science, generate manufacturing-ready SVGs, and run business economics on production runs. Where domain modeling meets creative tooling.

`React / TypeScript / Parametric Design / SVG Generation`

## Stack

**Languages**: Python, TypeScript, SQL

**AI/ML**: Claude API, OpenAI Embeddings, PydanticAI, Google ADK, Deepgram ASR, pgvector, RAG pipelines, MCP servers

**Backend**: FastAPI, PostgreSQL, Redis, SQLAlchemy/SQLModel, Alembic, Docker

**Frontend**: HTMX, Alpine.js, React, Tailwind CSS

**Infrastructure**: Docker Compose, GitHub Actions CI
