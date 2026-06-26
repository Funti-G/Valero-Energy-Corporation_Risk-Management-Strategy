# Valero Energy Corporation — Corporate Risk Management & Monte Carlo Simulation

> **Course:** FIN 6362 — Corporate Risk Management · University of Texas at Dallas  
> **Author:** Arvind Kumar Gill  
> **Advisor:** Dr. Kannoo Ravindran 
> **Date:** December 2025  

---

## Overview

This project applies quantitative risk modeling techniques to assess the financial risk profile of **Valero Energy Corporation (NYSE: VLO)** — one of the world's largest independent petroleum refining and marketing companies.

Using **Monte Carlo simulation**, the analysis models the impact of commodity price volatility (crude oil, crack spreads, and refined product margins) on Valero's revenue and earnings, generating a probabilistic distribution of financial outcomes under varying market conditions.

The central question: **How exposed is Valero's bottom line to oil price shocks, and what risk management strategies can best protect shareholder value?**

---

## Key Questions Addressed

- What is the probability distribution of Valero's operating income under different crude oil price scenarios?
- How sensitive are refining margins to crack spread volatility?
- What is the Value at Risk (VaR) for Valero's earnings at 95% and 99% confidence intervals?
- What hedging strategies minimize downside risk while preserving upside exposure?

---

## Methodology

### 1. Monte Carlo Simulation
- Simulated **10,000+ price path scenarios** for crude oil and refined product prices
- Modeled input variables (crude oil price, crack spread, throughput volume) as stochastic processes with historical volatility calibrated from market data
- Generated probability distributions of operating income and free cash flow under each scenario

### 2. Sensitivity Analysis
- Identified key value drivers and their marginal impact on earnings
- Quantified the earnings impact of a **$10/barrel move** in crude oil prices
- Stress-tested performance under tail-risk scenarios (oil spike, demand collapse, margin compression)

### 3. Risk Metrics
- **Value at Risk (VaR):** Estimated maximum expected loss at 95% and 99% confidence
- **Expected Shortfall (CVaR):** Modeled average loss beyond the VaR threshold
- **Break-even Analysis:** Identified crude oil price floors required to maintain positive operating margins

---

## Key Findings

| Scenario | Crude Oil Price | Operating Margin Impact |
|---|---|---|
| Base Case | $75–85/bbl | Stable margins (~8–10%) |
| Upside (Low Crude) | <$65/bbl | Margin expansion (+2–3pp) |
| Downside (High Crude) | >$95/bbl | Margin compression (−3–5pp) |
| Tail Risk | >$110/bbl | Near break-even or loss |

- Crack spread volatility explains **~60%** of operating income variance — more than crude oil price level alone
- A **$10/bbl increase** in crude with no corresponding product price increase reduces annual operating income by an estimated **$800M–$1.2B**
- Hedging via crack spread futures reduces earnings volatility by approximately **30–40%** without significantly capping upside

---

## Strategic Recommendations

1. **Implement crack spread hedging** for 30–40% of forward refining volume to stabilize near-term cash flows
2. **Maintain feedstock flexibility** — ability to switch between crude grades is Valero's most durable competitive advantage
3. **Prioritize throughput optimization** during low-margin environments to preserve fixed cost absorption
4. **Build liquidity buffers** sized to withstand a 6-month tail-risk scenario without distressed asset sales

---

## Repository Contents

| File | Description |
|---|---|
| `CRM Report.docx` | Full written report with analysis, findings, and recommendations |
| `Common Workbook_Draft.xlsx` | Monte Carlo simulation model and sensitivity analysis |
|
