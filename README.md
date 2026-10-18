SWYNEX Final Data Analytics Project

Project Overview

This project brings together my data analytics work completed during my internship with SWYNEX Technologies. It covers data cleaning, exploratory data analysis, and interactive sales dashboard development.

Project Objectives

- Clean and prepare retail sales data.
- Analyze sales trends and patterns.
- Identify top-performing products and countries.
- Present insights through an interactive Power BI dashboard.

Dataset Information

- Dataset Name: Online Retail Dataset
- Dataset Type: Retail transaction data
- Key Columns: Invoice Number, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country.
- Original Dataset Size: 541,909 rows.
- Cleaned Dataset Size: 401,564 rows.
- Data Source: The dataset used in this project was provided as an Online Retail dataset for analysis.

Data Cleaning Process

The dataset was cleaned and prepared using Python and Pandas.

The following steps were performed:

1. Duplicate Removal: Removed 5,268 duplicate records.
2. Missing Descriptions: Replaced 1,454 missing Description values with "Unknown".
3. Missing Customer IDs: Removed rows with missing CustomerID values.
4. Zero Unit Prices: Removed 40 records with zero UnitPrice values after filtering missing CustomerIDs.
5. Negative Quantities: Retained negative quantities because they may represent product returns or cancelled transactions.
6. Data Type Validation: Checked the data types of all columns.
7. Data Consistency Checks: Checked Country and StockCode values for missing or obvious formatting inconsistencies.

After cleaning, the dataset contained 401,564 rows and was ready for exploratory data analysis and dashboard development.

Tasks Completed

Task 1: Data Cleaning and Preparation

Cleaned and prepared the retail dataset using Python and Pandas.

"View Task 1 Repository" (https://github.com/Smitarai144/SWYNEX-Data-Cleaning-Preparation)

Task 2: Exploratory Data Analysis (EDA)

Analyzed sales trends, monthly revenue, transactions, top products, and country-wise performance using Python, Pandas, and Matplotlib.

"View Task 2 Repository" (https://github.com/Smitarai144/SWYNEX-Exploratory-Data-Analysis)

Task 3: Interactive Sales Dashboard

Created an interactive sales dashboard using Microsoft Power BI.

"View Task 3 Repository" (https://github.com/Smitarai144/SWYNEX-Interactive-Dashboard/tree/main)

Task 4: Final Data Analytics Project

Combined the project workflow, analysis, dashboard reference, and business findings into a final case study.

Tools and Technologies

- Python
- Pandas
- Matplotlib
- Microsoft Power BI
- GitHub

Key Analysis Areas

- Monthly revenue trends
- Monthly transaction trends
- Top 10 products by revenue
- Country-wise revenue
- Sales performance insights

Key Business Insights

1. The UK Dominates Sales

The United Kingdom accounted for approximately 81.5% of calculated revenue, making it the largest market in the analysis.

2. November 2011 Had the Highest Transaction Activity

November 2011 recorded approximately 64,218 transaction records, the highest monthly activity in the analyzed period.

3. November 2011 Generated the Highest Monthly Revenue

Calculated revenue in November 2011 was approximately £1.13 million.

4. Negative Quantities May Indicate Returns or Cancellations

The dataset contained 8,872 records with negative quantities, with a combined quantity of approximately -273,035 units. These records may represent returns, cancellations, or adjustments.

5. Extreme Values Require Further Investigation

Quantity values ranged from approximately -80,995 to 80,995, while unit prices ranged from £0.001 to £38,970. These unusual values should be investigated before making business decisions based on them.

Business Recommendations

- Monitor sales performance in the UK and other markets.
- Study seasonal sales patterns, particularly the November peak.
- Investigate negative-quantity records to understand returns and cancellations.
- Validate extreme quantities and prices before using them in business reports.
- Use the Power BI dashboard to monitor revenue, transactions, products, and country performance.

Conclusion

This project demonstrates a complete data analytics workflow, from data preparation and exploratory analysis to dashboard-based presentation of business insights.

Internship: SWYNEX Technologies
