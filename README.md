# Stock Analysis Dashboard — ADSK vs NOW

**Autodesk, Inc. (ADSK) · ServiceNow, Inc. (NOW)**  
Interactive stock analysis dashboard built with Chart.js · Last updated: **June 24, 2026** · Data as of Jun 23, 2026 close · NOW $95.94 (+3.15%) · ADSK $187.72

[![GitHub](https://img.shields.io/badge/GitHub-Stock--Analysis-blue?logo=github)](https://github.com/mohdkhidir/Stock-Analysis-Autodesk-Inc-and-ServiceNow)

---

## Live Preview

Open `dashboard.html` directly in any browser — no server or build step required.

```
file:///C:/path/to/dashboard.html
```

---

## What's New — June 24, 2026 (data: Jun 23 close)

- **NOW Major Reversal** — NOW closed **$95.94 (+3.15%)** on Jun 23 — massive reversal from $93.01; High $97.50, Low $94.61, Open $95.14; Post-market $96.61 (+0.70%)
- **NOW Volume Surge** — 32.56M shares (8.1× avg) Jun 23; combined with Jun 22's 24.8M = **57.4M shares in 2 days** — historic capitulation/reversal event
- **NOW Net Money Inflow +$49.40M** — Total inflow $422.55M vs outflow $373.15M; all 4 size tiers (XL +$14.4M · L +$6.2M · M +$10.3M · S +$18.5M) net positive
- **NOW Active Buy Dominant** — Active Buy ~22.3M shares (68.4%) vs Active Sell ~10.3M (31.6%); Net Active Buy +12.0M shares
- **NOW Volume Profile POC shifted** — New POC at **$92–96 (28.1M shares)** — largest 30-day concentration zone, replacing old $100–105 POC; strong support base established
- **NEW: Trade Overview section** — Full money flow breakdown by trade size (XL/L/M/S), Active Buy/Sell donut chart, session stats, post-market data
- **NOW Market Cap** — Updated to **$98.94B** (from $95.9B) reflecting Jun 23 close
- **ADSK unchanged** — Still $187.72, RSI 26.00 extreme oversold, new 52-wk low $185.50, Speculative Buy thesis intact

### Previous Update — June 23, 2026
- ADSK new 52-wk low $185.50; NOW $93.01 (-2.14%, 24.8M shares); analyst actions; ADSK RSI 26 extreme oversold

### Previous Update — June 22, 2026
- US Economic Indicators (12), Federal Reserve FOMC Jun 17, Market Indices, Sector Heatmap, Company Logos

---

## Features

### Stock Analysis — ADSK & NOW

#### Chart Controls

| Control | Options |
|---|---|
| **Range** | Daily (May 19–Jun 22) · Weekly (Mar 3–Jun 22, 17 wks) · Hourly (Apr 1–Jun 13, ~385 bars) |
| **Style** | Line · Candlestick · OHLC Bar · Heikin Ashi · Renko |
| **Indicators** | RSI(5) · RSI(10) · RSI(20) · Bollinger Bands · Fibonacci Retracement |

#### Chart Styles

| Style | Description |
|---|---|
| **Line** | Smooth area chart with fill. Best for long-range trend direction. |
| **Candlestick** | OHLC boxes — green bull, red bear. Best for pattern recognition. |
| **OHLC Bar** | Classic open/close tick-mark stems. Compact, institutional style. |
| **Heikin Ashi** | Noise-filtered smoothed candles. Consecutive same-colour = strong trend. |
| **Renko** | ATR-sized price bricks with no time axis. Filters noise, pure price structure. |

> All 5 styles shown as **live mini-chart previews** in the Chart Style Gallery — click to apply instantly.

#### Indicators

- **RSI** — multi-select RSI 5, 10, 20; sub-panel with OB/OS lines at 70/30
- **Bollinger Bands** — BB(10) daily/weekly, BB(20) hourly; translucent channel fill
- **Fibonacci Retracement** — auto-computed 7 levels (0%–100%) from visible period high/low

#### Candle Patterns (Daily · Candlestick or Heikin Ashi)

| Stock | Patterns |
|---|---|
| ADSK | Shooting Star · Bearish Marubozu · Bearish Harami · Doji · Hammer |
| NOW | Bullish Engulfing · Shooting Star · Doji at Top · Evening Doji |

#### Analysis Sections

| Section | Contents |
|---|---|
| **Snapshot Cards** | Live price, market cap, P/E, revenue, analyst rating, PT, net inflow — with company logos |
| **Pro Chart** | Candlestick + volume + RSI(14) integrated pro view with Volume Profile sidebar |
| **Chart Style Gallery** | 5 live mini-chart previews |
| **Support & Resistance** | Daily + Weekly S/R levels with colour-coded badges |
| **Volume Profile** | 30-day POC, HVN, LVN bar charts + written analysis (NOW POC updated to $92–96) |
| **Trade Overview** | Money flow by size (XL/L/M/S), Active Buy/Sell donut, session & post-market stats |
| **Technical Analysis** | MA, VWAP, RSI, MACD, ADX comparison table with Tippy.js tooltips |
| **Fundamental Analysis** | Revenue, margins, guidance, AI monetization head-to-head |
| **Corporate Actions** | Chronological event log with SEC source links |
| **Analyst Ratings** | Consensus, price targets, buy/hold/sell ratios with animated progress bars |
| **Valuation** | P/E, EV/Rev, FCF yield, gross margin side-by-side |
| **Verdict & Scorecard** | Star ratings and action plans |

---

### US Economic Indicators (NEW)

12 indicators sourced from Census Bureau, BLS, BEA, and the Federal Reserve — all with quarterly history from Q1 2021 to Q2 2026.

| Indicator | Source | ★ Impact |
|---|---|---|
| GDP Growth Rate | BEA | ★★★★★ |
| CPI Inflation | BLS | ★★★★★ |
| Unemployment Rate | BLS | ★★★★★ |
| Non-Farm Payrolls | BLS | ★★★★★ |
| Fed Funds Rate | Federal Reserve | ★★★★★ |
| Retail Sales | Census Bureau | ★★★★ |
| Consumer Confidence | Conference Board | ★★★★ |
| Industrial Production | Federal Reserve | ★★★★ |
| Housing Starts | Census Bureau | ★★★ |
| Building Permits | Census Bureau | ★★★ |
| Trade Balance | Census / BEA | ★★★ |
| Durable Goods Orders | Census Bureau | ★★★ |

**Graph View** — click any indicator button to render its bar chart with trend color coding.  
**Table View** — sortable by any column (click header) · filterable by text, star rating, and trend direction · click row to view chart.

---

### Federal Reserve Section (NEW)

- **Jun 17, 2026 FOMC Decision** — Hold at 3.50–3.75% (12–0 unanimous) · Chair Kevin Warsh's first meeting
- **Rate History Chart** — Full cycle from 0.25% floor (2021) → 5.5% peak (Jul 2023) → 3.75% hold (Jun 2026)
- **Hawkish Shift** — Dot plot flipped: 17/18 officials see upside inflation risk; median now implies hike by end-2026
- **Executive Summary** — Stagflation-lite (GDP 1.6%, CPI 4.2%, Consumer Confidence 48.9), markets still at ATH on AI thesis

---

### Major Market Indices (NEW)

KPI cards with current level, daily change, YTD, 1-year, and since-Q1-2021 returns.

| Index | Level (Jun 22) | Daily Chg | YTD | Since Q1'21 |
|---|---|---|---|---|
| S&P 500 | 7,472 | -0.37% | +14.2% | +102% |
| NASDAQ | 26,167 | -1.32% (Big Tech drag) | +39.1% | +106% |
| DJIA | 51,713 | +0.29% | +20.1% | +67% |
| FTSE 100 | 10,364 | -0.34% (Jun 19) | +10.0% | +58% |

Normalized performance chart (base 100 = Q1 2021) with key event annotations (CPI peak, rate peak, rate cuts).

---

### Sector Heatmap (NEW)

Color-coded grid of all 11 S&P 500 sectors with:
- YTD return (%) and market cap weighting
- Representative company logo (NVIDIA, JPMorgan, Exxon, Meta, Amazon, etc.)
- Horizontal ranked bar chart view
- Color scale: strong green (>10%) → yellow (flat) → strong red (<-8%)

| Sector | YTD | Wt |
|---|---|---|
| Energy (XLE) | +12.4% | 4.2% |
| Healthcare (XLV) | +11.2% | 12.8% |
| Financials (XLF) | +8.9% | 13.1% |
| Utilities (XLU) | +6.3% | 2.5% |
| Industrials (XLI) | +4.5% | 8.5% |
| Consumer Staples (XLP) | +3.8% | 6.0% |
| Comm. Services (XLC) | +2.1% | 8.7% |
| Real Estate (XLRE) | +2.0% | 2.3% |
| Materials (XLB) | -1.8% | 2.4% |
| Consumer Disc. (XLY) | -5.2% | 10.0% |
| Technology (XLK) | -8.5% | 29.5% |

---

### Company Logos

Logos loaded via **Google Favicon Service** (`google.com/s2/favicons`) — no API key required, always accessible. Applied in:
- Navbar brand bar
- ADSK & NOW snapshot cards
- Pro chart headers
- Verdict section titles
- S&P 500 / NASDAQ / DJIA / FTSE 100 index cards
- Federal Reserve decision card
- Census Bureau / BLS / BEA section header
- All 11 sector heatmap cells

---

### UI/UX

- Dark / Light mode toggle (persists via `localStorage`)
- Scroll-to-zoom + drag-to-pan on all price charts with Reset button
- Scroll progress bar · Back-to-top button · Section jump nav (14 sections)
- AOS scroll-in animations · CountUp animated number counters
- Tippy.js tooltips on RSI, MACD, EMA, SMA, VWAP, cRPO
- Live pulse dot on date badge · Sticky navbar with blur backdrop
- Fully responsive — Bootstrap 5.3 · Custom scrollbar

---

## Key Findings — June 24, 2026 (data: Jun 23 close)

| | ADSK | NOW |
|---|---|---|
| **Price (Jun 23 close)** | **$187.72** (Jun 22 unchanged) | **$95.94** ↑ (+3.15%) — major reversal |
| **Jun 23 Session** | Pre-market $190.00 (+1.21%) | Open $95.14 · High $97.50 · Low $94.61 |
| **Post-Market** | — | $96.61 (+0.70%) · Vol 2.11M |
| **52-Wk Range** | **$185.50** – $329.09 (52-wk low $185.50) | $81.24 – $211.48 |
| **Market Cap** | $39.6B | **$98.94B** |
| **P/E (TTM)** | **27.42×** | 55.37× |
| **Forward P/E** | **14.56×** | 21.45× |
| **RSI (14)** | **26.00 — EXTREME OVERSOLD** | ~42 (recovering) |
| **Volume Jun 23** | 4.6M (Jun 22 exhaustion) | **32.56M (8.1× avg — reversal)** |
| **Net Money Flow** | — | **+$49.40M** (In $422.55M / Out $373.15M) |
| **Active Buy/Sell** | — | Buy 68.4% (22.3M) vs Sell 31.6% (10.3M) |
| **Volume Profile POC** | $215–220 (9.3M — overhead) | **$92–96 (28.1M — new support base)** |
| **Rating** | ⭐⭐⭐⭐ 4.0/5 | ⭐⭐⭐⭐ 4.0/5 |
| **Recommendation** | **Speculative Buy — RSI 26 Extreme Oversold · Entry $185–192** | **Speculative Buy — Reversal Confirmed · Watch $97.50–$98 reclaim** |
| **Avg PT (12M)** | $318.53 (+69.7%) · 34 analysts | $141.98 (+47.9% from $95.94) · 48 analysts |
| **Buy/Hold/Sell** | 31 Buy / 3 Hold / 0 Sell (91.2%) | 43 Buy / 4 Hold / 1 Sell (89.6%) |
| **Technical** | 🔴 Bearish — RSI 26 extreme oversold · all MAs bearish | 🟡 Recovering — massive vol reversal · next: reclaim $98–100 |
| **Next Catalyst** | MaintainX integration update | **Jul 22, 2026 — Q2 FY26 Earnings** |

---

## Tech Stack

| Library | Version | Purpose |
|---|---|---|
| Chart.js | 4.4.3 | Core charting engine |
| CandlePlugin | custom | Candlestick / OHLC / Heikin Ashi (native canvas, no external dep) |
| chartjs-plugin-annotation | 3.0.1 | Event lines, Fib levels, candle pattern boxes, S/R zones |
| chartjs-plugin-zoom | 2.0.1 | Scroll-to-zoom + drag-to-pan (Hammer.js 2.0.8) |
| Bootstrap | 5.3.3 | Responsive layout, dark/light `data-bs-theme` |
| FontAwesome | 6.5.0 | Icons throughout |
| AOS | 2.3.4 | Scroll-triggered fade animations |
| Tippy.js | 6 | Rich indicator tooltips |
| CountUp.js | 2.8.0 | Animated number counters |
| Google Favicon API | — | Company & index logos (no API key) |

All dependencies via CDN — no `npm install` or build step needed.

> **CandlePlugin Note:** `chartjs-chart-financial` (v0.2.x) was removed — built for Chart.js 3.x, crashed on 4.4.3. Replaced with a self-contained `afterDatasetsDraw` plugin drawing directly on canvas 2D API.

---

## Files

```
├── dashboard.html        # Full interactive dashboard — open directly in browser
├── CLAUDE.md             # Comprehensive markdown analysis — all data tables, S/R, candle patterns, VP
├── README.md             # This file
└── Image/
    ├── NOW - 23June261.png   # Trade Overview (price, money flow, inflow/outflow by size)
    ├── NOW - 23June262.png   # Volume Profile & Active Buy/Sell table (upper)
    ├── NOW - 23June263.png   # Volume Profile & Active Buy/Sell table (middle)
    └── NOW - 23June264.png   # Volume Profile & Active Buy/Sell table (lower)
```

---

## Data Sources

| Source | URL |
|---|---|
| StockAnalysis ADSK | https://stockanalysis.com/stocks/adsk/ |
| StockAnalysis NOW | https://stockanalysis.com/stocks/now/ |
| Yahoo Finance ADSK | https://finance.yahoo.com/quote/ADSK/ |
| Yahoo Finance NOW | https://finance.yahoo.com/quote/NOW/ |
| ADSK SEC Filings | https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000769397 |
| NOW SEC Filings | https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001373715 |
| ADSK Q1 FY27 Earnings | https://www.sec.gov/Archives/edgar/data/0000769397/000076939726000041/q127pressrelease.htm |
| ADSK MaintainX 8-K | https://www.sec.gov/Archives/edgar/data/0000769397/000121390026062125/ea029248301ex99-1.htm |
| NOW Q1 FY26 Earnings | https://www.sec.gov/Archives/edgar/data/0001373715/000137371526000054/erq1fy26.htm |
| Barchart ADSK Technical | https://www.barchart.com/stocks/quotes/ADSK/technical-analysis |
| Barchart NOW Technical | https://www.barchart.com/stocks/quotes/NOW/technical-analysis |
| WallStreetZen ADSK | https://www.wallstreetzen.com/stocks/us/nasdaq/adsk/stock-forecast |
| StockAnalysis NOW Ratings | https://stockanalysis.com/stocks/now/ratings/ |
| Census Bureau Economic Indicators | https://www.census.gov/economic-indicators/ |
| Bureau of Labor Statistics | https://www.bls.gov/ |
| Bureau of Economic Analysis | https://www.bea.gov/ |
| Federal Reserve FOMC | https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm |
| Fed Jun 17 Decision | https://www.federalreserve.gov/newsevents/pressreleases/monetary20260617a.htm |
| ADSK 52-Wk Low | https://www.investing.com/news/company-news/autodesk-stock-hits-52week-low-at-19142-usd-93CH-4750581 |
| NOW Restructuring Drop | https://tradersunion.com/news/financial-news/show/2395960-servicenow-drops-4-53percent-to-usd96-74/ |
| ServiceNow IR | https://investor.servicenow.com/stock-info/default.aspx |

---

> **Disclaimer:** For informational and educational purposes only. Not financial advice. All data sourced from publicly available filings and financial data providers. ADSK price as of June 22, 2026 close; NOW price as of June 23, 2026 close. Money flow, active buy/sell, and volume profile data sourced from moomoo platform screenshots (Jun 23, 2026). Price data includes synthetically generated intra-period points for visualization. Always conduct independent due diligence before making investment decisions.
