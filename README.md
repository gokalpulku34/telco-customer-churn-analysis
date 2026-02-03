Telco Customer Churn Analysis
Overview

This project presents an end-to-end churn analysis on a telecom customer dataset with 7,043 customers.
The goal is to understand why customers churn and determine whether churn is driven by product dissatisfaction or structural business factors such as pricing and contract type.

The analysis is conducted using SQL (DuckDB) and Python (pandas) in a Jupyter Notebook, following a business-oriented analyst approach.

Tools & Technologies

Python (pandas, matplotlib)

SQL (DuckDB)

Jupyter Notebook

Dataset: IBM Telco Customer Churn

Key Findings
1. Overall Churn

Total customers: 7,043

Overall churn rate: 26.5%

This indicates a significant retention problem requiring business action.

2. Churn Timing (Tenure)

Churned customers leave significantly earlier than retained customers.

Avg tenure (churned): ~18 months

Avg tenure (retained): ~38 months

This shows that churn is primarily an early-stage problem.

3. Contract Type Is the Main Driver
Contract Type	Churn Rate
Month-to-month	42.7%
One year	11.3%
Two year	2.8%

Insight:
Churn is heavily concentrated in month-to-month contracts, while long-term contracts demonstrate strong retention.

4. Pricing Effect

Customers who churn pay significantly higher monthly charges than retained customers.

Avg monthly charge (churned): 74.4

Avg monthly charge (retained): 61.3

This suggests strong price sensitivity, especially for customers without long-term commitment.

5. Combined View: Contract × Price × Tenure

High-price + month-to-month customers show the highest churn risk.

Long-term contract customers churn rarely and typically after many years.

Churn in long-term contracts represents natural lifecycle churn, not systemic dissatisfaction.

Business Conclusion

Churn in this dataset is not a product quality problem.
It is driven by contract structure and pricing strategy, particularly affecting early-stage, non-committed customers.

Recommended Actions

Incentivize early conversion from month-to-month to long-term contracts.

Avoid offering high-priced plans without contractual commitment.

Focus retention efforts on the first 12–18 months of the customer lifecycle.
