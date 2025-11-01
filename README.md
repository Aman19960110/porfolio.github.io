# Aman Yadav — Quantitative Researcher 

**Quant researcher specialising in derivatives, options, volatility modelling, and systematic strategy development.**

---

## Profile Summary
I build reproducible, production-ready research and execution systems: from data pipelines and volatility forecasting models to backtests, risk analytics, and live order execution. I focus on measurable edge — statistical signal discovery, realistic transaction-cost modelling, and robust risk controls.

---

## Core Technical Profile
**Languages & Ecosystem:** Python, SQL, Bash, Docker

**Quant & Data Libraries:** pandas, numpy, scipy, statsmodels, arch, QuantLib, pyfolio/empyrical, numba

**Backtesting & Research Frameworks:** Backtrader, vectorbt, zipline (experience building custom engines)

**Machine Learning & Time Series:** scikit-learn, XGBoost, LightGBM, TensorFlow, PyTorch; ARIMA, GARCH, LSTMs, walk-forward validation

**Infrastructure & Tools:** Git, CI/CD, Docker, PostgreSQL, Kafka basics, Streamlit/Plotly for dashboards

**Research Methods:** statistical arbitrage,Delta-Nutral Options strategies, volatility surface modelling, NMF for cross-sectional signals, Monte Carlo and bootstrap for risk, A/B testing for execution logic

---

## Education
- **MSc in Financial Engineering (in progress)** — *WorldQuant University*
- **B.Tech in Civil Engineering (2018)** — *Dr. APJ Abdul Kalam Technical University*

---

## Professional Experience

**Derivative Analyst — Adroit Financials, Gurgaon, India** (May 2024 – Present)
- Designed and maintained Python pipelines to ingest and normalise high-frequency and end-of-day F&O datasets.
- Built and validated volatility forecasting models (GARCH-family and ML-hybrids) used as inputs for option-pricing and hedging experiments.
- Implemented a modular backtest engine for multi-leg options strategies with realistic order/sizing, margin and slippage modules.
- Created production-ready Streamlit dashboards and Plotly visualisations for trade PnL, exposures, and risk attribution used by traders and research leads.
- Collaborated across trading and engineering to translate research signals into executable strategies with clear risk limits.

---

## Selected Quant Projects (open-source)

### Straddle Backtest Engine — `straddle_backtest_engine`
Backtesting framework for multi-leg options strategies (straddles/strangles) with configurable order logic, slippage models, and performance reporting. Includes walk-forward and stress-test modules and example config files for reproducing net-return reports.

**Highlights:** modular config-driven backtests, reproducible net-return reports, Streamlit preview dashboards.

_Link:_ https://github.com/Aman19960110/straddle_backtest_engine

---

### Volatility Forecasting (GARCH) — `vol_forecasting_garch`
End-to-end volatility modelling pipeline: data ingestion, parameter estimation for GARCH-family models, one-step-ahead variance forecasting, and risk-adjusted strategy signals.

**Highlights:** automated model selection, backtested forecasts as inputs to hedging strategies, notebooked experiments and forecast visualisations.

_Link:_ https://github.com/Aman19960110/vol_forecasting_garch

---

### Bankruptcy Prediction (Poland, 2009) — `bankruptcy_2009-prediction-poland`
A supervised-learning project that forecasts corporate bankruptcy using financial statement features. Emphasis on handling imbalanced classes, multicollinearity, and explainability for risk models.

**Highlights:** feature engineering on financial ratios, SMOTE-based resampling, model explainability (SHAP), and evaluation using precision/recall for rare-event detection.

_Link:_ https://github.com/Aman19960110/bankruptcy_2009-prediction-poland

---

### Yield Curve Modeling — `yeild_curve_modeling`
(Repo spelling preserved) Framework for modeling and interpolating interest-rate term structures, fitting parametric curves (Nelson–Siegel / Svensson), and producing scenario-based yield forecasts for fixed-income risk and strategy work.

**Highlights:** curve-fitting utilities, bootstrapped confidence intervals, and code to generate yield-driven risk measures for hedging/backtesting.

_Link:_ https://github.com/Aman19960110/yeild_curve_modeling

---

### Token Live — `token_live`
A lightweight live-data ingestion & execution experiment designed to stream market ticks, manage ephemeral state, and prototype event-driven strategy ideas. Useful as a sandbox for integrating exchange feeds and testing execution logic.

**Highlights:** streaming ingestion examples, minimal order-simulation primitives, and notes on deployment patterns for low-latency prototyping.

_Link:_ https://github.com/Aman19960110/token_live

---

## Research Output & Deliverables
- Reproducible Jupyter notebooks with versioned data and seedable experiments
- Backtest reports (net-return, drawdown, risk metrics, trade logs)
- Live demo dashboards (Streamlit) for stakeholders
- Clear README & deployment scripts per repo for easy handoff

---

## Contact & Links
📧 amanyadav1004@gmail.com  
🐙 GitHub: https://github.com/Aman19960110  
🌐 Portfolio: https://aman19960110.github.io  
🔗 LinkedIn: https://linkedin.com/in/your-profile

---

## How to use this content
- Use sections directly on a personal site "About / Research / Projects / Contact" pages.
- Each project block links to the full repo and should embed the repo's README and key backtest plots.
- I can also convert this into a one-page HTML portfolio, a README.md, or a React/Tailwind component for immediate preview — say which format you want next.

