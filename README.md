# Project Title: Performance Analysis of FC Barcelona - A Decade of Evolution and Recurring Challenges in Competitions

## Project Overview and Motivation

Following their peak in the 2014/15 treble-winning season, FC Barcelona entered a turbulent period marked by declining performance, high transfer expenditure, and financial instability. This project uses data analytics to explore:

- How Barcelona’s on-pitch performance evolved over the past decade
- How finishing efficiency, defensive metrics, and squad structure changed
- How transfer spending and La Liga’s Squad Cost Limit shaped team performance
- Why the club struggled in the UEFA Champions League
- Whether financial indicators correlate with competitive outcomes

The goal is to provide a data-driven explanation of Barcelona’s transition from European dominance to instability and ongoing rebuilding.

## Tools and Technologies

- **Python:** pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook**
- **Github** for version control and project sharing
- (Optional) **Plotly** for interactive visualizations  

## Techniques & Skills Demonstrated


- Multi-source data integration
- Cleaning & preprocessing (column standardization, numeric conversions, deduplication)
- Feature engineering:
  - Standardized season format (e.g., 2014/15 → 14/15)
  - Finishing & defensive efficiency metrics (GF/xG, GA/xGA)
  - Aggregated season-level datasets for combined analysis
- Exploratory Data Analysis (EDA)
- Statistical & trend analysis
- Correlation analysis
- Interactive visualizations (Plotly, when relevant)

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

- Over €1.1B spent between 2016–2020 with minimal impacts and poor returns on investments
- Squad Cost Limit collapsed after 2020, reaching negative levels in 2021/22.
- Financial restrictions directly correlate with weaker on-field performance.

## Visualization

### La Liga Performance

- **Performance trends** (Total Goals vs Rank)

![Goals vs Rank](outputs/figures/goals_vs_rank.png)

- **Defensive Weakness** (Goals-For, Goals-Against, Goals-Difference):

  > **Note:** This is a [basic interactive plot](outputs/html/goals_vs_ga.html), you can interact with it by upload this notebook to Google Colab.

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
- Install dependencies (pandas, matplotlib, seaborn)
- Open FCB_performance_analysis.ipynb in Jupyter Notebook
- For interactive charts, run in Google Colab or a local environment with Plotly installed.
