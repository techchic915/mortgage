# 🏦 Mortgage Applicant Analysis Dashboard

### Overview

This project analyzes a fictional mortgage applicant dataset using Snowflake SQL and Microsoft Power BI. The objective was to simulate a real-world banking analytics workflow by importing data into a cloud data warehouse, performing SQL analysis, and building an interactive executive dashboard.

The dashboard helps identify trends in applicant income, credit quality, loan eligibility, and down payments to support lending decisions.

### Technologies Used
* Snowflake
* SQL
* Microsoft Power BI
* Power Query
* DAX

### Project Workflow
1. Imported a mortgage applicant CSV file into Snowflake.
2. Cleaned and explored the data using SQL.
3. Wrote analytical SQL queries using:
  * Aggregations
  * GROUP BY
  * HAVING
  * CASE statements
  * Window Functions
4. Connected Snowflake directly to Power BI.
5. Built an interactive dashboard using Power BI.
6. Created calculated columns and DAX measures to support business reporting.

# Dashboard Features

Executive KPIs
Total Applicants
Average Annual Income
Average Down Payment
Average Credit Score
Interactive Filters
Education
Area
Income Bracket
Credit Rating
Visualizations
Average Credit Score by Education
Average Down Payment by Area
Applicants by Income Bracket
Average Annual Income by Credit Rating
Average Maximum Loan Amount by Income Bracket
Business Questions Answered
How many mortgage applicants are included in the dataset?
What is the average annual income of applicants?
Which education level has the highest average credit score?
How do down payments vary across geographic areas?
How are applicants distributed across income brackets?
How does annual income relate to credit rating?
Which income bracket qualifies for the highest average loan amount?
SQL Concepts Demonstrated
SELECT
WHERE
ORDER BY
GROUP BY
HAVING
Aggregate Functions
CASE Statements
Window Functions
AVG() OVER()
FIRST_VALUE()
LAST_VALUE()
Power BI Concepts Demonstrated
Snowflake Connection
Import Storage Mode
DAX Measures
Calculated Columns
Conditional Logic
KPI Cards
Interactive Slicers
Dashboard Design
Data Visualization
Key Insights
Higher-income applicants generally qualify for larger mortgage amounts.
Applicants with stronger credit ratings also tend to have higher annual incomes.
Education level shows a positive relationship with average credit score.
Average down payments remain relatively consistent across geographic areas.
The Upper Middle Income segment represents the largest portion of applicants.
