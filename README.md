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

##Skills Demonstrated

Power BI data modelling (fact and dimension relationships)

Advanced DAX (weighted averages, time intelligence, profitability measures)

Interactive visuals (slicers, drilldowns, Smart Narrative)

Business storytelling — linking analytical outputs to commercial insights


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

## Page 2 – Cost & Lifecycle Analysis
**Weighted Cost vs Price Trend:** Tracks per-unit cost and selling price to reveal margin movement over time.  
**Top and Bottom 10 products
**Product Lifecycle Trend:** Shows category sales evolution, identifying mature vs growth product lines.  
Key insight – Price–cost gap narrowed in 2019, and Accessories continue steady long-term growth.(screenshots/Cost_vs_Price_and_Lifecycle.png)

## Page 3 - Discount & Price Impact
This analysis explores how pricing and discounting behaviour affects profitability across product categories from 2017–2020.
Key measures such as Average Discount %, Profit Margin %, and Actual Selling % were created using DAX to simulate real business pricing scenarios.

🔹 Findings

Accessories maintained the highest profit margins despite moderate discounting, suggesting strong price resilience.

Bikes showed the largest discount activity and the greatest margin sensitivity, higher sales volumes but thinner margins.

Clothing had the steepest average discount rate (~15%) and the lowest margin contribution.

Over time, discounting remained consistent, but the profit margin recovery lagged, indicating room to improve pricing discipline.

Techniques used: DAX calculations (weighted averages, simulated discount column, YoY measures), Smart Narratives, multi-metric visuals (bubble, combo, stacked bar).

## Page 4 - Reseller & Regional Sales Intelligence
This page visualises where and what products were sold globally, highlighting regional performance and profit contribution.

Findings

Australia and the U.S. Southwest lead global sales, driven primarily by Bike sales, accounting for over 50% of total revenue.

Europe (particularly Germany and France) delivers smaller volumes but higher profit margins, showing efficient operations.

California, New South Wales, and England rank as the most profitable states.

Accessories perform strongly across all regions, while Bikes dominate APAC.

Techniques used: Map visualisations (country/state), matrix with conditional formatting, DAX KPIs for total sales and profit margin, and dynamic ranking for top regions.
