# ⚾ MLB Salary Efficiency Analysis

## 📘 Overview
Fans often argue that many baseball players are overrated — they earn enormous salaries yet can’t perform perfectly every game.  
This project investigates that claim by analyzing the relationship between **salary** and **on-field performance**, asking:  
> Are players truly worth what they’re paid, or could teams optimize payroll without sacrificing wins?

Although centered on baseball, this framework can also be applied to the **job market**, evaluating whether compensation aligns with measurable output.

---

## 📂 Dataset Summary
- **Scope:** Player salary, WAR, OPS+, position, age, and performance metrics  
- **Size:** ~200K player-season observations  
- **Tools:** Python (`pandas`, `NumPy`, `seaborn`), `scikit-learn`

---

## ⚙️ Key Analysis

### 1️⃣ Performance Analysis
- **WAR–OPS+ correlation:** `r = 0.82`
- **Outfielders** had the highest average WAR (2.8), followed by **Infielders** (2.3)
- **Peak performance age:** 26–29 (avg WAR = 2.5)
- **Contact Rate** showed 15 % stronger impact on WAR than Power-Speed metric

### 2️⃣ Salary Efficiency
- Avg cost per WAR = **$4.2 M**
- **Younger players (23–25)** offered the best ROI  
- **Veterans (32+)** were 40 % less efficient
- Identified **$45.2 M** in potential salary optimization opportunities

### 3️⃣ Position-Specific Insights
| Position | Salary/WAR | Insight |
|-----------|-------------|----------|
| **C** | Stable, low variance | Consistent value |
| **IF** | **$3.8 M/WAR** | Best efficiency |
| **OF** | $12.4 M avg salary | High potential, high variance |
| **DH** | **$5.6 M/WAR** | Least efficient |

### 4️⃣ Age-Value Analysis
- **Peak salary efficiency:** Age 26 → `$3.2 M/WAR`
- **Rookies (≤25)** deliver **2.1× ROI** vs. veterans  
- **Veterans (32+)** show 40 % higher cost per WAR

---

## 💰 Optimization Impact
- **Total potential savings:** `$45.2 M` (≈ 18 % payroll reduction)  
- **Performance gain:** `+3.2 total WAR`  
- **By position:**  
  - OF → `$18.5 M`  
  - IF → `$15.3 M`  
  - C → `$6.8 M`  
  - DH → `$4.6 M`

---

## 🧠 Takeaway
Quantitative analysis reveals that player salaries often misalign with true performance value.  
By modeling **salary vs. WAR**, teams — and even organizations beyond sports — can make data-driven compensation decisions, **maximizing efficiency while maintaining performance**.
