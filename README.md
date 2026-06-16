# Stock Analysis Dashboard — ADSK vs NOW

**Autodesk, Inc. (ADSK) · ServiceNow, Inc. (NOW)**  
Interactive stock analysis dashboard built with Chart.js · Analysis date: June 15, 2026

---

## Live Preview

Open `dashboard.html` directly in any browser — no server or build step required.

---

## Features

### Chart Controls
| Control | Options |
|---|---|
| **Range** | Daily (May 19–Jun 13) · Weekly (Mar 3–Jun 13, 15 wks) · Hourly (Apr 1–Jun 13, ~385 bars) |
| **Style** | Line · Candlestick · OHLC Bar |
| **Indicators** | RSI(5) · RSI(10) · RSI(20) · Bollinger Bands · Fibonacci Retracement |

### Indicators Detail
- **RSI** — multi-select (all three periods can show simultaneously); sub-panel below each chart with overbought (70) and oversold (30) reference lines
- **Bollinger Bands** — BB(10) on daily/weekly, BB(20) on hourly; upper/middle/lower bands with translucent fill
- **Fibonacci Retracement** — auto-computed from the period's high/low; 7 levels annotated (0%, 23.6%, 38.2%, 50%, 61.8%, 78.6%, 100%)

### Candle Patterns (Daily + Candlestick/OHLC mode)
| Stock | Patterns Annotated |
|---|---|
| ADSK | Shooting Star · Bearish Marubozu · Bearish Harami · Doji (Exhaustion) · Hammer (Reversal) |
| NOW | Bullish Engulfing · Shooting Star · Doji at Top · Evening Doji |

### Additional Sections
- **Support & Resistance card** — Daily and Weekly S/R levels for both stocks with badge classifications
- **Volume Profile** — 30-day POC, HVN, LVN analysis with written summary findings per stock
- **Technical Analysis table** — EMA, SMA, VWAP, RSI, MACD, volume trend comparison
- **Fundamental Analysis** — Revenue, margins, guidance, AI monetization head-to-head
- **Corporate Finance Actions** — Chronological event log with SEC source links
- **Analyst Ratings** — Consensus, price targets, buy/hold/sell ratios with animated progress bars
- **Valuation Comparison** — P/E, EV/Rev, FCF yield, gross margin side-by-side
- **Verdict & Scorecard** — Star ratings and action plans for both stocks

### UI/UX
- Dark / Light mode toggle (persists via localStorage)
- Scroll-to-zoom + drag-to-pan on all price charts
- AOS scroll animations · CountUp animated numbers
- Tippy.js tooltips on technical indicator badges (RSI, MACD, VWAP, EMA, cRPO)
- Scroll progress bar · Back-to-top button · Section jump nav
- Fully responsive (Bootstrap 5.3)

---

## Key Findings (June 15, 2026)

| | ADSK | NOW |
|---|---|---|
| Price | $198.43 ↓ -0.31% | $102.13 ↑ +0.90% |
| Market Cap | $52.4B | $105.2B |
| Rating | ⭐⭐⭐⭐ 4.0/5 | ⭐⭐⭐⭐ 4.2/5 |
| Recommendation | **Speculative Buy — Accumulate on Weakness** | **Buy / Hold — Momentum Play** |
| 12M Analyst Target | $319.27 (+60.9% upside) | $149.62 (+46.5% upside) |
| Technical Signal | 🔴 Bearish — below all MAs | 🟢 Bullish — above VWAP & short-term MAs |
| Volume Profile | Distribution — POC at $215–220 (overhead) | Accumulation — trading at POC $100–105 |

### Current Support & Resistance

**ADSK** · Daily: S1 $193–196 · S2 $188 · R1 $203–205 · R2 $215–220 (VWAP + POC)  
**NOW** · Daily: S1 $98–100 (VWAP + HVN) · R1 $105–108 (VAH) · R2 $115 (measured move)

---

## Tech Stack

| Library | Version | Purpose |
|---|---|---|
| Chart.js | 4.4.3 | Core charting engine |
| chartjs-chart-financial | 0.2.1 | Candlestick / OHLC chart types |
| chartjs-plugin-annotation | 3.0.1 | Event lines, Fib levels, pattern boxes |
| chartjs-plugin-zoom | 2.0.1 | Scroll-to-zoom + pan (requires Hammer.js) |
| Bootstrap | 5.3.3 | Layout, dark/light theme |
| FontAwesome | 6.5.0 | Icons |
| AOS | 2.3.4 | Scroll animations |
| Tippy.js | 6 | Indicator tooltips |
| CountUp.js | 2.8.0 | Animated number counters |

All dependencies loaded via CDN — no `npm install` needed.

---

## Files

```
├── dashboard.html   # Full interactive dashboard (single-file, no build step)
├── CLAUDE.md        # Comprehensive markdown analysis with all data tables
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
| Barchart ADSK Technical | https://www.barchart.com/stocks/quotes/ADSK/technical-analysis |
| TipRanks ADSK | https://www.tipranks.com/stocks/adsk/forecast |
| WallStreetZen ADSK | https://www.wallstreetzen.com/stocks/us/nasdaq/adsk/stock-forecast |
| StockAnalysis NOW Ratings | https://stockanalysis.com/stocks/now/ratings/ |

---

> **Disclaimer:** For informational and educational purposes only. Not financial advice. Price data includes synthetically generated intra-period points for visualization. Always conduct independent due diligence before making investment decisions.
