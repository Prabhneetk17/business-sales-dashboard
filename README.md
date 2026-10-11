# 📊 Business Sales Performance Dashboard | Microsoft Excel

## Project Overview

An interactive sales analytics dashboard built using Microsoft Excel to evaluate business performance across regions, product categories, sub-categories, and discount levels.

The project analyses historical Superstore sales data from 2014–2017 to identify profitability patterns, understand regional performance, and highlight areas that may require further business investigation.

## 🎯 Business Problem

Sales teams need more than total revenue figures to evaluate business performance. High sales do not necessarily translate into high profits, and aggressive discounting may be associated with lower profitability.

This project addresses the following business questions:

- Which regions generate the highest sales and profit?
- How do sales change over time?
- Which product categories and sub-categories contribute most to profitability?
- How does profitability vary across discount bands?
- Which areas should management investigate to improve business performance?

## 🛠️ Tools and Techniques

- **Microsoft Excel**
- Excel Tables and structured references
- PivotTables and summary tables
- SUMPRODUCT and calculated fields
- Percentage and currency calculations
- Column, line, pie, and bar charts
- Dashboard design and business interpretation

## 📈 Key Performance Indicators

Based on the current workbook:

| Metric | Result |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Overall Profit Margin | 12.47% |
| Order-Line Records | 9,994 |
| Average Sales per Record | Approximately $230 |
| Regions | 4 |
| Period Covered | 2014–2017 |

*Note: The dataset contains 9,994 order-line records. These should not be interpreted as 9,994 unique orders without checking distinct order IDs.*

## 🔍 Analysis and Findings

### 1. Regional Performance

Compared sales and profit across the East, West, Central, and South regions to identify differences in regional contribution and profitability.

### 2. Monthly Sales Trends

Visualised monthly sales from 2014 to 2017 to examine fluctuations and changes in sales performance over time.

### 3. Category-Level Sales Mix

Compared Furniture, Office Supplies, and Technology to understand how each category contributes to total sales.

### 4. Sub-Category Profitability

Examined profit across product sub-categories to identify stronger and weaker performers, including sub-categories with negative aggregate profit.

### 5. Discount and Profitability Analysis

Grouped transactions into discount bands and compared total sales, total profit, record counts, and profit margins.

The current analysis shows:

- **0%–20% discount:** approximately $421,773 in profit, with a 21.8% profit margin.
- **Above 20%–40% discount:** approximately $35,817 in losses, with a −15.3% profit margin.
- **Above 40% discount:** approximately $99,559 in losses, with a −77.4% profit margin.

These results identify an association between higher discount bands and weaker profitability in this dataset. They do not establish that discounts alone caused the losses; product mix, costs, and other factors may also contribute.

## 💡 Business Recommendations

1. **Investigate high-discount transactions:** Review products, order sizes, and customer segments associated with the largest losses.
2. **Review product-level profitability:** Identify products with recurring negative profits and investigate pricing, costs, and discount policies.
3. **Compare regional performance:** Examine differences in profit margins and product mix before deciding where to focus sales initiatives.
4. **Monitor profitability alongside revenue:** Track profit margin and total profit instead of evaluating performance using sales alone.
5. **Validate discount decisions:** Use transaction-level analysis and, where possible, further statistical testing before changing discount policies.

## ⚙️ Methodology

1. Inspected the source sales data and its fields.
2. Added a discount-band classification to group transactions by discount level.
3. Summarised sales, profit, and record counts using PivotTables.
4. Calculated profit margins using profit divided by sales.
5. Built charts to compare regional performance, sales trends, category mix, sub-category profitability, and discount-band profitability.
6. Interpreted the results to identify areas for further business investigation.

## ⚠️ Limitations

- The analysis is descriptive and does not establish causal relationships.
- Profitability differences across discount bands may reflect product mix, costs, or other underlying factors.
- Monthly trends do not independently establish seasonality or explain the causes of sales fluctuations.
- Order-line counts are not equivalent to unique order counts.
- Recommendations should be validated against additional business context before implementation.

## 📂 Repository Contents

- `BusinessSalesDashboard_Updated.xlsx` — Excel workbook containing the dashboard, source data, and supporting analyses.
- `images/dashboard.png` — Dashboard screenshot for quick review.

*Update these filenames to match the actual files uploaded to the repository.*

## 👩‍💻 Author

**Prabhneet Kaur**

- GitHub: [PrabhneetK17](https://github.com/PrabhneetK17)
- LinkedIn: [Prabhneet Kaur](https://www.linkedin.com/in/prabhneet-kaur2003/)

## 📌 Project Objective

This project demonstrates practical use of Excel for data summarisation, visualisation, KPI reporting, and exploratory business analysis.
