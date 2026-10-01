# AdventureWorks Sales Dashboard (Power BI)

An interactive Power BI project analyzing sales, profit, costs, returns, and
product performance for **AdventureWorks Bike Shop**.

## Project Overview
This dashboard helps business leaders track performance across time, regions,
and product categories, and spot growth opportunities and return-rate issues.

## Key Metrics
| Metric | Value |
|---|---|
| Total Sales | 25M |
| Total Profit | 10M |
| Total Cost | 14M |
| Customers | 18K |
| Total Orders | 84K |
| Average Order Value (AOV) | 296 |
| Return Rate | 2.17% |

## Dashboard Pages
1. **Executive Summary**: KPIs, sales vs. orders trend, profit and profit margin by country, sales vs. cost, income level by gender
2. **Continent Analysis**: sales by continent, month-over-month (MoM) profit growth, orders by country
3. **Category Analysis**: profit by category, sales and return % by subcategory
4. **Selected Product**: monthly sales, orders, and profit vs. target, with a what-if adjustment parameter

## Screenshots
![Executive Summary](screenshots/01_executive_summary.png)
![Continent Analysis](screenshots/02_continent_analysis.png)
![Category Analysis](screenshots/03_category_analysis.png)
![Selected Product](screenshots/04_selected_product.png)

## Key Insights
- Bikes generate about 93% of total profit.
- The United States and Australia are the top profit-generating countries.
- Profit margin stays steady at around 42% across countries.
- Overall return rate is low at 2.17%.
- December shows the highest MoM profit growth (about 50%).

## Tools & Techniques
- Power BI Desktop
- DAX measures (MoM growth, profit margin, return %, AOV)
- Interactive slicers (Quarter, Year, Continent, Product)
- What-if parameter for profit adjustment
- KPI cards, gauges, combo charts, donut charts

## How to Use
1. Download `powerbi/adventureworks_sales_dashboard.pbix`
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the slicers to explore the data

## Author
**Nishant Pal**
