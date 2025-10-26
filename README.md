# Bank Loan Report | SQL & Power BI

This is a comprehensive data analyst portfolio project in the financial domain designed to monitor and assess the bank's lending activities and performance through three dynamic and insightful dashboards built using Power BI and validated with SQL.

## Overview
This project is considered an advanced Data Analyst portfolio project within the financial domain, commonly used in real-time industries. The project's main goal is to transform raw financial loan data into actionable business intelligence for stakeholders.  
The project resulted in three distinct, interactive dashboards in Power BI, connected to an MSSQL database, providing different levels of analysis:
1. **Summary Dashboard (KPI Dashboard):** Focuses on high-level performance metrics and overall business health.
2. **Overview Dashboard:** Enables deep-dive analysis into data at a granular level using various charts to generate specific insights.
3. **Details Dashboard:** Provides a consolidated, row-by-row view (grid view) of all essential loan data for comprehensive inspection.

## Problem Statement
The bank required a comprehensive report to monitor and assess its lending activities and performance. This report needed to provide insights into key loan-related metrics and their changes over time (like Month-to-Date and Month-over-Month growth) to help the bank make data-driven decisions, track the loan portfolio's health, and identify trends to inform lending strategies.

## Dataset
- **Size:** Approximately 38,576 rows and 24 fields (columns).  
- **Key Fields:** ID (Loan ID), address_state, application_type, emp_length, loan_status (Charged Off, Current, Fully Paid), issue_date, loan_amount, total_payment, int_rate, and dti.  
- The dataset is sourced from financial loan data, also known as Bank Loan Data.

## Tools and Technologies & Method
**Tools & Technologies:**
- **SQL (MSSQL Server):** Used for data import, initial data management, querying, and establishing data validation results.
- **Power BI:** Used for connecting to the server, data modeling, calculating advanced DAX measures (especially Time Intelligence), and creating dynamic visualizations.

**Methodology:**
1. **SQL Setup and Data Import:** Import raw CSV data into MSSQL Server, create database and table, correct data types.  
2. **SQL Validation (Unit Testing):** Calculate all KPIs (Total Applications, Funded Amount, MTD, PMTD, Good/Bad Loan metrics) and save results in a Query Document.  
3. **Power BI Connection and Data Quality:** Connect Power BI to SQL Server and validate data quality using Power Query Editor.  
4. **Data Modeling:** Create Date Table using DAX (CALENDAR) and establish relationships. Create 'Good versus Bad Loan' grouping.  
5. **DAX Calculations:** Define all KPI measures and advanced Time Intelligence measures (MTD, PMTD, MoM).  
6. **Visualization and Dashboard Design:** Build Summary, Overview, and Details dashboards using interactive features like Field Parameters and Slicers.  
7. **Final Validation:** Cross-check Power BI dashboard results with SQL Query Document to ensure accuracy.

## Key Insights
- **Overall Performance:** Total Funded Amount ≈ 435M, Total Amount Received ≈ 473M.  
- **Monthly Trends:** Loan applications and funded amounts steadily increased month-over-month.  
- **Good vs Bad Loans:** ~86% applications are Good Loans; ~13.8% are Bad Loans, showing significant loss potential.  
- **Geographical Distribution:** States like California had the highest loan applications and funded amounts.  
- **Purpose & Term:** Most loans were for Debt Consolidation and 36-month terms.

## How to Run This Project
1. Set up MSSQL Server and import the loan dataset into a database (e.g., bank_loan_DB).  
2. Execute SQL validation queries (from Query Document) to confirm KPI calculations.  
3. Open Power BI Desktop and connect to the MSSQL Server.  
4. Create Date Table, establish relationships, and set up 'Good vs Bad Loan' grouping.  
5. Define DAX measures for core KPIs and Time Intelligence (MTD/MoM).  
6. Build the three dashboards integrating calculated measures and interactive features.  
7. Cross-check dashboard values with SQL query results for validation.

## Result and Conclusion
The project delivers a professional Bank Loan Report fully validated with SQL, enabling the bank to monitor loan performance and portfolio health.  
- Provides crucial insights such as Good vs Bad Loan distribution and financial losses due to defaulted loans.  
- Supports data-driven decision-making to adjust lending policies (e.g., reviewing DTI and credit scores).  
- Demonstrates advanced Power BI skills, including dynamic dashboards and interactive features for stakeholder exploration.

## Author and Contact
**Author:** Ishant Katiyar  
**Email:** ishantkatiyar68@gmail.com 
**Linkedin:** https://www.linkedin.com/in/ishantkatiyar/
