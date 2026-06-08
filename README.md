# Excel_SQL_CRM- TechFlow CRM Analyses
### End-to-end CRM data analysis project for a B2B SaaS company, focusing on data cleaning, revenue performance, churn analysis, and pipeline forecasting using Excel and SQL. This project analyses CRM data from a B2B SaaS company to investigate a recent revenue decline, understanding the cause and determining next steps using data.

## Business Problem: TechFlow Solutions experienced a significant revenue shortfall in the second half of 2024:
- Revenue fell 18% below target in Q3 2024
- Revenue fell a further 11% in Q4 2024
The leadership team does not yet know the root cause of this decline.
Possible causes include:
- Low lead quality (pipeline problem)
- Poor conversion rates (sales performance issue)
- High customer churn (retention issue)
- Weak pipeline forecasting
The aim of this project is to identify the key factors that caused revenue decline and provide actionable insights.

## Files in this repo
### Excel File: TechFlow_CRM_Dataset_and_Analysis
This contains 7 sheets: 
CRM Raw Export: This contains the raw, dirty data with all the empty cells and spelling inconsistencies.

Data Dictionary: This contains the description of all the fields in the dataset, their data type, and all the things to note about each field.

Data Cleaning Log: This sheet contains all the data cleaning steps taken to assess data quality and prepare the dataset for proper analysis.

Working Data: Cleaned dataset

KPI Analyses: This sheet contains the analyses carried out to answer 4 out of the 5 business questions. For each question, there are manual range tables and pivot tables to answer the same questions. The sections included are: revenue by lead sources (Q1), sales reps' win rates (Q2), revenue by product tier (Q4), revenue by contract type (Q4), and sales pipeline analysis (Q5).

Churn Analysis: This sheet contains answers to the 3rd business question. It contains sections on annual churn rate, churn by product tier, lead sources, company size category, and country. It also contains an analysis of customer satisfaction and retention. Most of the answers were obtained using a pivot table. 

Dashboard: Contains KPI cards, bar charts, line charts, doughnut charts, pivot tables and slicers that present answers to the business questions at a glance.
