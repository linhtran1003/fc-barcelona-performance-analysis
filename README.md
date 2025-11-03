# Project Title: Performance Analysis of FC Barcelona - A Decade of Evolution and Recurring Challenges in Competitions

## Executive Summary and Motivation

This project explores FC Barcelona’s performance trends across La Liga and the UEFA Champions League between 2014 and 2025, integrating financial metrics such as transfer spending and squad cost limits. The analysis provides insights into how squad efficiency, managerial changes, and financial constraints shaped the club’s competitive trajectory.

**Motivation**: After the 2014/15 treble-winning season, Barcelona faced a decade of highs and lows, including performance decline, financial instability, and restructuring. This project uses data to uncover the causes behind these patterns.

**Key Insight**s: A decade of FC Barcelona’s domestic and international performance, finishing efficiency, and financial trends.

![Key Insights](./outputs/figures/overall_key_insights.png)

> This is an interactive dashboard created by `plotpy`. Run in Google Colab or a local environment with Plotly installed to explore more information on the plot.

## Tools and Technologies

- **Python:** pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook**
- **Github** for version control and project sharing
- (Optional) **Plotly** for interactive visualizations  

## Techniques & Skills Demonstrated

- Multi-source data integration and preprocessing
- Cleaning & standardization (season formatting, numeric conversion)
- Feature engineering: finishing efficiency (GF/xG), defensive efficiency (GA/xGA)
- Exploratory Data Analysis (EDA) and trend analysis
- Correlation analysis between financial and performance metrics
- Static and interactive visualizations

## Key Analysis and Findings

### 🔵 Declining attacking output (post-2016)

- Goals scored peak between 14/15 and 16/17, and then declined gradually, reaching the lowest in 2022.

### 🔴 Defensive Weaknesses

- Goal difference decreased steadily after the 14/15 season.
- 21/22 marked the lowest level in FC Barcelona's performance, with low goals scored but high goals conceded.
- Improvement under Xavi (22/23) but inconsistency remains

### 🟡 Finishing Efficiency (Expected Goals vs Goals-For)

- Open-play efficiency dropped below 1.0 after 19/20
- Set-piece efficiency weakened dramatically after 2021, coincided with Messi departure, showing reliance on key players

### 🔵 UEFA Chaampions League Performance

- 8 eliminations in Quarter/Semi finals since 2015
- Demoted to Europa League in 21/22 and 22/23, Round of 16 failure in 21/22 and Round of 32 failure in 22/23
- Goals scored improved recently, but knockout failures persist

### 🟠 Financial Context

- €1.1B+ spent between 2016–2020 with minimal impacts and poor returns on investments
- Squad Cost Limit collapsed after 2020, reaching negative levels in 2021/22.
- Financial restrictions directly correlate with weaker on-field performance.

## Visualization

### La Liga Performance

- **Performance trends** (Total Goals vs Rank)

![Goals vs Rank](outputs/figures/goals_vs_rank.png)

- **Defensive Weakness** (Goals-For, Goals-Against, Goals-Difference):

![Goals vs GA](outputs/figures/goals_vs_ga.png)

- Finishing Efficiency (Goals-For vs Expected Goal):

![Finishing Efficiency](./outputs/figures/finishing_eff.png)

### UCL Performance

### Financial

- **Transfer Spend (M€)**

![Transfer Sum](./outputs/figures/transfer_expenditures.png)
  
- **Squad Cost Limit (M€)**

![Squad Cost Limit](./outputs/figures/squad_cost_limit.png)

## Conclusion

FC Barcelona’s decline cannot be explained by performance metrics alone. Instead, the combined analysis shows:

- Squad mismanagement (2017–2020) created structural weaknesses
- Financial collapse (2020–2022) restricted squad-building capacity
- Efficiency declines (finishing and defensive) negatively impacted results
- UCL performance drop mirrors domestic instability
- Financial flexibility strongly predicts competitive performance

The project demonstrates how long-term football performance can only be understood by combining data, context, and finance.

## How to run

- Clone the repo
- Install dependencies: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotply` (optional)
- Open `FCB_performance_analysis.ipynb` in Jupyter Notebook
- For interactive charts, run in Google Colab or a local environment with Plotly installed.

## Limitations & Potential Improvements in The Future

**Limitations:**

- Limited dataset granularity: match-level stats and player-level contributions are not considered
- Financial data are unavailable or approximate.

**Future Work:**

- Integrate match-level or player-level datasets for advanced metrics (e.g., xGA, pressing, possession).  
- Develop interactive dashboards for storytelling.
- Comparative analysis with other top clubs over the same period.
