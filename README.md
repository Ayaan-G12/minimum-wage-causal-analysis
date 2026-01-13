# Causal Impact of Minimum Wage Increases on Unemployment

## Overview
This project applies a causal inference framework to examine whether state-level minimum wage increases affect unemployment rates in the United States. Using a Difference-in-Differences (DiD) approach with state and year fixed effects, the analysis estimates the average causal impact of minimum wage policy changes on unemployment outcomes.

The project emphasizes causal identification, transparent assumptions, and careful interpretation of results.

---

## Research Question
**Do increases in state minimum wages causally affect unemployment rates?**

---

## Data
The analysis uses publicly available U.S. state-level data on:
- Annual unemployment rates
- State minimum wage levels

Data sources include U.S. government labor statistics and compiled state minimum wage records.  
Raw data are cleaned and transformed into a state-year panel dataset for analysis.

---

## Methodology
- Difference-in-Differences (DiD) framework
- State fixed effects to control for time-invariant heterogeneity
- Year fixed effects to control for national macroeconomic shocks
- Heteroskedasticity-robust (HC1) standard errors

The primary coefficient of interest is the interaction between treatment status and post-treatment period.

---

## Key Findings
- After controlling for state and year fixed effects, minimum wage increases are not associated with statistically significant changes in unemployment rates.
- The estimated effects are small in magnitude and statistically indistinguishable from zero.
- These results suggest that moderate minimum wage increases do not generate large aggregate employment effects at the state level.

---

## Limitations
- Analysis is conducted at the state-year level and may mask heterogeneous effects across demographic groups or industries.
- Treatment definition does not fully capture variation in policy magnitude or enforcement.
- Results focus on short- to medium-run effects and do not assess long-term labor market adjustments.

---
