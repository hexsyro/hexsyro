# What's in My Private Repositories


### SocialIntel
**A dataset marketplace offering pre-enriched, ready-to-use datasets across 100+ social media sources, with custom datasets delivered in 1–3 days.** 🔗 [socialintel.io](https://socialintel.io)

---

### Pulse Aggregator
**A live news-aggregation SaaS pulling from 10,000+ sources via Python crawlers, with a modern Next.js frontend.**

🔗 [pulseaggregator.com](https://pulseaggregator.com)

---

### FinPull *(Coming Soon)*
**A unified trading dashboard for stocks, forex, crypto, and futures — built charting- and technical-analysis-first, with honest latency labeling on every asset class.**

---

### Certus Data *(Coming Soon)*
**A shared platform for a suite of data and content pipeline verification tools.** 

**EnrichAudit** - Detects miscalculated engagement rates, stale or misapplied enrichment fields, and sentiment–emotion contradictions 

**LinguaCheck** - Flags sentiment scores computed with the wrong language model (e.g., non-English content scored as English)

**SourceLock** - Verifies AI-generated summaries and claims trace back to real source posts (hallucination detection)

**ScrapeWatch** - Detects scrapers silently breaking when a target site's structure changes 

**WhyChanged** - Generates plain-English explanations for why a tracked metric shifted 

**NuanceBench** - Evaluates sentiment tools/vendors on sarcasm, slang, and emoji handling 

**FilterGap** - Identifies bot/spam mentions slipping through budget-tier listening tools 

---

## Unified Tech Stack
  
| Category | Technologies | Used In |
|---|---|---|
| **Language** | Python, TypeScript | All products |
| **API Framework** | FastAPI, Uvicorn, slowapi (rate limiting) | All products |
| **Database** | PostgreSQL | All products |
| **ORM / Migrations** | SQLAlchemy, Alembic, `psycopg2-binary` / `psycopg[binary]` | FinPull, Certus Data |
| **Task Scheduling** | APScheduler | SocialIntel, Pulse Aggregator |
| **Web Scraping** | Playwright, cloudscraper, feedparser | SocialIntel, Pulse Aggregator |
| **Auth & Security** | PyJWT, PyOTP, bcrypt, cryptography, python-multipart, email-validator | All products |
| **Real-Time / Messaging** | WebSocket, Redis (pub/sub) | FinPull |
| **HTTP Clients** | httpx, requests, urllib3 | SocialIntel, Pulse Aggregator |
| **Config Management** | pydantic-settings | Certus Data |
| **Frontend Framework** | Next.js (App Router) | All products |
| **Frontend Tooling** | TypeScript, ESLint | All products |
