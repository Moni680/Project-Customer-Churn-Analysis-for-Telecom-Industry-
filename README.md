# Project-Customer-Churn-Analysis-for-Telecom-Industry-
<br>
TOOLs-Python, SQL Server, PowerBI, Meachine learning
<br>
Objective:
<br>
Predict customer churn and uncover actionable strategies to retain customers in a highly competitive telecom environment.
<br>
Tools Used:

SQL: For data aggregation and feature engineering
<br>
Python (Scikit-learn, ELI5): For model building and interpretability
<br>
(Optional: SHAP for advanced explainability)
<BR>
Churn is a critical concern in the telecom sector. This project focused on analyzing historical customer data and predicting potential churners using machine learning. The goals were:
<br>
Identify key churn drivers
<br>
Segment customers based on churn risk
<Br>
Predict likely churners
<br>
Recommend data-driven retention strategies
<br>
📊 2. Key Findings from Historical Churn Data
<br>
💡 Overall Stats
<br>
![Screenshot 2025-05-01 235602](https://github.com/user-attachments/assets/e15bae12-6c89-40ff-a226-7aaf51846b83)
<br>
Total Customers: 3,223
<br>
Churned Customers: 883
<br>
Churn Rate: 27.4%
<br>
New Joiners: 211
<br>

🔍 Churn by Segments
<br>
Attribute	Insight
<br>
Gender	Male customers churn more (65% of churned users)
<br>
Age	Customers aged >50 have the highest churn rate (31.7%)
<br>
Tenure	Even long-tenured users (≥24 months) have a 29.6% churn rate
<br>
Contract	Month-to-month users have a 47.5% churn rate vs 2.7% for 2-year users
<br>
Payment Method	Mailed Check users churn at 41.3%, Credit Card users only 14.4%
<br>
Internet Type	Fiber optic customers churn more (41.8%)
<br>
States	Jammu (59.5%), Assam (40.8%) lead in churn rates
<br>
Churn Reason	Competition is the top reason (392 churns)
<br>
Service Impact	Customers using Unlimited Data and Premium Support churn less
<br>
📈 3. Predictive Model Insights
<br>
Model Summary
<br>
Type: Binary Classification (Churn/No Churn)
<br>
Algorithm: Random Forest (explained with ELI5)
<br>
Accuracy: ~81%
<br>
Explainability: Key drivers identified include contract type, monthly charges, tenure, and support service usage
<br>
Predicted Churners
<br>
Total Predicted Churners: 377
<br>
Estimated Monthly Revenue Risk: ₹16,190
<br>
Total Revenue at Risk: ₹43,009.85
<br>

Breakdown of Predicted Churners:
<br>
Gender: 245 Female, 132 Male
<br>
![Screenshot 2025-05-01 235623](https://github.com/user-attachments/assets/f3727b0c-42b5-4c00-becb-e18a67e0d024)
<br>
Age Group: Majority >35 years
<br>
Tenure: High churn risk in both 6–18 months and ≥24 months
<br>

Contract: ~100% are on Month-to-Month
<br>

Top States: Uttar Pradesh, Maharashtra, Tamil Nadu, Karnataka
<br>

🎯 4. Customer Segmentation
<br>
Customers were classified into the following categories for strategy alignment:
<br>

Segment	Criteria	Action
<br>
At Risk	Predicted churners with high monthly charges	Personalized retention offers, call center follow-up
<br>
Loyal	1–2 year contract holders, low churn history	Upsell premium services
<br>
Dormant	Users with low activity or usage	Re-engagement via campaigns or surveys
<br>

✅ 5. Recommendations
<br>
Contract & Billing
<br>
Offer discounts for switching to annual or 2-year contracts
<br>

Promote auto-pay via Credit Card for improved retention
<br>

Customer Experience
<br>
Focus on high-churn states (e.g., Jammu, Assam, Uttar Pradesh)
<br>
Improve Fiber Optic service experience through quality audits
<br>

Retention Campaigns
<br>
Target older customers (>50) and those with >24 months tenure with appreciation rewards
<br>
Launch personalized retention campaigns based on churn drivers (e.g., service dissatisfaction, competition)
<br>
Operational Enhancements
<br>
Use churn prediction to trigger real-time retention workflows
<br>
Analyze complaint logs to align product/service improvement
