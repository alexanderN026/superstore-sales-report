# Sales Performance Report

![Report screenshot](/report/Sales_Data_Report_screenshot.png)

## Project Summary
This project analyzes sales data from 2011 to 2014 from the Kaggle Superstore dataset, covering about 5,000 orders and $2.3M in revenue. I prepared the data in Google Sheets, explored it with pivot tables, and built an Power BI Report to track revenue, profit, regional performance. The analysis shows that profit grew faster than revenue, but Furniture and the Central region earn much less profit than their sales suggest.

## Business Problem
- Are revenue and profit growing, and when do sales peak?
- Which categories, sub-categories, and products drive revenue and profit?
- Which regions perform best and worst?
- How do discounts relate to profit?

## Approach
1. Imported the Kaggle Superstore dataset into Google Sheets
2. Duplicated imported sheet and added new columns
3. Explored the data with pivot tables
4. Built an Power BI report
5. Wrote an insight summary with recommendations

## Key insights
1. **Revenue depends heavily on Q4:** November and December generate about 30% of annual revenue every year.
2. **Technology leads in profit:** It generates about 50% of total profit, while Furniture earns less than 10% with a profit margin of about 6%.
3. **Regions have different problems:** Central generates 22% of revenue but only 14% of profit, while South has a healthy margin with low sales at 17% of revenue.

Full write-up: [Insight Summary (PDF)](./docs/Sales_Insight_Summary.pdf)

## KPIs Tracked
- Total profit
- Total Revenue
- Products Sold
- Average Order Revenue
- Month over Month Revenue Growth

## Tools used
- **Google Sheets:** data preparing and pivot tables
- **Power BI Desktop:** data model, DAX measures, report

## Dataset
[Superstore Sales (Kaggle)](https://www.kaggle.com/datasets/ishanshrivastava28/superstore-sales/data) by Ishan Shrivastava, licensed under [Database Contents License (DbCL) v1.0](https://opendatacommons.org/licenses/dbcl/1-0/)

## Files
- `data/raw_data.csv`: original dataset, unchanged
- `data/stage_data.csv`: prepared dataset used in Power BI
- `analysis/pivot_analysis.xlsx`: pivot tables
- `report/Sales_Data_Report.pbix`: Power BI File, that requires Power BI Desktop on Windows
- `report/Sales_Data_Report_screenshot.png`: report preview
- `docs/Sales_Insight_Summary.pdf`: one-page insight summary