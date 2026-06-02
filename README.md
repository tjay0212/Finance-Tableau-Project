# Superstore Sales & Profit Dashboard — Tableau

An interactive Tableau dashboard analysing sales, profit, and regional performance for a US retail company across Furniture, Office Supplies, and Technology categories (2019–2022).

**[View Live Dashboard](https://public.tableau.com/views/SuperstoreSalesProfitAnalysis_17803611716750/SuperstoreSalesProfitAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## Objective

To identify which products, regions, and customer segments drive the most revenue and profit — and which are underperforming despite high sales volume.

---

## Dashboard Preview

![alt text](https://github.com/[tjay0212]/[Finance-Tableau-Project]/blob/[branch]/image.jpg?raw=true)

---

## Key Findings

- Overall profit margin is 12.56% on $2.3M in total sales
- Texas and Illinois generate high sales but run at a loss — driven by excessive discounting
- Tables and Bookcases are the least profitable sub-categories despite strong sales
- Copiers have the highest profit ratio of any sub-category
- Technology drives the sharpest seasonal spike every November/December
- The West region is the most profitable region overall

---

## Dashboard Features

- 3 KPI tiles — Total Sales, Total Profit, Overall Profit Ratio
- US profit map — bubble size = sales volume, colour = profit (red = loss, blue = profit)
- Sub-category bar chart — sales ranked by category with profit ratio colour coding
- Monthly sales trend — line chart split by category showing seasonality
- Sales vs Profit scatter — identifies high-sales/low-profit outliers
- Interactive filters — click any chart to filter the entire dashboard

---

## Tools & Skills Used

| Tool | Usage |
|---|---|
| Tableau Desktop / Public | Dashboard design and publishing |
| Calculated Fields | Profit Ratio = SUM(Profit) / SUM(Sales) |
| Dashboard Actions | Click-to-filter interactivity across all charts |
| Map Visualisation | Geographic profit analysis by US state |
| Colour Diverging Palette | Instant visual of profitable vs loss-making areas |

---

## Files in This Repository

```
├── Superstore_Dashboard.twbx   # Packaged Tableau workbook (open in Tableau Public)
├── README.md                   # This file
```

---

## How to Open Locally

1. Download Tableau Public (free) from public.tableau.com
2. Clone or download this repository
3. Open Superstore_Dashboard.twbx in Tableau Public
4. The full dashboard loads with all data included

---

## Data Source

Sample - Superstore — Tableau's built-in fictional US retail dataset (~10,000 order rows covering 2019–2022). Includes orders, returns, and regional manager data across 3 product categories and 17 sub-categories.

---

## About

Built as part of a 5-project finance and analytics portfolio.

Other projects in this portfolio:
- [Apple Financial KPI Dashboard — Excel](../excel)
- Market Analysis Report — coming soon
- Python Stock Analysis — coming soon
- 3-Statement Financial Model + DCF — coming soon
