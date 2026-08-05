# Here are my Private Repository Projects

# Social Intel

A dataset marketplace that offers pre-enriched ready datasets across 100+ social media sources and builds custom datasets automatically within 1-3 days.

[![Social Intel](https://socialintel.io/logo.png)](https://socialintel.io)

## 🚀 Tech Stack

# Backend
FastAPI ✓, PostgreSQL (psycopg2-binary) ✓, APScheduler ✓, playwright ✓, cloudscraper ✓, feedparser ✓  
cryptography ✓, pyjwt ✓, pyotp ✓, httpx ✓, requests ✓, urllib3 ✓, Python >=3.11 ✓

# Frontend  
Next.js ✓, TypeScript ✓, React 18 ✓, Tailwind CSS ✓, Vercel Analytics ✓, eslint ✓

# Testing
pytest ✓, playwright (frontend) ✓, ruff ✓

## 📊 Key Features

- **100+ Platform Integrations** - Covers all major social media platforms
- **Pre-enriched Datasets** - High-quality, ready-to-use datasets with quality scoring
- **Custom Dataset Builder** - 1-3 day turnaround for custom requests
- **Background Workers** - Auto-scaling architecture with task automation
- **Enterprise Security** - JWT authentication, OAuth 2.0, role-based access
- **Scalable API Architecture** - Designed for concurrent high-volume requests

## 🔗 Links

- **WebApp**: https://socialintel.io

---

### [Pulse Aggregator](https://www.pulseaggregator.com)
A news aggregation platform that scrap news from 10K+ sources hourly.

Backend (Python):
  FastAPI web framework
  PostgreSQL with asyncpg
  APScheduler for task automation
  Web scraping: camoufox, cloudscraper, lxml, playwright, feedparser
  Machine learning: scikit-learn, sentence-transformers
  Security: cryptography, pyjwt, pyotp
  HTTP: httpx, requests, urllib3
  Python 3.12+

Frontend (Next.js/React):
  Next.js framework
  TypeScript

Other Tools:
  Testing: pytest, jest
  Linter: ruff, eslint

---

### [GoodQuote Scraper](https://github.com/hexsyro/Goodreads-quote-scraper)
Production Goodreads scraper → **structured CSV/JSON datasets** (quotes, authors, tags).

`BeautifulSoup` `Pagination` `Data validation` `Multi-page`

---

### [FinPull](https://finpull.app) *(Upcoming)*
**Financial data pipeline** pulling OHLCV, earnings, P/E ratios, and analyst ratings into structured datasets.

Backend:
Python 3.x
FastAPI (REST API framework)
uvicorn (ASGI server)
SQLAlchemy + Alembic (ORM + migrations)
PostgreSQL database

Frontend:
Next.js (App Router)
TypeScript

Other Key Components:
WebSocket streaming
Redis (pub/sub bus)
slowapi (rate limiting)

---

## Production Tech Stack

| Layer | Tools |
|---|---|
| **Scraping** | Playwright · BeautifulSoup · Asyncio · Proxy rotation |
| **Data** | Pandas · NumPy · Parquet/JSONL exports |
| **Backend** | FastAPI · PostgreSQL · APScheduler · JWT |
| **Frontend** | Next.js 15 · Tailwind · TypeScript |
| **Infra** | Vultr · Vercel · Supabase · Docker |

**freeCodeCamp Certified**: Responsive Web Design (Mar 2024) · Scientific Computing with Python (Nov 2025)
