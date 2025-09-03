-- Telecom Customer Churn Analysis --

-- Project Overview:

This project analyzes customer churn in the telecom industry using SQL for data cleaning & transformation and Power BI for visualization.
The dataset contains 6,418 customer records with demographics, service usage, billing details, and churn reasons.

The goal is to identify key churn drivers and provide business insights to improve customer retention.

-- Dataset info:

Rows: 6,418
Columns: 32

Key Features:

Customer_ID, Gender, Age, Married, State
Tenure_in_Months, Phone_Service, Internet_Type
Online_Security, Streaming_TV, Device_Protection_Plan
Payment_Method, Monthly_Charge, Total_Revenue
Customer_Status (Stayed, Churned, Joined)
Churn_Category, Churn_Reason

-- Data Cleaning & Transformation (MySQL):

✔️ Removed duplicates & handled missing values
✔️ Converted data types (e.g., Total_Charges → FLOAT)
✔️ Created derived features:
Churn Flag (Yes/No)
Tenure Bins (<6m, 6–12m, 1–2y, 2+ years)
Revenue Segments
✔️ Used CASE, JOINS, GROUP BY, and CTEs for summary aggregations

-- Power BI Dashboard Features:
Overall Metrics:

Total Customers: 6,418
Churned: 1,732 (27%)
New Customers: 411
Churn by Demographics: Gender & Age Group

Churn by Contract & Payment:

Month-to-Month contracts → 46.5% churn
Mailed Check payments → 37.8% churn
Churn by Internet Type: Fiber optic users → 41.1% churn
Churn by State: Jammu & Kashmir (57.2%) highest churn
Churn Reasons: Competitor (44%), Dissatisfaction (28%), Attitude (18%)
Interactive slicers for Monthly Charges, Tenure, Marital Status

-- Tools & Skills Applied:

SQL (MySQL): Data cleaning, transformation, aggregation
Power BI: Dashboard design, DAX measures, interactive reports
Data Analytics Workflow: Raw data → cleaned dataset → visual insights
Business Intelligence: Identifying churn patterns & retention strategies

-- Key Insights:

Long-term contracts (1–2 years) reduce churn significantly.
Customers paying via Credit Card/Auto Payment show higher retention.
Fiber optic customers report high dissatisfaction → service quality needs improvement.
Competitor offers are the top churn reason → loyalty strategies are critical.

-- Author: Posham Chanikya
-- Linkedin: https://www.linkedin.com/in/chanikya-posham-747489227/
-- Github: https://github.com/Chanikya0309

