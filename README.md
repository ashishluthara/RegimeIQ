# 🧠 RegimeIQ -- NIFTY Market Regime Engine
### Daily Structural Market Analysis for the NIFTY Index

![status](https://img.shields.io/badge/status-active-success)
![research](https://img.shields.io/badge/type-quant%20research-blue)
![model](https://img.shields.io/badge/model-regime%20detection-purple)
![data](https://img.shields.io/badge/data-daily%20market%20structure-orange)

---

## 📊 Project Overview

Financial markets are **not random**.

Empirical analysis of the **NIFTY 50 index** reveals strong evidence of:

• persistent structural regimes  
• volatility clustering  
• tail-risk concentration  

This repository publishes the **daily output of a proprietary regime-detection engine** applied to:

➡️ **NIFTY 50**

The system analyzes market structure and classifies the environment into **distinct behavioral regimes**.

⚠️ **Important:**  
This repository **does not contain the source code of the model.**

Instead, it serves as a **public archive of model outputs** for transparency and research.

---

# 🧭 What This Engine Does

The system analyzes market data along **three structural axes**:

| Axis | Purpose |
|-----|--------|
| 📈 Trend | Detect directional persistence |
| 🌪 Volatility | Measure risk and clustering behavior |
| 💧 Liquidity | Identify structural fragility |

These axes combine to produce **eight macro market regimes**.

---

# 🧩 Market Regimes Detected

| Regime | Description |
|------|-------------|
| 🟢 **Bull Grind** | Slow, persistent upward trend with low volatility |
| 🔵 **Structured Trend** | Strong directional trend with sustained momentum |
| 🟡 **Premium Harvest** | Low-volatility range where option decay dominates |
| 🟠 **Chaotic** | Whipsaws, false breakouts, unstable structure |
| 🔴 **Panic Crash** | High-volatility downside shock regime |
| ⚪ **Compression** | Extremely low volatility before expansion |
| 🟣 **Short Squeeze** | Rapid upward volatility spike |
| 🟤 **Thin Trend** | Directional move with weak liquidity |

These regimes capture **how the market behaves**, not just where it moves.

---

# 🔬 Key Statistical Findings (2018–Present)

Analysis of historical NIFTY data reveals:

### 📍 Persistent Structural States
Regimes tend to **persist for multiple days** rather than changing randomly.

Example persistence probabilities:

| State | P(stay) |
|------|--------|
Bull Grind | ~0.83  
Structured Trend | ~0.77  
Panic Crash | ~0.75  

---

### 📍 Volatility Clustering
Large price moves tend to be followed by large moves.

Evidence:

• |Return| autocorrelation ≈ **0.27 at lag-1**  
• GARCH persistence ≈ **0.9** in calm regimes  
• High-volatility states persist **~15 days**

---

### 📍 Tail-Risk Concentration

Extreme losses cluster in specific regimes.

Most downside tails occur during:

• **Chaotic states**  
• **Panic Crash regimes**

These states represent **<20% of time but dominate extreme events**.

---

# 📅 Daily Output Archive

Each day the engine publishes:

- detected macro regime
- volatility estimates
- transition probabilities
- structural risk indicators
- market interpretation

Example output:
