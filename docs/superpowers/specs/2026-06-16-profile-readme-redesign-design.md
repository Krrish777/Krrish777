# Profile README Redesign — Design Spec

**Date:** 2026-06-16
**Repo:** `Krrish777/Krrish777` (GitHub profile README)
**Owner:** Krish Sharma (`Krrish777`)

## Problem

The current `README.md` is an unmodified export from `rahuldkjain/github-profile-readme-generator`. It is stale and sends mixed signals:

- Header says "Data Science enthusiast" while the toolbelt is mostly design/web (Photoshop, Illustrator, XD, Figma, HTML/CSS) — no clear identity.
- An 11-icon "tools I touched" wall with no narrative.
- Broken LinkedIn link (`linkedin.com/in/krish sharma` — space breaks the URL).
- Generic one-liner, trophy + default stats cards with no story.
- Does not reflect who Krish actually is or what his GitHub/portfolio show.

## Goal

A substance-forward profile README that resonates with Krish's real identity — **Applied AI Engineer** (agents, RAG, backend infra) — and serves two audiences: **recruiters** and **OSS collaborators**. Honest about traction (no fabricated metrics), proof-of-work over decoration.

## Identity (settled, consistent with portfolio)

- **Applied AI Engineer** — builds AI agents, RAG systems, and backend infrastructure.
- Style reference: `gautamkrishnar`'s profile (substance-forward, narrative + featured work), scaled honestly to Krish's footprint (most repos at 0★, so feature projects by *what they do and the stack they prove*, not by stars).

## Design decisions

| Decision | Choice |
|---|---|
| Direction | "The Builder" (substance-forward), no motion gimmicks |
| Stats theme | `github_dark`, `hide_border=true` |
| Typing SVG headline | **No** |
| Gradient/capsule banner | **No** |
| Snake animation | **No** |
| Trophy widget | **No** (dated) |
| WakaTime | **No** (no data yet) |
| PGP key | **No** |
| Streak card | **No** (low value for this audience) |
| Contact email | `777krrish@gmail.com` (confirmed) |

## README structure (section order)

### 1. Header
- `Hi, I'm Krish 👋`
- `Applied AI Engineer`
- One sharp line: *"I build AI agents, RAG systems, and backend infra — LangGraph · RAG · MCP · FastAPI."*
- Plain markdown (no typing SVG).

### 2. Intro bullets (emoji style)
- 🔭 Building: **TAP Voice Agent** — a C4GT GovTech student drop-off insight engine
- 🌱 Sharpening: web-scraping · finetuning · bash scripting
- 💬 Ask me about: LangGraph · RAG · MCP · agentic systems · vector search
- 🌍 Open source: **FreeCAD** contributor · contributing to **LangChain** · FOSSEE
- ✍️ First technical blog post coming soon
- 🔗 [Portfolio](https://krish-portfolio-psi-gilt.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/krish-sharma-3375b927b/) · `777krrish@gmail.com`

### 3. 🚀 Featured Projects (markdown table: Project · What it is · Stack)

| Project | What it is | Stack |
|---|---|---|
| **[TAP Voice Agent](https://github.com/Krrish777/TAP-voice-agent)** | C4GT GovTech drop-off insight engine — reason-aware conversation builds a sliceable student knowledge graph of *why* students drop off; multilingual (Hindi-first) voice delivery over a WhatsApp/IVR/USSD channel router; DPDP-audited; reproducible WER-under-noise benchmark | FastAPI · embeddings · Sarvam STT · SQLite/alembic |
| **[Sqlite_Python](https://github.com/Krrish777/Sqlite_Python)** ⭐16 | A SQLite-style database engine built from scratch in Python | Python |
| **[arXiv-Paper-Curator](https://github.com/Krrish777/arXiv-Paper-Curator)** | RAG pipeline that curates and answers over arXiv papers | RAG · vector search |
| **[Multilingual Voice Assistant](https://github.com/Krrish777/Multilingual-AI-based-Voice-Assistant)** | Multilingual voice assistant | Python · speech |

### 4. 🛠️ Tech Stack
Grouped `shields.io` (flat-square) badges by category. Real stack only — **no design-tool icons**:
- **Languages:** Python · C++ · SQL · TypeScript · JavaScript
- **GenAI & Orchestration:** LangChain · LangGraph · Google ADK · Agno · Haystack · DSPy · RAG · MCP
- **Data & ML:** PyTorch · Pandas · NumPy · Feature Engineering · Vector Search (HNSW) · Apache Airflow
- **Cloud & DevOps:** AWS (Lambda/S3/EC2) · GCP (Vertex AI/Cloud Run) · Docker · Kubernetes · CI/CD
- **Databases & Retrieval:** Qdrant · PgVector · Pinecone · OpenSearch · PostgreSQL · Redis · SQLite

### 5. 📊 GitHub Stats
- `github-readme-stats` overview card: `?username=Krrish777&show_icons=true&theme=github_dark&hide_border=true&count_private=true`
- Top languages card: `/top-langs?username=Krrish777&layout=compact&theme=github_dark&hide_border=true`

## Fixes baked in
- Repair broken LinkedIn link.
- Point all stat widgets at `Krrish777`.
- Unify identity to match the portfolio ("Applied AI Engineer").
- Remove the design-tool icon wall and the trophy.

## Out of scope (YAGNI)
Typing SVG, capsule banner, snake animation, trophy, WakaTime, PGP key, streak card, auto-updating blog feed (revisit once the first blog post exists).

## Success criteria
- A visitor instantly understands Krish is an Applied AI Engineer.
- Featured projects communicate real capability (agents, RAG, GovTech, systems-from-scratch) without relying on star counts.
- All links work; no stale/mismatched identity; clean, professional, low-maintenance.
