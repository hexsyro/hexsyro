# Hi, I'm Heshan 👨‍💻

[![Pulse Aggregator](https://img.shields.io/badge/PulseAggregator-10K+%20Sources-0a84ff?style=for-the-badge&logo=news)](https://pulseaggregator.com)
[![Social Intel](https://img.shields.io/badge/SocialIntel-100%2B%20Platforms-0066cc?style=for-the-badge&logo=data)](https://socialintel.io)
[![FinPull](https://img.shields.io/badge/FinPull-Coming%20Soon-f0a500?style=for-the-badge&logo=chart-line)](https://finpull.dev)

---

## Featured Projects

### [Social Intel](https://socialintel.io)
**Custom + pre-enriched social media datasets** — pick platforms and keywords, we collect, enrich, and deliver in CSV/JSON/JSONL/Parquet.

Enrichment is fully deterministic (no LLM) — sentiment, topics, financial signals, bot detection, 250+ fields per post, 25 quality checks.

**Custom datasets delivered in 1–3 days** from **$9** (10K–25K rows). Free catalog for datasets under 10K rows, free 100-row samples, no signup needed.

`FastAPI` `PostgreSQL` `Next.js` `Playwright` `PayPal` `AWS S3` `VADER Lexicon`

[![Demo](https://img.shields.io/badge/Watch%20Demo-🚀-00d2d3)](https://youtu.be/r6EkmOJcg8E?si=YCoAs1uwM16Ae_rA)

---

### [Pulse Aggregator](https://www.pulseaggregator.com)
**Production news platform** indexing **100000+ articles per week from 10,000+ news sources updated hourly.**

**4-tier RSS fallback** → Playwright scraper (paywalls) → hourly APScheduler → **full-text search + REST API**

![Articles](https://img.shields.io/badge/10,000%2B-articles%2Fweek-brightgreen?style=flat-square)
![Sources](https://img.shields.io/badge/10,000%2B-sources-blue?style=flat-square)
![Uptime](https://img.shields.io/badge/99.9%25-uptime-success?style=flat-square)

`FastAPI` `PostgreSQL` `Playwright` `Next.js` `APScheduler`

[![Demo](https://img.shields.io/badge/Watch%20Demo-🔥-ff4757)](https://youtu.be/McLvQCSXJsU?si=A6glq0tg1zJAX5IE)

---

### [GoodQuote Scraper](https://github.com/hexsyro/Goodreads-quote-scraper)
Production Goodreads scraper → **structured CSV/JSON datasets** (quotes, authors, tags).

`BeautifulSoup` `Pagination` `Data validation` `Multi-page`

---

### [FinPull](https://finpull.dev) *(Upcoming)*
**Financial data pipeline** pulling OHLCV, earnings, P/E ratios, and analyst ratings into structured datasets.

Playwright + yfinance → FastAPI → PostgreSQL → **REST API + Next.js dashboard**

`Playwright` `yfinance` `FastAPI` `PostgreSQL` `Next.js`

**Target**: Traders · Analysts · Portfolio dashboards

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
