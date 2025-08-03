**Project Overview**
This project focuses on analyzing and predicting customer churn for Teco, a fictional telecommunications company. The primary goal is to uncover key patterns that influence customer attrition and build actionable strategies to improve retention. Using data analysis, visualization, and machine learning, this project offers deep insights into customer behavior, particularly around contract types, payment methods, tenure, and demographics.

**Objectives**
Identify the key factors contributing to customer churn.
Analyze how contract length, payment methods, internet service types, and tenure affect churn rates.
Visualize patterns in customer attrition using graphs and charts.
Provide actionable recommendations to reduce churn.
Optionally, develop a predictive model to classify high-risk customers.

**Dataset Description**
The dataset contains customer information including:
Demographics: Senior citizen status, gender, etc.
Services: Internet service type, streaming services, device protection
Account info: Contract type, payment method, monthly charges, total charges
Tenure: Customer lifetime (in months)
Target variable: Churn (Yes/No)

**Key Insights**
1. Contract Type vs Churn
42% of customers on month-to-month contracts churned.
Only 11% and 3% churned from 1-year and 2-year contracts, respectively.
Recommendation: Encourage long-term contracts with discounts or rewards.
2. Payment Method vs Churn
45% of customers using electronic checks churned.
Customers using credit cards or bank transfers had churn rates between 15–18%.
Recommendation: Promote more stable payment methods to reduce churn.
3. Customer Tenure
Customers with <1 year tenure had a 50% churn rate.
Churn drops to 15% after 3+ years.
Recommendation: Implement onboarding and loyalty programs during the first year.
4. Senior Citizens
Senior citizens had a churn rate of 41%, compared to 26% for others.
Recommendation: Offer personalized support and communication for elderly customers.
5. Internet Service Type
Customers using Fiber Optic churned at 30%, compared to 20% for DSL.
Recommendation: Assess service quality or pricing for fiber users.

**Tools & Technologies Used**
Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook
Data Cleaning & Preprocessing
Data Visualization

**Visualizations**
Bar charts comparing churn rates across contract types and payment methods.
Line graphs showing churn trends based on tenure.
Pie charts of customer distributions.
Heatmaps of correlations.

**Business Recommendations**
Offer incentives for long-term contracts.
Encourage switch from electronic checks to more secure payment methods.
Engage customers early in their journey (within the first 6–12 months).
Create targeted retention strategies for senior citizens and high-risk customer segments.

**Future Scope**
Build a churn prediction model using supervised learning.
Deploy the model via Streamlit or Flask to create a real-time churn risk dashboard.
Implement segmentation and personalization strategies using clustering.
