# AI-Assisted Cryptocurrency Paper-Trading System

**Type:** Independent learning and engineering project  
**Status:** Experimental / simulation, not a live investment product

## Goal
Build an automated research and simulation system that observes cryptocurrency markets, evaluates candidate trades, models risks, and records simulated execution outcomes.

## System design
- Python-based market scanning and exchange API integrations.
- Historical and current market data processing; SQL/SQLite persistence.
- Rule-based strategies and AI/ML-assisted research and analysis.
- Simulated order execution with attention to spreads, liquidity, fees, slippage, and position sizing.
- Dashboard and Telegram alerts for monitoring.
- Guardrails such as limits on allocation, daily loss, and drawdown.

## Technologies
Python · REST APIs · SQL / SQLite · Freqtrade / FreqAI · Telegram integration

## What it demonstrates
API integration, scheduled automation, persistent data models, risk-aware decision logic, failure monitoring, and evaluation of AI-generated suggestions.

## Important limitations
- **Paper trading is the default.** No claim of live trades or real returns.
- A trading signal is not proof of an economic edge.
- Profitability, model quality, and execution realism require independent evaluation and out-of-sample tests.
- No API keys, exchange credentials, or live wallet details are published.

## Evidence to add
Sanitised architecture diagram, simulated performance charts with labelled data windows, reproducible backtesting methodology, and brief demo of the dashboard.
