# AtliQ Hardware — Business Analytics Report (Excel)
 
 
An end-to-end Excel analytics solution for **AtliQ Hardware**, a hardware manufacturing company, built to analyze sales performance, market performance, and profitability across customers, markets, divisions, and fiscal periods — starting from raw CSV files and ending in stakeholder-ready reports.
 
---
 
## 📌 Project Overview
 
AtliQ Hardware needed a business analytics report to evaluate:
- Sales performance by customer
- Market performance against targets
- Profitability (P&L) by division, fiscal month, and fiscal year
I took the data through the full analytics workflow — extraction, transformation, modeling, analysis, and report creation — with the final reports built to match a business mockup provided by stakeholders.
 
```
Raw CSV Data → Power Query → Data Model → Relationships → DAX Measures → PivotTables → Conditional Formatting → Business Report
```
 
---
 
## 🛠️ How I Built the Report
 
### 1. Data Extraction
- Extracted source data from CSV files
- Worked with separate **fact and dimension tables** rather than one flat dataset
### 2. Data Transformation & Cleaning
- Used **Power Query** to clean and transform source data
- Prepared tables for modeling and analysis
### 3. Data Modeling
- Loaded transformed tables into the **Excel Data Model**
- Established relationships between fact and dimension tables
- Added a dedicated **Date table** to support time-series and fiscal-period reporting
### 4. Measures & Analysis
Built **DAX measures** for key business metrics:
- Net Sales
- COGS
- Gross Margin / Gross Margin %
- Year-over-Year comparisons
- Target variance / Target variance %
### 5. Report Development
- Built reports using **PivotTables** connected to the Data Model
- Applied **conditional formatting** to surface performance differences
- Kept report structure aligned with the stakeholder-provided mockup
---
 
## 📊 Report Walkthrough
 
### 1. Customer Net Sales Performance
Customer-level sales performance comparing net sales across **2022, 2023, and 2024**, along with 2024 vs 2023 growth %.
 
**Answers:**
- Which customers contribute the most to net sales?
- Which customers experienced strong growth?
- Which customers may require further investigation?
![Customer Net Sales Performance](images/customer-net-sales-performance.png)
 
---
 
### 2. Market Performance vs Target
Market/country-level performance comparing actual 2024 net sales against the 2024 target.
 
**Includes:**
- Net Sales for 2022, 2023, 2024
- 2024 target variance & target variance %
- Market-level comparison
Conditional formatting highlights markets furthest from target, making underperformance easy to spot.
 
![Market Performance vs Target](images/market-performance-vs-target.png)
 
---
 
### 3. P&L by Fiscal years ( For Division)

Division-level Profit & Loss report at the fiscal-year level, tracking Net Sales, COGS, Gross Margin, and Gross Margin %.

Useful for identifying:

Yearly sales patterns across divisions
Changes in gross margin
Periods of stronger/weaker profitability
Differences in performance across divisions

![P&L by Fiscal Months](images/pl-by-fiscal-division.png)
 
---
 
### 4. P&L by Fiscal Years ( Quarter Level)


Quarter-level Profit & Loss summary within each fiscal year — a higher-level view of Net Sales, COGS, Gross Margin, Gross Margin %, and YoY performance.
 
![P&L by Fiscal Years](images/pl-by-fiscal-years.png)
 
---
 
## 🧰 Excel Skills Demonstrated
 
| Category | Skills |
|---|---|
| **Data Preparation** | Power Query, data cleaning & transformation, fact/dimension datasets |
| **Data Modeling** | Excel Data Model, table relationships, Date table, fiscal-period analysis |
| **Analysis** | PivotTables, DAX measures, YoY analysis, Target vs Actual, customer/market/division-level analysis |
| **Reporting** | Conditional formatting, business-focused report layouts, mockup implementation, KPI reporting |
 
---
 
## 🎯 Key Takeaway
 
This project wasn't just about creating PivotTables — it was about building a complete reporting flow where raw CSV data could be transformed, modeled, analyzed, and presented in a format business stakeholders could actually use to evaluate sales and profitability.
 
---
 
## 🧑‍💻 Tools Used
 
`Microsoft Excel` · `Power Query` · `Excel Data Model / Power Pivot` · `DAX` · `PivotTables` · `Conditional Formatting`
 
