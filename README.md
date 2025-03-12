# Sales And Financial Analysis in Excel

This project involves advanced Excel based financial and sales analysis for AtliQ Hardwares, a company with sell Computer hardware to wordwide customers. The goal was to extract, transform, and analyze the data from the year 2019 to 2021 to generate insightful reports that help in decision-making.

<b>Reports Created</b>
+ Customer Performance Report: Analyzes net sales per customer for 2019, 2020, and 2021 with year-over-year comparisons.<br><br>
+ Market Performance Report: Evaluates country-wise net sales from 2019 to 2021 and compares them against 2021 targets.<br><br>
+ Profit and Loss (P&L) by Fiscal Year: calculates yearly Profit & Loss (P&L) reports for fiscal year 2019 to 2021.<br><br>
+ Profit and Loss (P&L) by Fiscal Quarters: Quarterly Profit & Loss breakdown,year over year comparison from 2019 to 2021<br><br>


<b>Data Processing Steps</b> <br><br>
<b>Situation:</b><br>
AtliQ had sales, expense, and dimensional data spread across multiple Excel files. They needed structured reports to assess financial and sales performance over time.

<b>Task:</b><br>
The objective was to clean, transform, and consolidate data from different sources into structured Excel reports using Power Query, Power Pivot, and DAX.

<b>Actions:</b><br>
   Imported 5 CSV files (customers, markets, products, sales data, net sales targets).  
   Used Power Query to clean inconsistencies (e.g., misspellings, incorrect letter casing, missing region values).
  
<i>Data Modeling:</i><br>
   -Implemented a Star Schema in Power Pivot by connecting fact tables to dimension tables.<br>
   -Created a date dimension table (2018–2021) with fiscal year calculations (AtliQ's fiscal year starts in September).<br><br>
<i>Customer Performance Report:</i><br>
   -Used Pivot Tables to display net sales per customer for 2019, 2020, and 2021.<br>
   -Created DAX measures for year-over-year growth calculations.<br><br>
<i>Market Performance Report:</i><br>
   -Filtered net sales by country and fiscal year.<br>
   -Compared 2021 sales with targets.<br><br>
<i>Financial Reports</i>
<i>Expense Data Integration:</i><br>
   -Integrated freight and manufacturing costs from a separate dataset into the existing model.<br>
   -Created DAX measures for COGS, Gross Margin, and Gross Margin %.<br><br>
<i>Yearly & Quarterly P&L Reports:</i><br>
   -Aggregated Net Sales, COGS, Gross Margin, and Gross Margin % by year and quarter. <br>
   -Used conditional formatting for visual insights.<br>
   -Applied error handling in DAX to prevent calculation failures due to division by zero.<br><br>
<i>Quarterly Sales Analysis:</i><br>
   -Derived quarter names dynamically using Power Pivot formulas (e.g., ROUNDUP(Month/3)).<br>
   -Created monthly breakdowns for year-over-year performance comparisons.</p>

<p><b>Results & Insights</b><br>
 -Provided customer-level and market-level sales trends to track performance.<br>
 -Enabled year-over-year and quarter-over-quarter financial comparisons.<br>
 -Ensured data integrity and accuracy through Power Query transformations.<br>
 -Optimized dynamic reports using DAX measures and Pivot Tables.</p>
<b>Tech Stack Used</b> <br>
✅ Excel (Power Query, Power Pivot, DAX, Pivot Tables)<br>
✅ Data Modeling (Star Schema)<br>
✅ Advanced Formulas & Conditional Formatting<br><br>


<b>Fiscal Year Definition</b><br>
<i>AtliQ Hardwares' fiscal year starts in September and ends in August.</i>

# Report Links
+ [Customer Performance Report](customers_net_sales_performance_report_excel.pdf)<br>
+ [Market Performance Report](market_performance_versus_target_report_sales_in_excel.pdf)<br>
+ [Profit and Loss (P&L) by Fiscal Year](P&L_by_month.pdf)<br>
+ [Profit and Loss (P&L) by Quarter](P&L_yearly.pdf)<br>
# Future Enhancements
    -Automate reports using Power BI for better visualization.<br>
    -Integrate with SQL databases for real-time data updates.<br>












