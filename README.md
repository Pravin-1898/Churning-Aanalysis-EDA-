📊 Customer Churn Analysis – EDA Report
📝 Project Overview
This project aims to analyze customer churn for a telecom company using Exploratory Data Analysis (EDA). The objective is to extract meaningful patterns and insights that can help the business improve customer retention, especially identifying key factors that influence customer churn.

🔍 Problem Statement
Churn prediction is critical for subscription-based businesses. This analysis identifies customer behaviors and attributes that are linked with high churn rates and provides data-driven recommendations to reduce customer attrition.

📁 Dataset Description
The dataset contains various features related to customer demographics, account information, service details, and contract types. The main target variable is:

Churn: Whether the customer has left within the last month (Yes/No)

Key Columns:
gender, SeniorCitizen, Partner, Dependents

PhoneService, MultipleLines, InternetService, OnlineSecurity, TechSupport, etc.

Contract, PaymentMethod, MonthlyCharges, TotalCharges

tenure: Number of months the customer has stayed with the company

⚙️ Preprocessing Steps
Converted Churn into binary values (Yes = 1, No = 0)

Created dummy variables for categorical features

Grouped tenure into buckets for easier analysis

Checked for correlation between numerical variables

📊 Key Findings
🔴 High Churn Indicators:
Contract Type:

41% churn rate in month-to-month customers

Long-term contracts (1 or 2 years) reduce churn significantly

Payment Method:

Customers paying via electronic check have the highest churn

Tenure:

Majority of churn happens within the first 12 months

Support Services:

No tech support and no online security strongly linked to higher churn

Demographics:

Senior citizens and single customers are more likely to churn

Gender has minimal impact

Charges:

High monthly charges and low total charges (often short tenure) correlate with higher churn

📈 Visual Insights
KDE Plots for monthly charges, total charges, and tenure clearly show differences between churned and retained customers

Correlation Heatmap supports feature selection (e.g., Gender and PhoneService have negligible correlation with churn)

Bar plots reveal contract types, tech support, and payment methods as high-impact factors

📌 Recommendations
Encourage customers to switch from month-to-month to longer-term contracts

Reduce churn for new customers with onboarding assistance and offers

Provide bundled support services (online security, tech support) in early months

Promote auto-payment methods to reduce churn linked with electronic checks

Use targeted retention campaigns for high-risk groups (senior citizens, customers with no partners)

🛠️ Tools Used
Python (Pandas, NumPy, Seaborn, Matplotlib)

Jupyter Notebook

Seaborn for data visualization

Correlation and KDE plots for analysis

📎 Conclusion
This EDA project provides a comprehensive understanding of churn behavior. The insights can guide data-driven retention strategies, potentially reducing churn and increasing customer lifetime value.
