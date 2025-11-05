# ⚾ New York Mets Hitter Salary & Performance Analysis

## 📘 Overview
This project focuses exclusively on **New York Mets hitters (n = 19)** to analyze the relationship between player performance and salary efficiency.  
Using machine learning models such as **Random Forest** and **XGBoost**, the analysis evaluates how metrics like **WAR, OPS+, OBP, SLG, Contact Rate**, and **Power Speed** contribute to performance value and contract fairness.

Although limited to the Mets roster, the same framework can be extended to other teams or organizations to quantify performance-based compensation efficiency.

---

## 🧠 Methodology
- **Data:** 19 Mets hitters (latest season)
- **Tools:** Python (`pandas`, `NumPy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`)
- **Models:** Linear Regression, Ridge, Random Forest, XGBoost
- **Goal:** Predict player salaries based on performance metrics and identify over- or under-valued players.

---

## 🔍 Key Findings and Actionable Insights

### 1️⃣ Performance Analysis
- **WAR vs OPS+ correlation:** r = 0.82  
- **Outfielders** recorded the highest average WAR (2.8), followed by **Infielders** (2.3)  
- **Peak performance age:** 26 – 29 (average WAR ≈ 2.5)  
- **Contact Rate** had ~15 % stronger impact on performance than **Power Speed**

### 2️⃣ Salary Efficiency Findings
- Average **$ 4.2 M per WAR** across all positions  
- Identified **$ 45.2 M** in potential salary optimization opportunities  
- **Younger players (23 – 25)** offered best value; **veterans (32 +)** 40 % less efficient  
- **Outfielders** showed largest salary variance (σ = $ 5.8 M)

### 3️⃣ Position-Specific Insights
| Position | Salary/WAR | Observation |
|-----------|-------------|--------------|
| **C** | Low variance, stable WAR | Reliable performance |
| **IF** | **$ 3.8 M / WAR** | Best efficiency |
| **OF** | $ 12.4 M avg salary | High potential but volatile |
| **DH** | **$ 5.6 M / WAR** | Least efficient |

### 4️⃣ Age-Value Analysis
- **Peak salary efficiency age:** 26 → $ 3.2 M per WAR  
- **Early prime (25 – 27)** = best performance / salary ratio  
- **Rookies (≤ 25)** show ~2.1× better ROI than veterans  
- **Veterans (32 +)** ≈ 40 % higher $/WAR than team average  

### 5️⃣ Optimization Opportunities
- **Total potential savings:** $ 45.2 M (≈ 18 % of Mets payroll)  
- **Projected performance gain:** +3.2 team WAR  
- **By position:**  
  - OF → $ 18.5 M savings  
  - IF → $ 15.3 M  
  - C → $ 6.8 M  
  - DH → $ 4.6 M  

---

## 💡 Takeaway
Data-driven salary modeling for **New York Mets hitters** reveals clear opportunities to improve payroll efficiency while maintaining team performance.  
By integrating advanced metrics (WAR, OPS+, OBP) into salary prediction, front-office decisions can become more objective, measurable, and cost-effective.

---

## 🧾 Code & Notebook
Full implementation is available in [`batter_analysis.ipynb`](./batter_analysis.ipynb), including:
- Data preprocessing and feature engineering  
- Model training (Random Forest, XGBoost)  
- Feature importance visualization  
- Over-/under-valued player identification  
