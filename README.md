⚾️ MLB Salary Efficiency Analysis
Overview

Fans often argue that many baseball players are overrated — they earn enormous salaries yet can’t perform perfectly every game.
This project investigates that claim by quantifying the relationship between salary and on-field performance, asking:

Are players truly worth what they’re paid, or could teams optimize payroll without sacrificing wins?

Although based on baseball, the same framework can be applied to the job market — evaluating whether compensation aligns with measurable output.

📊 Dataset Summary

Scope: Player salary, WAR, OPS+, position, age, and performance metrics

Size: ~200K player-season observations

Tools: Python (pandas, NumPy, seaborn), scikit-learn

⚙️ Key Analysis
1️⃣ Performance Analysis

WAR vs OPS+ correlation: r = 0.82

Outfielders highest avg WAR (2.8), Infielders next (2.3)

Peak age: 26–29 (avg WAR 2.5)

Contact Rate → 15% stronger effect on WAR than Power-Speed metric

2️⃣ Salary Efficiency

Avg $4.2 M per WAR across all players

Younger players (23–25) most cost-efficient

Veterans (32+) 40% less efficient

Identified $45.2 M potential savings through contract optimization

3️⃣ Position Insights
Position	Salary/WAR	Notable Insight
C	Stable WAR, low variance	Consistent value
IF	$3.8 M/WAR	Best efficiency
OF	$12.4 M avg salary	High potential, high variance
DH	$5.6 M/WAR	Least efficient
4️⃣ Age-Value

Peak efficiency age: 26 yrs ($3.2 M/WAR)

Rookie contracts (≤25) → 2.1× better ROI than veterans

💰 Optimization Impact

Total potential savings: $45.2 M (~18% payroll reduction)

Performance gain: +3.2 total WAR

By position: OF $18.5 M · IF $15.3 M · C $6.8 M · DH $4.6 M

🧠 Takeaway

Quantitative analysis reveals that player salaries often misalign with true performance value.
By modeling salary vs. WAR, teams (and organizations in general) can make data-driven compensation decisions — maximizing efficiency while maintaining performance.
