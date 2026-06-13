# TASK-4-BLESSING-CHARLES-MBONG
Python-powered e-commerce data visualization workbook built with Pandas &amp; openpyxl. Features 7 chart types (bar, line, pie, stacked column) across 1,200 orders (2023–2025), covering revenue trends, product performance, payment methods, marketing channels &amp; order fulfilment. 

# PROJECT OVERVIEW

This project delivers a 7-chart interactive Excel workbook built entirely in Python, visualizing three years of e-commerce transaction data (2023–2025, n = 1,200 orders). Each chart was designed to answer a specific business question using the right chart type, following core data visualization principles.
# WORKBOOK STRUCTURE

|Sheet              |Chart Type    |Business Question                               |
|-------------------|--------------|------------------------------------------------|
|📊 Dashboard        |KPI Summary   |Top-line performance at a glance                |
|Revenue by Product |Horizontal Bar|Which products generate the most revenue?       |
|Revenue Trend      |Line Chart    |How has revenue trended monthly (2023–2025)?    |
|Payment Methods    |Grouped Column|Which payment method drives the most revenue?   |
|Order Status       |Pie Chart     |What is the health of order fulfillment?        |
|Referral Sources   |Column Chart  |Which marketing channel drives the most revenue?|
|Quarterly Revenue  |Grouped Bar   |How does revenue vary by quarter and year?      |
|Order Size Segments|Stacked Column|How are order sizes distributed across products?|
|🛠️ Tools & Methods  |Reference     |Tools used and visualization principles applied |

# KEY INSIGHTS
	•	Total Revenue: ₦1,264,761.96 across 1,200 orders (Avg. ₦1,053.97/order)
	•	Top Product: Chair (₦195,620) and Laptop (₦192,127) lead; Laptop commands the highest average order value (₦1,111)
	•	Top Channel: Instagram drove the most revenue (₦275,285 / 259 orders)
	•	Revenue Trend: 2023 was the peak year; 2024 dipped but recovered with a June 2024 record (₦68,069); 2025 shows a recovery trajectory
	•	Order Fulfillment Risk: Only 38.8% of orders have positive outcomes (Delivered + Shipped); 41.4% are Cancelled or Returned — a critical operational concern
	•	Payment Methods: Revenue is remarkably balanced across all 5 methods (spread of only ₦31,487), indicating no significant payment friction
	•	Seasonal Pattern: Q2 is consistently the strongest quarter across all years
	•	Order Size Mix: Medium orders (₦300–₦800) dominate across all product categories

# TOOLS &  TECHNOLOGY
  Tool                               |Purpose                                                    |
|-----------------------------------|-----------------------------------------------------------|
|*Python 3*                       |Primary scripting language                                 |
|*Pandas*                         |Data aggregation — groupby(), pivot(), value_counts()|
|*openpyxl*                       |Excel workbook creation, chart generation, and styling     |
|*BarChart / LineChart / PieChart*|openpyxl chart objects for all 7 visualizations            |
|*PatternFill / Font*             |Cell formatting — headers, KPI boxes, insight callouts     |
|*Excel Formulas*                 |Dynamic SUM/AVERAGE calculations (no hardcoded values)     |

# Visualization Principles Applied
	•	Form follows function — Business question defined before chart type selected
	•	Explanatory over exploratory — Charts titled with insights, not variable names
	•	Data-Ink Ratio (Tufte) — Gridlines, 3D effects, and decorative elements removed
	•	Zero-baseline axes — All bar/column charts start at 0 to prevent Lie Factor distortion
	•	Chart Selection Matrix — Bar = comparison | Line = trend | Pie = composition | Stacked = segment mix

  File                                |Description                                                                            |
|------------------------------------|---------------------------------------------------------------------------------------|
|P4_DataVisualization_Blessing.xlsx|Final deliverable — multi-sheet Excel workbook with 7 embedded charts and KPI dashboard|

# AUTHOR
Blessing Charles Data Analyst Intern — Decodelap Batch 2026  LinkedIn:https://www.linkedin.com/in/blessing-charles-b4877063 ·                                                                                                                    GitHub:
