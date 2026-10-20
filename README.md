

# Ecommerce Sales Analysis Dashboard

An interactive Excel dashboard that gives a single view of sales, profit, order volume and margin for an ecommerce business, with filters for year, region and customer segment.



## Overview

Transaction-level sales data is hard to read on its own. This dashboard turns it into a one-screen summary so a manager can answer quick questions without rebuilding reports:

- How are Sales, Profit, Quantity, Orders and Profit Margin doing, and how do they compare with last year?
- Which months are strongest and weakest?
- Which categories, sub-categories and US states drive the business?
- Does the picture change by year, region or customer segment?

## Dashboard Contents

| Section | What it shows |
| --- | --- |
| KPI cards | Sales, Profit, Quantity, No. of Orders and Profit Margin, each with YoY growth and a trend line |
| Sales and Profit Analysis | Monthly combo chart (Jan to Dec): Sales as columns, Profit as a line on a secondary axis |
| Category Wise Analysis | Waterfall-style chart of category contribution to the total |
| Category Wise Sales Share | Donut chart for Furniture, Office Supplies and Technology |
| Sales by State | Filled map of US states with a colour scale |
| Top 10 Sub-Categories | Ranked bar chart by Sales (Phones, Machines, Chairs, Bookcases, Storage and others) |
| Filters | Slicers for Year (2011 to 2014), Region (Central, East, South, West) and Segment (Consumer, Corporate, Home Office) |

All visuals respond to all three slicers at the same time.

## KPI Definitions

| KPI | Calculation |
| --- | --- |
| Sales | Sum of Sales |
| Profit | Sum of Profit |
| Quantity | Sum of Quantity |
| No. of Orders | Distinct count of Order ID |
| Profit Margin | Profit / Sales |
| YoY Growth | (Current year - Previous year) / Previous year |

## Tools and Techniques

- **Microsoft Excel**: PivotTables, PivotCharts, slicers, map chart, conditional formatting
- **Data cleaning**: removing duplicates, fixing data types, creating Year and Month fields
- **Dashboard design**: dark theme, KPI cards on top, charts in a grid, filters on the right

## How to Use

1. Download the workbook from this repository and open it in Excel 365 (the map chart needs Excel 365 with Bing Maps support).
2. Use the slicers on the right to filter by Year, Region and Segment.
3. After updating the source data, go to **Data > Refresh All** so every PivotTable and chart updates.

## Project Structure

```
.
├── Ecommerce_Sales_Dashboard.xlsx   # Workbook with data, pivots and dashboard
├── BRD_Ecommerce_Sales_Dashboard.docx   # Business Requirements Document
├── images/
│   └── dashboard.png                # Dashboard screenshot
└── README.md
```

.

## Possible Next Steps

- Show "N/A" instead of an error on YoY cards when no previous year exists
- Add a "last refreshed" note on the dashboard
- Rebuild the same dashboard in Power BI or Tableau
- Add customer-level and product-level drill-through pages

## Author

**Mohammad Shahid**
Data Analyst | SQL, Python, Power BI, Excel, Tableau

- GitHub: [github.com/ShahidMullaji](https://github.com/ShahidMullaji)
- LinkedIn: [linkedin.com/in/mohammad-shahid-7bba45290](https://linkedin.com/in/mohammad-shahid-7bba45290)
- Email: shahidmulla2713@gmail.com
