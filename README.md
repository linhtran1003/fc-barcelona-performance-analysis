# Project Title: Performance Analysis of FC Barcelona - A Decade of Evolution and Recurring Challenges in Competitions

## Project Overview and Motivation

- After their peak in 2014/2015, FC Barcelona has transitioned from European dominance to facing recurring challenges in both domestic and continental competitions. This project analyzes FC Barcelona's performance trends over the past decade (2014–2025) in domestic (La Liga) and international (UEFA Champions League) competitions. It explores attacking and defensive metrics, finishing efficiency, and financial factors such as transfer spending and squad cost limits to identify potential drivers behind the club’s recent decline and rebuilding phase.
- By integrating multiple datasets and applying advanced analytics, the project aims to answer a central question

  > *How did FC Barcelona go from European dominance to financial and competitive instability, and what factors explain their decline and recovery?*

## Tools and Technologies

- **Python:** pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook**
- **Github** for version control and project sharing
- (Optional) **Plotly** for interactive visualizations  

## Techniques & Skills Demonstrated

### **Data collection & preparation**

- Multi-source data integration (performance + financial data)
- Manual and automated data extraction from official websites
- Cleaning & standardizing inconsistent formats `2014/15 → 14/15`

### **Data transformation & feature engineering**

- `groupby` aggregations for season-level and situation-level metrics
- Derived metrics:
  - Finishing efficiency `GF/xG`
  - Defensive efficiency `GA/xGA`
- Merging datasets to create analysis-ready tables

### **Exporatory Data Analysis (EDA)**

- Trend and time-series analysis
- Comparing attacking, defensive, and efficiency metrics
- UCL progression and knockout-stage failure patterns
- Squad cost limit comparison vs Real Madrid
- Correlation heatmaps
- Contextual football interpretation (injuries, departures, tactical shifts)

### Financial Analysis

- Visualizing long-term transfer spending
- Impacts of overspending, COVID-19, and "economic lever"
- Salary-cap restrictions and squad-depth implications
- Relationships between finance and performance

### **Visualization (matplotlib, seaborn, and plotly)**

- Multi-line and bar plots
- Dual-axis plots (e.g., Goals vs Rank)
- Multi-team comparative plots (FCB vs Real Madrid)
- Heatmaps for correlation analysis
- Interactive Plotly dashboard that summarizes the key aspects of the project

### **Critical thinking & Problem solving**

- Identifying causation vs correlation between finances and performance
- Explaining performance fluctuations using contextual factors (player transfers, injuries, coaching, financial regulations)
- Recognizing dataset limitations and adapting methodology accordingly (e.g., manual table creation)

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

### 🟠 Financial Mismanagement Impact

- Over €1.1B spent between 2016–2020 with poor returns
- Experienced strict salary-cap restrictions after 2020
- Heavy rely on:
  - Free transfers
  - Loan signings
  - La Masia youth (FC Barcelona Academy)
- Temporary recovery in 22/23 due to “economic levers” but not consistent
- **Correlation**: higher financial flexibility generally improves win rate and squad depth, while restrictions lead to inconsistent performance

## Visualization

### La Liga Performance

- **Performance trends** (Total Goals vs Rank)

![Goals vs Rank](outputs/figures/goals_vs_rank.png)

- **Defensive Weakness** (Goals-For, Goals-Against, Goals-Difference):

  > **Note:** This is a [basic interactive plot](outputs/html/goals_vs_ga.html), you can interact with it by either downloading it and open locally in your browser, or upload this notebook to Google Colab.

![Goals vs GA](outputs/figures/goals_vs_ga.png)

- Finishing Efficiency (Goals-For vs Expected Goal):

### UCL Performance

### Financial

- **Transfer Spend (M€)**

![Transfer Sum](./outputs/figures/transfer_expenditures.png)
  
- **Squad Cost Limit (M€)**

![Squad Cost Limit](./outputs/figures/squad_cost_limit.png)

## Conclusion

- Over the past decade, FC Barcelona’s journey from dominance to reconstruction reflects the deep interplay between financial constraints, tactical transition, and player turnover.
- The data reveals that declining squad efficiency and defensive inconsistency coincided with the club’s financial tightening post-2020. Despite a brief rebound in 22/23 season, sustained success remains limited by squad renewal constraints under La Liga’s financial rules.
- Ultimately, restoring long-term competitiveness will require not only tactical refinement but also sustainable financial recovering - ensuring that spending power, recruitment strategy, and player development align more effectively.

## How to run

- Clone the repo
- Install dependencies (pandas, matplotlib, seaborn)
- Open FCB_performance_analysis.ipynb in Jupyter Notebook
- Optional: use Google Colab to experience interactive plots
