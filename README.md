# New York Mets Hitter Salary & Performance Analysis

## Overview
This project focuses exclusively on **New York Mets hitters (n = 19)** to analyze the relationship between player performance and salary efficiency.  
Using machine learning models such as **Random Forest** and **XGBoost**, the analysis evaluates how metrics like **WAR, OPS+, OBP, SLG, Contact Rate**, and **Power Speed** contribute to performance value and contract fairness.

Although limited to the Mets roster, the same framework can be extended to other teams or organizations to quantify performance-based compensation efficiency.

---

## Methodology
- **Data:** 19 Mets hitters (latest season)  
- **Tools:** Python (`pandas`, `NumPy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`)  
- **Models:** Linear Regression, Ridge, Random Forest, XGBoost  
- **Goal:** Predict player salaries based on performance metrics and identify over- or under-valued players  

---

## Key Findings and Actionable Insights

### 1. Performance Analysis
- **WAR vs OPS+ correlation:** r = 0.82  
- **Outfielders** recorded the highest average WAR, followed by **Infielders**  
- **Peak performance age range:** mid-to-late 20s  
- **Contact Rate** showed stronger contribution to performance than Power Speed metrics  

---

### 2. Salary Efficiency Findings
- **Total roster cost:** $205.83M  
- **Identified inefficient spending:** $92.17M  
- **Optimization opportunities identified:** 5  
- **Potential salary savings:** $52.35M through targeted roster optimization  

---

### 3. Position-Specific Insights
| Position | Optimization Insight |
|--------|----------------------|
| **OF** | Moderate cost reduction with strong WAR upside |
| **IF** | Largest source of salary inefficiency |
| **C** | Stable performance with limited but positive savings |

---

### 4. Optimization Opportunities
- **Total potential savings:** $52.35M  
- **Projected performance gain:** +2.90 team WAR  
- **By position:**  
  - **Outfield (OF):** $7.34M savings, +1.40 WAR  
  - **Infield (IF):** $44.30M savings, +0.80 WAR  
  - **Catcher (C):** $0.70M savings, +0.70 WAR  

---

## Takeaway
Data-driven salary modeling for **New York Mets hitters** reveals clear opportunities to **reduce payroll while improving on-field performance**.  
By integrating advanced metrics such as **WAR and OPS+** into machine learning–based salary prediction, this analysis demonstrates how front-office decisions can become more objective, measurable, and cost-effective.

---

## Code & Notebook
Full implementation is available in [`batter_analysis.ipynb`](./batter_analysis.ipynb), including:
- Data preprocessing and feature engineering  
- Model training (Random Forest, XGBoost)  
- Feature importance analysis  
- Over- and under-valued player identification  
