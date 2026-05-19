# RFM-Analysis-using-SQL-Big-Query-Power-BI
Performed RFM (Recency, Frequency, Monetary) analysis on customer purchasing behavior to identify customer segments, improve targeted marketing, and support customer retention decisions.
 ## Project Overview / Introduction
This project focuses on customer segmentation using the RFM (Recency, Frequency, Monetary) technique to support targeted marketing and customer retention strategies. Many businesses struggle to identify high-value customers, improve customer retention, and optimize marketing efforts. By analyzing customer purchasing behavior using RFM analysis, this project will help the business in making a more data-driven decision.

## Business Problem / Objective
The company wants to segment their 2025 customers based on their purchase behavior & segment them into 10 segments for better granularity using the following steps;
- Calculate RFM values
-	Assign decile scores
-	Compute Aggregate RFM scores
-	Define RFM segments
-	Build Power Bi report

________________________________________
## Dataset Overview
The dataset contains 12 monthly CSV files of customer purchases which contains data that will enable us get how recently a customer made a purchase, how frequent they purchase & the revenue they bring into the business.
###  Table Structure
Key Columns
- customer id
- order_date 
- order_id 
- order_value
- product_type
  
  ###  Dataset Purpose
The dataset was designed to support customer behavior analysis through the RFM framework by tracking:

- How recently customers made purchases (Recency)
- How often customers purchased (Frequency)
- How much revenue customers brought in (Monetary)

  ###  Notes
  - The presence of customer_id allows transactions to be aggregated per customer, which is essential for customer segmentation.
  - Since the dataset contains order_date and order_id, it can track purchasing timelines and buying behavior over time.
  - order_value enables analysis of customer revenue contribution and identification of high-value customers.
 
  **Dataset Link:**
  [user_events](https://docs.google.com/spreadsheets/d/1qq04-TKpxHvDxcodKvjDDm2m-qgftMvjdXkBGbltURk/edit?usp=sharing)


- ## Tools & Technologies

- PostgreSQL
- BigQuery
- Power BI
- Excel
- Git & GitHub

  ## Methodology

1.	Upload sales data to Big Query
2.	Calculate RFM values
3.	Assign decile scores
4.	Compute Aggregate RFM scores
5.	Define RFM segments
6.	Build Power Bi report

## Key Questions Answered

- Who are the most valuable customers?
- Which customers are at risk of churning?
- Which customer segments generate the most revenue?
- Which customers require re-engagement campaigns?
- How can customer groups be segmented based on purchasing behavior?

## SQL Techniques Used


## SQL Techniques Used

- data consolidation using UNION ALL
- Table Creation from Query Results (CREATE OR REPLACE TABLE)
- Views Creation (CREATE VIEW)
- aggregation functions (SUM, COUNT, MAX)
- date calculations (DATE_DIFF)
- window functions for ranking & bucketing (ROW_NUMBER, NTILE)
- Cmmon Table Expressions CTEs
- conditional logic (CASE statements)
- views to build an end-to-end RFM customer segmentation model.

## Dashboard Preview

![Dashboard](dashboard/RFM_png.png)




