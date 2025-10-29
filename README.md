# Note: This portfolio is being updated daily (started on the 22nd Oct 2025).
More Power BI and SQL projects will appear here shortly follow along for updates!

# Portfolio
A collection of SQL, Python and powerBI analytics projects demostrating data cleaning, modelling and storytelling.

## Data & Tools
- Data : Udemy PowerBI  - From the complete Microsoft PowerBI Bootscamp
- SQL : Text Blob, ridge plot, violin polot and Matplot insights
- PowerBI : Created and DAX Measures, calculate and filtering, set up secrity levels to different insights / pages
- Microsoft Febric: published some insight to Microsoft Febric with security access
- Python: cleaned missing values, created



# Project -  Bike Co. Sales & Profitability (2017–2020)

## Problem
Leadership needs a clear view of revenue, profit, and margins across products, regions, and channels to decide where to invest, where to reduce discounting, 
and how to plan inventory.

## Data & Model
- Fact: Sales (order lines with quantity, price, discount, cost, date, product, customer, reseller, territory).
- Dimensions: Product, Customer, Reseller, Sales Territory, Date (generated).
- Star schema with single-direction filters; Date marked as Date table.

## Metrics
Net Sales, Units, Gross Profit, Gross Margin %, ASP, AOV, Discount Amount, YoY growth, 12-month running totals.

## Key Insights (example)
- E-bikes and Hybrid drove most profit growth in 2019–2020 while maintaining higher margin than other categories.
- Online/Reseller channel doubled revenue in 2020 but applied 3× higher discounts, cutting margin by ~5 pts.
- Europe contributed a smaller share of revenue but a larger share of profit due to stronger pricing power.

## Decisions Enabled
- Increase inventory allocation and paid campaigns for high-margin categories (E-bikes/Hybrid).
- Tighten discount policies for underperforming resellers; shift budget to partners with better unit economics.
- Prioritize European expansion and test price elasticity in North America for selected products.


## Page 1 – Executive Overview
Summarises 2017–2020 performance across all regions and categories.  
Southwest leads total sales, while Accessories deliver the strongest profit margin.  (screenshots/Executive_Overview.png)