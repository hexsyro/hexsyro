# Here are my Private Repositories

## Social Intel

A dataset marketplace that offers pre-enriched ready datasets across 100+ social media sources and builds custom datasets automatically within 1-3 days.

### Tech Stack

# Backend
FastAPI , PostgreSQL (psycopg2-binary) , APScheduler , playwright , cloudscraper , feedparser   
cryptography , pyjwt , pyotp , httpx , requests , urllib3

# Frontend  
Next.js , TypeScript , eslint 

### Key Features

- **100+ Platform Integrations** - Covers all major social media platforms
- **Pre-enriched Datasets** - High-quality, ready-to-use datasets with quality scoring
- **Custom Dataset Builder** - 1-3 day turnaround for custom requests
- **Background Workers** - Auto-scaling architecture with task automation

### Links

- **WebApp**: https://socialintel.io

---

# Pulse Aggregator

Live news-aggregation SaaS with 10,000+ sources, Python crawlers, and Next.js frontend.

**Live:** [pulseaggregator.com](https://pulseaggregator.com)

### Tech Stack

# Backend
Python + FastAPI, PostgreSQL (psycopg2-binary), feedparser, Playwright, APScheduler, cloudscraper, cryptography, pyjwt, pyotp, httpx, requests, urllib3

# Frontend  
Next.js, TypeScript, ESLint

### Key Features

- **10,000+ Sources** - RSS feeds from major news outlets worldwide
- **Multi-Tier Scraping** - RSS with JavaScript-rendered page fallback
- **Anti-Blocking** - UA rotation and stealth measures
- **Semantic Dedup** - ML-based similarity detection
- **Full-Text Search** - PostgreSQL full-text search
- **Keyword Alerts** - Email when articles match keywords
- **Weekly Digests** - Automated digest email
- **Translation** - 20+ languages supported

### Links

- **WebApp**: https://pulseaggregator.com
  
---

## FinPull (Coming Soon)

A unified trading dashboard for stocks, forex, crypto, and futures — charting and technical analysis first, with honest latency labeling on every asset class.

### Tech Stack

# Backend
FastAPI, uvicorn, SQLAlchemy + Alembic, PostgreSQL, slowapi, JWT (pyjwt), WebSocket, Redis (pub/sub)

# Frontend
Next.js, TypeScript


### Key Features

- **Multi-Asset Trading** - Stocks, forex, crypto, and futures in one dashboard
- **Real-time Charts** - Advanced charting and technical analysis
- **Watchlists & Alerts** - Customizable watchlists with automated alerts
- **Live Market Data** - Real-time WebSocket streaming with honest latency labeling
- **WebSocket API** - Low-latency streaming for live ticks and market data

---

## Certus Data (Coming Soon)

A shared platform for a suite of data/content pipeline verification tools. Rather than building five separate apps, every tool is a self-contained module that plugs into one shared backend, one shared database, one shared auth/billing system, and one shared dashboard. Each tool keeps its own landing page and pricing, but shares all underlying infrastructure.

**Tools in the suite:**
- EnrichAudit | Miscalculated engagement rates, stale/misapplied enrichment fields, sentiment-emotion contradictions
- LinguaCheck | Sentiment scores computed with the wrong language model (non-English content scored as if English)
- SourceLock | AI-generated summaries/claims that can't be traced back to real source posts (hallucination check)
- ScrapeWatch | Scrapers silently breaking when a target site's structure changes
- WhyChanged | Plain-English explanations for why a tracked metric shifted
- NuanceBench | Sentiment tools/vendors that fail on sarcasm, slang, and emoji
- FilterGap | Bot/spam mentions slipping through budget-tier listening tools

--- (App Router)

### Tech Stack

# Backend
FastAPI, SQLAlchemy, PostgreSQL (psycopg[binary], alembic), pydantic-settings, PyJWT, bcrypt, python-multipart, email-validator

# Frontend  
Next.js, TypeScript

### Key Features
- **Multi-Tool Platform** - Shared backend, database, auth, and billing across 7 verification tools
- **Tool Router** - Extensible registry for adding new tools as self-contained modules
- **Findings Engine** - Generic write/read layer for analysis results shared by every tool
- **Modular Architecture** - Each tool lives in its own folder with router.py and logic.py
- **Object Storage** - For uploaded datasets (local initially, then S3-compatible)

---
