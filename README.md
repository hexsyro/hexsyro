# Private Repositories

A collection of SaaS products spanning social data intelligence, news aggregation, multi-asset trading, and data pipeline verification.

---

## SocialIntel

**A dataset marketplace offering pre-enriched, ready-to-use datasets across 100+ social media sources, with custom datasets delivered in 1–3 days.**

🔗 [socialintel.io](https://socialintel.io)

### Key Features

- **100+ Platform Integrations** — Coverage across all major social media platforms
- **Pre-Enriched Datasets** — Quality-scored, ready-to-use data with no manual cleanup required
- **Custom Dataset Builder** — 1–3 day turnaround on bespoke data requests
- **Background Workers** — Auto-scaling worker architecture for task automation

### Tech Stack

| Layer | Technologies |
|---|---|
| **Backend** | FastAPI, PostgreSQL (`psycopg2-binary`), APScheduler, Playwright, cloudscraper, feedparser, cryptography, PyJWT, PyOTP, httpx, requests, urllib3 |
| **Frontend** | Next.js, TypeScript, ESLint |

---

## Pulse Aggregator

**A live news-aggregation SaaS pulling from 10,000+ sources via Python crawlers, with a modern Next.js frontend.**

🔗 [pulseaggregator.com](https://pulseaggregator.com)

### Key Features

- **10,000+ Sources** — RSS feeds from major news outlets worldwide
- **Multi-Tier Scraping** — RSS ingestion with JavaScript-rendered page fallback
- **Anti-Blocking** — User-agent rotation and stealth scraping measures
- **Semantic Deduplication** — ML-based similarity detection to eliminate near-duplicate content
- **Full-Text Search** — Native PostgreSQL full-text search
- **Keyword Alerts** — Real-time email notifications on keyword matches
- **Weekly Digests** — Automated digest email delivery
- **Translation** — Support for 20+ languages

### Tech Stack

| Layer | Technologies |
|---|---|
| **Backend** | Python, FastAPI, PostgreSQL (`psycopg2-binary`), feedparser, Playwright, APScheduler, cloudscraper, cryptography, PyJWT, PyOTP, httpx, requests, urllib3 |
| **Frontend** | Next.js, TypeScript, ESLint |

---

## FinPull *(Coming Soon)*

**A unified trading dashboard for stocks, forex, crypto, and futures — built charting- and technical-analysis-first, with honest latency labeling on every asset class.**

### Key Features

- **Multi-Asset Trading** — Stocks, forex, crypto, and futures unified in one dashboard
- **Real-Time Charts** — Advanced charting and technical analysis tools
- **Watchlists & Alerts** — Customizable watchlists with automated alerting
- **Live Market Data** — Real-time WebSocket streaming with transparent, honest latency labeling
- **WebSocket API** — Low-latency streaming for live ticks and market data

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

### Key Features

- **Multi-Tool Platform** — Shared backend, database, auth, and billing across 7 verification tools
- **Tool Router** — Extensible registry for adding new tools as self-contained modules
- **Findings Engine** — Generic read/write layer for analysis results, shared across every tool
- **Modular Architecture** — Each tool lives in its own folder with dedicated `router.py` and `logic.py`
- **Object Storage** — Local storage for uploaded datasets initially, with S3-compatible storage planned

### Tech Stack

| Layer | Technologies |
|---|---|
| **Backend** | FastAPI, SQLAlchemy, PostgreSQL (`psycopg[binary]`, Alembic), pydantic-settings, PyJWT, bcrypt, python-multipart, email-validator |
| **Frontend** | Next.js, TypeScript (App Router) |

---
