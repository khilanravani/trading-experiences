# Quantitative Trading Strategy Notes

This repository documents my independent trading and research work in Indian equity markets between 2020 and 2024. While not a professional role, I approached it with the rigor of a quant researcher—developing strategies, backtesting signals, and analyzing market structure under real-world constraints.

📈 **Performance highlight**: Designed and backtested trend-following, event-driven, and statistical arbitrage strategies using Python (Pandas, TA‑Lib); validated on 15 years of historical data, achieving ~14% annualized returns with Sharpe ~1.3 (pre‑costs, walk‑forward tested).

---

## 🧠 Trading & Investment Experience (2020–2024)

- Managed a personal portfolio with diversified exposure across Indian equities (small-cap to blue-chip), including PSUs and private banks.
- Combined long-term investments with short-term tactical trades using structured, data-driven strategies.
- Focused on identifying market inefficiencies and event-driven signals across NSE and BSE.

---

## 🔍 Strategy Focus

- **Style**: Event-driven, trend-following, and mean-reversion  
- **Markets**: NSE (primary), BSE (secondary for arbitrage)  
- **Approach**:  
  - Data-driven: price action, volume, sector flows, macro filters  
  - Quantitative indicators: moving averages, volatility bands  
  - Blended discretionary overlays with systematic rules

---

## 📊 Key Strategies I Worked On

### 1. MA-Based Trend Following
- Used 7D/50D/100D moving average crossovers
- Combined with volume breakout confirmation for conviction
- Example: Traded PSU bank basket during the 2022 re-rating cycle post recap announcements

### 2. NSE-BSE Arbitrage
- Exploited price discrepancies in dual-listed stocks (e.g., SBI, Tata Motors)
- Initially executed manually, later automated via Zerodha Kite API (rate-limited, ~20ms latency)
- Most effective during high-volatility sessions when spreads widened

### 3. Sector/Event-Driven Plays
- Traded directional momentum around earnings, RBI policy days, and Union Budget events
- Used a basket approach across 2–3 correlated stocks or ETFs
- Captured short-term volatility bursts following macro catalysts

### 4. Statistical Arbitrage (Backtested)
- Developed pairs trading models using cointegration tests and z-score thresholds (e.g., HDFC vs. ICICI)
- Performed well during range-bound markets; struggled in strong trends
- Not deployed live due to API latency and execution limitations

---

## ⚙️ Algo Trading & Execution Stack

- **Backtesting**: Python (Pandas, TA-Lib), Excel for prototyping  
- **Execution**: Zerodha Kite API, WebSocket-driven scripts  
- **Automation**: SMA crossover bots, basic arbitrage logic  
- **Data Constraints**:  
  - Relied on 1-min OHLC data (free API)  
  - Lacked access to tick data (NSE TBT feed costs ~₹3–5L/month)  
  - Subscribed to a premium retail data pack (~₹2k/month) to improve signal reliability  
- **Infra**: Retail-grade execution stack with manual supervision

---

## 🧭 Risk Management Evolution

- Started with basic stop-loss rules (2–4%)  
- Evolved into structured risk control framework:
  - Portfolio-level max drawdown thresholds (daily/weekly)  
  - Volatility-adjusted position sizing  
  - Event-driven risk reduction (e.g., pre-Fed announcements, Budget day)  
- Maintained a detailed post-trade journal to log signal performance, execution outcomes, and emotional/behavioral context

---

## 🌍 Market Events That Shaped My Style

### Semiconductor Supply Chain Crisis (2021–22)
- **Positioning**: Long auto ancillary stocks (Bosch, Motherson, Bharat Forge) expecting post-COVID recovery  
- **Mistake**: Underestimated the impact of global chip shortages  
- **Outcome**: Sector-wide drawdown despite strong company fundamentals  
- **Lesson**: Always hedge thematic bets; systemic risks can override bottom-up analysis

---

### Russia–Ukraine War (2022)
- **Positioning**: Long logistics, aviation, and oil marketing companies  
- **Mistake**: Failed to account for geopolitical escalation risk  
- **Outcome**: Sharp losses due to oil price spike and margin compression  
- **Lesson**: Don’t stay married to positions; respond fast when macro regime flips

---

### US Fed Tightening Cycle (2022–23)
- **Positioning**: Long high-beta tech and NBFCs during the growth optimism phase  
- **Mistake**: Underappreciated speed and magnitude of rate hikes  
- **Outcome**: Risk-off flows from FIIs led to major drawdowns  
- **Lesson**:
  - Tracked FII flows, U.S. yields, and dollar index dashboards more closely  
  - Started reducing exposure ahead of macro announcements  
  - Integrated global macro sentiment filters into signal framework

---

## 🛠️ Tools & Workflow

- **Brokerage**: Zerodha (Kite + Console)  
- **Backtesting**: Python (Pandas, TA-Lib), Excel for prototyping  
- **Execution**: Zerodha Kite API with WebSocket-driven basic bots  
- **Data**: Premium EOD + intraday (1-min); lacked access to NSE TBT feed (~₹3–5L/month), so subscribed to a premium retail data pack (~₹2k/month) to improve signal quality  
- **Infra**: Retail-level stack with scripting and manual alerts

---

## 📚 Where I Stand Now

Currently pursuing an MSc in FinTech at Imperial College London, focused on:
- Financial econometrics  
- Applied Quant Macro Strategies
- Systematic and algorithmic trading

The journey from a retail trader reacting to headlines to someone now building systematic frameworks to test hypotheses and design strategies has been immensely rewarding. I now understand what institutional-level infrastructure and research rigor look like—and how to bridge my retail experience with quant-driven strategy design.

Closing Thought: While the capital I deployed was limited, the intellectual skin-in-the-game was deep. These years gave me a real appreciation for risk, market structure, behavioral edges, and the importance of macro context—qualities I believe are essential in a quantitative research or trading role.


---
