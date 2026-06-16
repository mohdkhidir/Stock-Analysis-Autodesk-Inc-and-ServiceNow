# Stock Analysis Dashboard — ADSK vs NOW

**Autodesk, Inc. (ADSK) · ServiceNow, Inc. (NOW)**  
Interactive stock analysis dashboard built with Chart.js · Prices last updated: June 16, 2026

---

## Live Preview

Open `dashboard.html` directly in any browser — no server or build step required.

---

## Features

### Chart Controls

| Control | Options |
|---|---|
| **Range** | Daily (May 19–Jun 13) · Weekly (Mar 3–Jun 13, 15 wks) · Hourly (Apr 1–Jun 13, ~385 bars) |
| **Style** | Line · Candlestick · OHLC Bar · Heikin Ashi · Renko |
| **Indicators** | RSI(5) · RSI(10) · RSI(20) · Bollinger Bands · Fibonacci Retracement |

### Chart Styles

| Style | Description |
|---|---|
| **Line** | Smooth area chart with fill. Best for long-range trend direction. |
| **Candlestick** | OHLC boxes — green bull, red bear. Best for pattern recognition. |
| **OHLC Bar** | Classic open/close tick-mark stems. Compact, institutional style. |
| **Heikin Ashi** | Noise-filtered smoothed candles (`haO=(prevO+prevC)/2`, `haC=(O+H+L+C)/4`). Consecutive same-colour = strong trend. |
| **Renko** | ATR-sized price bricks with no time axis. Filters noise, shows pure price structure. |

> All 5 styles are shown as **live mini-chart previews** in the Chart Style Gallery — click any card to instantly apply the style to both main charts.

### Indicators Detail

- **RSI** — multi-select (RSI 5, 10, 20 can all be active simultaneously); sub-panel below each chart with overbought (70) and oversold (30) reference lines
- **Bollinger Bands** — BB(10) on daily/weekly, BB(20) on hourly; upper/middle/lower bands with translucent channel fill
- **Fibonacci Retracement** — auto-computed from the visible period's high/low; 7 levels annotated (0%, 23.6%, 38.2%, 50%, 61.8%, 78.6%, 100%)

### Candle Patterns (Daily · Candlestick or Heikin Ashi mode)

| Stock | Patterns Annotated |
|---|---|
| ADSK | Shooting Star · Bearish Marubozu · Bearish Harami · Doji (Exhaustion) · Hammer (Potential Reversal) |
| NOW | Bullish Engulfing · Shooting Star (Pause) · Doji at Top · Shooting Star (OB Warning) · Evening Doji |

Overbought ($105–108) and oversold ($188–196) zone bands also drawn.

### Analysis Sections

- **Chart Style Gallery** — 5 live mini-chart previews, clickable to apply style; syncs bidirectionally with toolbar
- **Support & Resistance card** — Daily + Weekly S/R levels for both stocks with colour-coded badges
- **Volume Profile** — 30-day POC, HVN, LVN charts with written description + summary findings per stock
- **Technical Analysis table** — EMA, SMA, VWAP, RSI, MACD, volume trend comparison with Tippy.js tooltips
- **Fundamental Analysis** — Revenue, margins, guidance, AI monetization head-to-head
- **Corporate Finance Actions** — Chronological event log with SEC source links
- **Analyst Ratings** — Consensus, price targets, buy/hold/sell ratios with animated progress bars
- **Valuation Comparison** — P/E, EV/Rev, FCF yield, gross margin side-by-side
- **Verdict & Scorecard** — Star ratings and action plans for both stocks

### UI/UX

- Dark / Light mode toggle with smooth CSS variable transitions (persists via `localStorage`)
- Scroll-to-zoom + drag-to-pan on all price charts; Reset button per chart
- Scroll progress bar at top · Back-to-top floating button · Section jump nav
- AOS scroll-in animations · CountUp animated numbers on key metrics
- Tippy.js rich tooltips on RSI, MACD, EMA, SMA, VWAP, cRPO badges
- Live pulse dot on date badge · Sticky navbar with blur backdrop
- Fully responsive (Bootstrap 5.3) · Custom scrollbar

---

## Key Findings (Updated Jun 16, 2026)

| | ADSK | NOW |
|---|---|---|
| Price | $191.29 ↓ -3.47% (Jun 16 est.) | $104.27 ↑ +2.10% (Jun 15) |
| Market Cap | $50.5B | $107.5B |
| Rating | ⭐⭐⭐⭐ 4.0/5 | ⭐⭐⭐⭐ 4.2/5 |
| Recommendation | **Speculative Buy — Accumulate on Weakness** | **Buy / Hold — Momentum Play** |
| Avg 12M Analyst Target | $315.00 (+64.7% upside) | $146.00 (+40.0% upside) |
| High / Low PT | $385 (Barclays) / $262 (BMO) | $236 (Bernstein) / $100 |
| Technical Signal | 🔴 Bearish — below all MAs | 🟢 Bullish — above VWAP & short-term MAs |
| Volume Profile | Distribution — POC $215–220 acts as overhead resistance | Accumulation — trading inside POC $100–105 |

### Current Support & Resistance

**ADSK** — Daily: S2 $188 (major) · S3 $180 (extreme) · R1 $203–205 · R2 $215–220 (VWAP + POC)  
**NOW** — Daily: S1 $98–100 (VWAP + HVN) · R1 $105–108 (VAH) · R2 $115 (measured move target)

### Latest Analyst Actions (Jun 2026)

| Firm | Stock | Rating | PT | Move |
|---|---|---|---|---|
| Barclays | ADSK | Overweight | $385 | ↑ from $355 |
| RBC Capital | ADSK | Outperform | $305 | ↓ from $335 |
| BMO Capital | ADSK | Market Perform | $262 | ↓ from $279 |
| Bernstein | NOW | Outperform | $236 | ↑ from $226 |
| Morgan Stanley | NOW | Overweight | $263 | ↑ from split-adj prior |

---

## Tech Stack

| Library | Version | Purpose |
|---|---|---|
| Chart.js | 4.4.3 | Core charting engine |
| CandlePlugin | custom | Candlestick / OHLC / Heikin Ashi (native canvas plugin — no external dep) |
| chartjs-plugin-annotation | 3.0.1 | Event lines, Fib levels, candle pattern boxes, S/R zone bands |
| chartjs-plugin-zoom | 2.0.1 | Scroll-to-zoom + drag-to-pan (requires Hammer.js 2.0.8) |
| Bootstrap | 5.3.3 | Responsive layout, dark/light `data-bs-theme` |
| FontAwesome | 6.5.0 | Icons throughout |
| AOS | 2.3.4 | Scroll-triggered fade animations |
| Tippy.js | 6 | Rich indicator tooltips |
| CountUp.js | 2.8.0 | Animated number counters on prices/targets |

All dependencies loaded via CDN — no `npm install` or build step needed.

> **Note on CandlePlugin:** `chartjs-chart-financial` (v0.2.x) was removed because it was built for Chart.js 3.x and corrupted the controller registry on load with Chart.js 4.4.3. The replacement is a self-contained `afterDatasetsDraw` plugin that draws candlestick/OHLC/HA shapes directly on the canvas using the 2D API, with zero external dependencies.

---

## Files

```
├── dashboard.html   # Full interactive dashboard (single HTML file, open directly in browser)
├── CLAUDE.md        # Comprehensive markdown analysis — all data tables, S/R, candle patterns, VP findings
└── README.md        # This file
```

---

## Data Sources

| Source | Link |
|---|---|
| StockAnalysis ADSK | https://stockanalysis.com/stocks/adsk/ |
| StockAnalysis NOW | https://stockanalysis.com/stocks/now/ |
| ADSK SEC Filings | https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000769397 |
| NOW SEC Filings | https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001373715 |
| ADSK Q1 FY27 Earnings | https://www.sec.gov/Archives/edgar/data/0000769397/000076939726000041/q127pressrelease.htm |
| ADSK MaintainX 8-K | https://www.sec.gov/Archives/edgar/data/0000769397/000121390026062125/ea029248301ex99-1.htm |
| NOW Q1 FY26 Earnings | https://www.sec.gov/Archives/edgar/data/0001373715/000137371526000054/erq1fy26.htm |
| Barclays ADSK PT | https://www.tipranks.com/news/the-fly/autodesk-price-target-raised-to-385-from-355-at-barclays-thefly |
| RBC Capital ADSK PT | https://finance.yahoo.com/news/rbc-capital-lowers-price-target-153950473.html |
| Barchart ADSK Technical | https://www.barchart.com/stocks/quotes/ADSK/technical-analysis |
| TipRanks ADSK | https://www.tipranks.com/stocks/adsk/forecast |
| WallStreetZen ADSK | https://www.wallstreetzen.com/stocks/us/nasdaq/adsk/stock-forecast |
| StockAnalysis NOW Ratings | https://stockanalysis.com/stocks/now/ratings/ |
| Bernstein / Yahoo Finance | https://finance.yahoo.com/markets/stocks/articles/bernstein-raises-price-target-servicenow-101343680.html |
| ServiceNow IR | https://investor.servicenow.com/stock-info/default.aspx |

---

> **Disclaimer:** For informational and educational purposes only. Not financial advice. Price data includes synthetically generated intra-period points for visualization. Always conduct independent due diligence before making investment decisions.
