# Telecom_Churn_Analysis--PowerBI
# Telecom Customer Churn & Retention Analytics

An end-to-end data analytics project focused on identifying customer churn drivers, evaluating revenue loss, and recommending retention strategies for a telecommunications business using **Power BI, Power Query, and DAX**.

---

##  Business Overview
Customer churn is a critical metric in the telecom industry. The primary goal of this analysis is to process over 7,000 customer records, understand why customers are leaving, and quantify the financial impact of customer attrition to help the business reduce churn rates.

---

##  Key Insights & Analytical Findings
* **Contract Risks:** Customers on **Month-to-Month contracts** constitute the highest proportion of churned users (~88%), whereas long-term contracts (1-year/2-year) show significantly higher retention.
* **Tenure Vulnerability:** Customers in their first year (`0 - 12 months`) are at the highest risk of churning (>30% churn rate).
* **Service Impact:** **Fiber Optic** internet subscribers experience a higher churn rate compared to DSL users, indicating potential service quality or pricing issues.
* **Financial Impact:** Estimated monthly revenue loss is heavily concentrated among short-tenure, month-to-month subscribers.

---

## 🛠️ Technical Implementation
* **Data Cleaning & ETL:** Used **Power Query** to handle missing values, correct data types, and transform raw customer records.
* **Data Modeling:** Established a clean star-schema / relational model for efficient performance.
* **DAX Calculations:** Created key measures for analytics:
  * Churn Rate %
  * Total Revenue Loss ($)
  *  Total Churned customers
