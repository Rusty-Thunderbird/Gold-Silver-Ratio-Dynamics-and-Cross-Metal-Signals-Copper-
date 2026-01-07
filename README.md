# Gold-Silver-Ratio-Dynamics-and-Cross-Metal-Signals-Copper-
A systematic macro–quant analysis of the Gold–Silver ratio and cross-metal signals, combining regime classification, forward return asymmetry, and historical stress behavior to assess silver’s relative attractiveness and validate findings using copper.

# Gold–Silver Ratio Dynamics and Cross-Metal Signals

## Overview
This project presents a **macro–quantitative research framework** to analyze the **Gold–Silver price ratio** and its implications for **relative metal performance**, with a particular focus on **silver asymmetry across liquidity and tightness regimes**.

To validate the robustness of the framework, the same regime-based logic is also applied to **copper**, a pure industrial metal, enabling **cross-metal comparison** and helping distinguish silver’s hybrid (precious + industrial) behavior.

Inspired by the style of institutional commodities research (e.g., sell-side metals strategy notes), the analysis combines **historical ratio dynamics, regime classification, and forward return distributions** to evaluate relative metal performance under different macro conditions.

This notebook is written as a **public research note**, not as a trading strategy, and is intended for **educational and analytical purposes**.

---

## Key Questions Addressed
- How does the Gold–Silver ratio behave across different macro regimes?
- What does an elevated or compressed ratio imply for **future silver returns**?
- Does silver exhibit **asymmetric payoffs** depending on market tightness?
- How do **industrial metals like copper** behave across the same regimes?
- Would conclusions remain stable if the analysis were conducted using only historical data up to a prior cutoff date?

---

## Methodology
The framework follows a **top-down, regime-aware approach**:

1. **Data Collection**
   - Historical gold, silver, and copper prices
   - Construction of the Gold–Silver ratio
   - Macro and market indicators used for regime classification

2. **Regime Classification**
   - Markets segmented into **Tight**, **Neutral**, and **Loose** regimes
   - Regimes defined using macro supply-demand and liquidity proxies

3. **Forward Return Analysis**
   - Forward 3M / 6M return distributions for silver and copper
   - Percentile-based analysis to capture downside risk and upside convexity

4. **Asymmetry Assessment**
   - Comparison of metal performance across regimes
   - Identification of conditions under which silver and copper perform worst vs best

5. **Robustness Check**
   - Framework stability tested by truncating data at historical endpoints
   - Ensures conclusions are not driven by recent outcomes alone

---

## Key Findings (High Level)
- Silver tends to **underperform following extreme tightness regimes**
- Performance improves meaningfully in **Neutral and Loose regimes**
- Copper shows its **strongest performance in Neutral / Loose regimes**, consistent with industrial-cycle dynamics
- Forward return distributions indicate **asymmetric payoff profiles**, particularly for silver
- The framework’s conclusions remain **directionally consistent** even when applied using only pre-cutoff historical data

---

## What This Project Is (and Is Not)
**This is:**
- A structured research framework
- A macro-driven relative value and cross-metal analysis
- A student-led institutional-style research note

**This is not:**
- Investment advice
- A short-term trading signal
- A fully production-ready trading model

---

## Tools & Libraries
- Python
- pandas, numpy
- matplotlib / seaborn
- Jupyter Notebook

---

## Intended Audience
- Finance and economics students
- Commodities and macro research enthusiasts
- Aspiring buy-side / sell-side analysts
- Recruiters evaluating applied research projects

---

## Author
**Chinmay Mandave**  
Computer Science + Finance  
Independent Research Project

---

## Disclaimer
This project is for **educational and research purposes only**.  
It does not constitute investment advice or a recommendation to buy or sell any asset.
The repository contains two notebook versions: a baseline analysis using data through 30 November 2025 and an updated version through 07 January 2026, allowing for explicit robustness and hindsight-bias checks.

