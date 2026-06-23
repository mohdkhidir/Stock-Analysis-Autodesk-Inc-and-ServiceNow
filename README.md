# Stock Analysis Dashboard — ADSK vs NOW

**Autodesk, Inc. (ADSK) · ServiceNow, Inc. (NOW)**  
Interactive stock analysis dashboard built with Chart.js · Last updated: **June 23, 2026** · Data as of Jun 22, 2026 close · Jun 23 pre-market: ADSK $190.00 (+1.21%), NOW $94.36 (+1.45%)

[![GitHub](https://img.shields.io/badge/GitHub-Stock--Analysis-blue?logo=github)](https://github.com/mohdkhidir/Stock-Analysis-Autodesk-Inc-and-ServiceNow)

---

## Live Preview

Open `dashboard.html` directly in any browser — no server or build step required.

```
file:///C:/path/to/dashboard.html
```

---

## What's New — June 23, 2026

- **Price Update** — ADSK **$187.72** (new 52-wk low $185.50 hit Jun 22, RSI 26.00 / RSI-9 20.24 extreme oversold) · NOW **$93.01** (-2.14%, 24.8M shares, approaching $90–92 support)
- **ADSK new 52-wk low** — $185.50 intraday Jun 22; closed $187.72 (-3.15%); ADX 39.43 strong downtrend; volume 4.6M (exhaustion signal); pre-market Jun 23: $190.00 (+1.21%)
- **NOW continued decline** — $93.01 Jun 22 close; 24.8M shares (5.2× avg sustained); RSI 39.25 approaching oversold; Jul 22 earnings upcoming
- **New analyst actions** — Exane BNP Paribas initiated ADSK Buy/$295; Citi maintained ADSK Hold/$252; Benchmark raised NOW to $130; BofA initiated NOW Buy/$130
- **Market indices updated** — S&P 500 7,472 (-0.37%), NASDAQ 26,167 (-1.32% Big Tech drag), DJIA 51,713 (+0.29%) as of Jun 22
- **Charts extended** — Jun 22 daily and weekly bars added; ADSK RSI extreme oversold zone visible
- **Upside recalculated** — ADSK +69.7% to avg PT; NOW +52.7% to avg PT (from new lower prices)
- **NOW analyst mix updated** — 43 Buy / 4 Hold / 1 Sell (89.6% buy ratio); 1 Strong Sell added

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
| **Snapshot Cards** | Live price, market cap, P/E, revenue, analyst rating, PT — with company logos |
| **Pro Chart** | Candlestick + volume + RSI(14) integrated pro view with Volume Profile sidebar |
| **Chart Style Gallery** | 5 live mini-chart previews |
| **Support & Resistance** | Daily + Weekly S/R levels with colour-coded badges |
| **Volume Profile** | 30-day POC, HVN, LVN bar charts + written analysis |
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
- Scroll progress bar · Back-to-top button · Section jump nav (13 sections)
- AOS scroll-in animations · CountUp animated number counters
- Tippy.js tooltips on RSI, MACD, EMA, SMA, VWAP, cRPO
- Live pulse dot on date badge · Sticky navbar with blur backdrop
- Fully responsive — Bootstrap 5.3 · Custom scrollbar

---

## Key Findings — June 23, 2026

| | ADSK | NOW |
|---|---|---|
| **Price (Jun 22 close)** | **$187.72** ↓ (-3.15%) | **$93.01** ↓ (-2.14%) |
| **Pre-market Jun 23** | $190.00 (+1.21%) | $94.36 (+1.45%) |
| **52-Wk Range** | **$185.50** – $329.09 (**new 52-wk low Jun 22!**) | $81.24 – $211.48 |
| **Market Cap** | $39.6B | $95.9B |
| **P/E (TTM)** | **27.42×** | 55.37× |
| **Forward P/E** | **14.56×** | 21.45× |
| **RSI (14)** | **26.00 — EXTREME OVERSOLD** | 39.25 — approaching oversold |
| **RSI (9)** | **20.24 — extreme oversold** | 31.86 |
| **ADX (9)** | 39.43 (strong downtrend) | 25.50 (downtrend) |
| **Volume Jun 22** | 4.6M (~1.8× avg — exhaustion signal) | 24.8M (5.2× avg — sustained distribution) |
| **Rating** | ⭐⭐⭐⭐ 4.0/5 | ⭐⭐⭐⭐ 4.0/5 |
| **Recommendation** | **Speculative Buy — RSI 26 Extreme Oversold · Entry $185–192** | **Hold — Approaching $90–93 Support · Watch Jul 22 Earnings** |
| **Avg PT (12M)** | $318.53 (+69.7%) · 34 analysts | $141.98 (+52.7%) · 48 analysts |
| **Buy/Hold/Sell** | 31 Buy / 3 Hold / 0 Sell (91.2%) | 43 Buy / 4 Hold / 1 Sell (89.6%) |
| **Technical** | 🔴 Bearish — new 52-wk low · all MAs bearish | 🔴 Bearish — below all MAs · approaching $90–92 |
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
├── dashboard.html   # Full interactive dashboard — open directly in browser
├── CLAUDE.md        # Comprehensive markdown analysis — all data tables, S/R, candle patterns, VP
└── README.md        # This file
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

> **Disclaimer:** For informational and educational purposes only. Not financial advice. All data sourced from publicly available filings and financial data providers as of June 23, 2026 (prices as of June 22, 2026 close; June 23 pre-market included). Price data includes synthetically generated intra-period points for visualization. Always conduct independent due diligence before making investment decisions.
