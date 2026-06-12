# Superstore Sales and Profit Dashboard

A Power BI report built on the Sample - Superstore dataset, providing interactive insights into sales performance, profitability, and discount trends across product categories and regions.

## File

| File | Description |
|------|-------------|
| `biproject.pbix` | Power BI Desktop report file |

## Report Pages

### Page 1: Sales Overview

A high-level snapshot of overall business performance:

- KPI Cards: Total Sales, Total Profit, Average Discount
- Pie Chart: Sales breakdown by product category
- Line Chart: Sales trend over time with a Year / Quarter / Month / Day hierarchy
- Clustered Column Chart: Sales by sub-category
- Table: Category-level detail
- Slicer: Filter all visuals by region

### Page 2: Profit Analysis

A deeper look at profitability across segments:

- KPI Cards: Total Sales, Total Profit, Average Discount
- Clustered Bar Chart: Total Profit by region
- Column Chart: Total Profit by sub-category
- Donut Chart: Profit share by category
- Table: Category-level detail
- Slicer: Filter all visuals by region

## Key Measures

| Measure | Description |
|---------|-------------|
| `Total Sales` | Sum of all sales revenue |
| `Total Profit` | Sum of all profit |
| `Average Discount` | Mean discount rate across orders |

## Data Source

The report uses the Sample - Superstore dataset, a widely used retail dataset covering orders, customers, products, and geography across the United States.

Key fields include:

- Order Date: used for time-series analysis
- Category and Sub-Category: product hierarchy
- Region: geographic segmentation
- Sales, Profit, and Discount: core financial metrics

## Getting Started

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Clone or download this repository.
3. Open `biproject.pbix` in Power BI Desktop.
4. The report loads with the embedded dataset. No additional data connection is required.

## Requirements

- Power BI Desktop (April 2026 release or later recommended)
- No external data source connection needed; data is embedded in the `.pbix` file

## Notes
- The report was created in Power BI cloud using the April 2026 release.
- A custom theme is applied for consistent visual styling.
- All visuals support cross-filtering; clicking any chart element filters the rest of the page.

