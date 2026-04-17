# Telecom KPI Dashboard

## Problem Statement
The telecommunications industry is highly competitive, and acquiring new customers is often more expensive than retaining existing ones. High churn rates directly impact revenue and profitability. The goal of this project is to analyze customer data to understand the key drivers of customer churn, segment customers based on demographics and services, and provide actionable insights to improve retention.

## Approach
1. **Data Sourcing:** Downloaded a synthetic 100,000-record Telecom Customer dataset.
2. **Data Transformation & Modeling:** Used Power Query to clean the dataset, handle missing values, and structure it for analysis. 
3. **DAX Measures:** Created calculated measures for Churn Rate, Average Revenue Per User (ARPU), Total Customers, and Retention Rate.
4. **Dashboard Creation:** Built an interactive 3-page Power BI report:
   - **Overview:** High-level metrics like Total Customers, overall Churn Rate, and Monthly Charges.
   - **Customer Segments:** Breakdown of demographics, account information, and service types.
   - **Churn Drivers:** Detailed analysis of why customers are leaving, filtered by contract type and payment method.

## Key Findings
Based on the analysis of 100,000 customers, the overall retention rate sits at 66.86%, with an average revenue per user (ARPU) of $79.97. The overall churn rate is high at 33.14%.

When analyzing the drivers of this churn, **Contract Type** emerged as the strongest indicator of customer retention risk. Customers on Month-to-Month contracts Account for 55,000 users (roughly 55% of the total base) and experience a significantly higher churn rate—nearly 50% of these users churn. Conversely, customers secured on 1-year and 2-year contracts show almost zero churn, indicating that long-term commitments successfully stabilize the user base. 

Furthermore, **Payment Method** plays a notable role in attrition. Users paying via Electronic Check represent the largest single payment cohort, but they also contribute to the highest volume of churned customers compared to Credit Card, Bank Transfer, or Mailed Checks. To improve retention, the business should focus on heavily incentivizing Month-to-Month users paying via Electronic Check to transition into 1-year contracts with automatic bank transfers.

## Screenshots


![Overview Dashboard](Overview.png)
![Customer Segments](Customer_Segments.png)
![Churn Drivers](Churn_Drivers.png)
