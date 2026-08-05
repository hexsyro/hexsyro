# What's in My Private Repositories

---

## SocialIntel

**A dataset marketplace offering pre-enriched, ready-to-use datasets across 100+ social media sources, with custom datasets delivered in 1–3 days.**

🔗 [socialintel.io](https://socialintel.io)

### Tech Stack

| Layer | Technologies |
|---|---|
| **Backend** | FastAPI, PostgreSQL (`psycopg2-binary`), APScheduler, Playwright, cloudscraper, feedparser, cryptography, PyJWT, PyOTP, httpx, requests, urllib3 |
| **Frontend** | Next.js, TypeScript, ESLint |

---

## Pulse Aggregator

**A live news-aggregation SaaS pulling from 10,000+ sources via Python crawlers, with a modern Next.js frontend.**

🔗 [pulseaggregator.com](https://pulseaggregator.com)

### Tech Stack

| Layer | Technologies |
|---|---|
| **Backend** | Python, FastAPI, PostgreSQL (`psycopg2-binary`), feedparser, Playwright, APScheduler, cloudscraper, cryptography, PyJWT, PyOTP, httpx, requests, urllib3 |
| **Frontend** | Next.js, TypeScript, ESLint |

---

## FinPull *(Coming Soon)*

**A unified trading dashboard for stocks, forex, crypto, and futures — built charting- and technical-analysis-first, with honest latency labeling on every asset class.**

### Tech Stack

| Layer | Technologies |
|---|---|
| **Backend** | FastAPI, Uvicorn, SQLAlchemy + Alembic, PostgreSQL, slowapi, JWT (PyJWT), WebSocket, Redis (pub/sub) |
| **Frontend** | Next.js, TypeScript |

---

## Certus Data *(Coming Soon)*

**A shared platform for a suite of data and content pipeline verification tools.** Rather than building separate applications for each tool, every module plugs into one shared backend, database, auth/billing system, and dashboard. Each tool retains its own landing page and pricing while sharing all underlying infrastructure.

### Tools in the Suite

| Tool | Purpose |
|---|---|
| **EnrichAudit** | Detects miscalculated engagement rates, stale or misapplied enrichment fields, and sentiment–emotion contradictions |
| **LinguaCheck** | Flags sentiment scores computed with the wrong language model (e.g., non-English content scored as English) |
| **SourceLock** | Verifies AI-generated summaries and claims trace back to real source posts (hallucination detection) |
| **ScrapeWatch** | Detects scrapers silently breaking when a target site's structure changes |
| **WhyChanged** | Generates plain-English explanations for why a tracked metric shifted |
| **NuanceBench** | Evaluates sentiment tools/vendors on sarcasm, slang, and emoji handling |
| **FilterGap** | Identifies bot/spam mentions slipping through budget-tier listening tools |

### Tech Stack

| Layer | Technologies |
|---|---|
| **Backend** | FastAPI, SQLAlchemy, PostgreSQL (`psycopg[binary]`, Alembic), pydantic-settings, PyJWT, bcrypt, python-multipart, email-validator |
| **Frontend** | Next.js, TypeScript (App Router) |

---
