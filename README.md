# HR-Analytics-Project--Employee-Attrition-Analysis
Employee attrition is a major challenge for organizations, impacting costs, morale, and long-term performance. By applying data science and machine learning techniques, this project uncovers key insights into why employees leave and provides prescriptive recommendations for HR teams.

HR Analytics Project – Employee Attrition Analysis
📌 Project Overview

This project explores the IBM HR Analytics Employee Attrition dataset to uncover the drivers of employee turnover. Employee attrition is costly and disruptive, affecting both productivity and morale. Through descriptive, diagnostic, predictive, and prescriptive analytics, the project addresses key business questions and delivers actionable recommendations for HR strategy.

❓ Business Questions

The project is guided by the following questions:

What is the current state of attrition in the company? (overall rate, department breakdowns)

Who is most likely to leave? (role, tenure, income, satisfaction, overtime, etc.)

Why are employees leaving? (statistical significance of different factors)

Can we predict attrition before it happens? (building risk models)

What interventions should HR implement to reduce attrition?

🛠️ Tools & Libraries

Python: Core programming

Pandas, NumPy: Data cleaning & manipulation

Matplotlib, Seaborn: Visualization

SciPy: Hypothesis testing

Scikit-learn: Machine learning (Logistic Regression, Random Forest)

🔍 Analytical Approach
1. Descriptive Analysis (What happened?)

Objective: Summarize attrition patterns across roles, departments, age groups, and satisfaction levels.

Why chosen: Provides HR with a clear snapshot of the problem.

Key Outputs: Attrition rate ~16%, highest in Sales and R&D overtime workers.

2. Diagnostic Analysis (Why did it happen?)

Objective: Test relationships between attrition and factors such as overtime, income, job satisfaction, and tenure.

Why chosen: Identifies root causes using statistical rigor.

Techniques: Chi-square tests for categorical variables, t-tests for numerical differences.

Key Outputs: Overtime, low income, and low satisfaction are statistically significant predictors of attrition.

3. Predictive Analysis (What will happen?)

Objective: Build models to classify employees as “likely to leave” vs. “likely to stay.”

Why chosen: Enables HR to proactively flag at-risk employees.

Models:

Logistic Regression (interpretable baseline)

Random Forest (handles non-linearities & interactions)

Key Outputs:

Logistic Regression → ROC-AUC ~0.77, good interpretability.

Random Forest → Higher accuracy & recall, better overall predictive power.

4. Prescriptive Analysis (What should we do?)

Objective: Translate findings into business recommendations.

Why chosen: Ensures insights lead to real-world HR actions.

Key Outputs: Actionable strategies to reduce turnover and improve employee satisfaction.

📊 Findings & Outputs

Overtime: Employees with overtime duties had the steepest risk of leaving.

Income Bands: Lower income within job levels correlated strongly with attrition.

Tenure: Early tenure (<2 years) carried the highest exit probability.

Satisfaction: Low job satisfaction was a consistent driver of attrition.

Career Stage: Mid-career plateau showed exit risks, while long-tenure staff were more stable.

Visual outputs (bar plots, heatmaps, ROC curves) helped communicate insights to non-technical stakeholders.

🧭 Recommendations

Workload Balance – Rotate overtime or hire temporary staff during peak demand.

Compensation Adjustments – Review salary bands, especially for junior/mid roles.

Early-Career Retention – Enhance onboarding, mentoring, and growth opportunities in the first two years.

Satisfaction Monitoring – Deploy regular engagement surveys to flag dissatisfied groups.

Career Development – Create structured growth paths to reduce mid-career attrition.

✅ Conclusion

This project demonstrated how data-driven HR analytics can transform employee management:

HR teams gain visibility into attrition patterns.

Predictive models enable proactive interventions.

Prescriptive insights guide strategic HR policies.

Ultimately, this approach not only reduces turnover costs but also fosters a healthier, more engaged workforce.
