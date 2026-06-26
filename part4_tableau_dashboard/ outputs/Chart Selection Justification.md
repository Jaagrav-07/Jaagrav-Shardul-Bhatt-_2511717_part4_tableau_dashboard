## **Chart Selection Justification** 

This document explains the rationale behind each visualization used in the Tableau Executive Dashboard. 

## **1. Sales Trend View** 

## **Business Question** 

How are sales changing over time? 

## **Chart Type** 

## **Line Chart** 

## **Why This Chart** 

A line chart effectively displays trends and seasonal patterns across time, making it ideal for monitoring business growth. 

## **Fields Used** 

- **X-Axis:** Order Date 

- **Y-Axis:** Sales 

- **Filter:** Date, Region 

## **Design Principle** 

Chronological ordering emphasizes changes over time. 

## **Mistake Avoided** 

Avoided using bar charts, which make long-term trends more difficult to interpret. 

## **2. Regional Performance View** 

## **Business Question** 

Which regions contribute the most to sales and profit? 

## **Chart Type** 

## **Horizontal Bar Chart** 

1 

## **Why This Chart** 

A horizontal bar chart allows easy comparison of performance across regions. 

## **Fields Used** 

- **Category:** Region 

- **Measure:** Sales / Profit 

- **Color:** Profit 

- **Filter:** Category 

## **Design Principle** 

Bars are sorted from highest to lowest for rapid comparison. 

## **Mistake Avoided** 

Avoided pie charts because they make precise comparisons difficult. 

## **3. Category Profitability View** 

## **Business Question** 

Which product categories generate the highest profit? 

## **Chart Type** 

## **Bar Chart** 

## **Why This Chart** 

Bar charts clearly compare profitability between categories and sub-categories. 

## **Fields Used** 

- **Category** 

- **Sub-category** 

- **Profit** 

- **Filter:** Region 

## **Design Principle** 

Consistent color encoding improves readability. 

## **Mistake Avoided** 

Avoided stacked charts that reduce comparison accuracy. 

2 

## **4. Customer Segment View** 

## **Business Question** 

How do customer segments differ in business performance? 

## **Chart Type** 

## **Bar Chart** 

## **Why This Chart** 

The chart enables direct comparison of sales and profit across customer segments. 

## **Fields Used** 

- Customer Segment • Sales • Profit 

## **Design Principle** 

Consistent scaling allows fair comparisons. 

## **Mistake Avoided** 

Avoided unnecessary 3D effects that distort perception. 

## **5. Shipping Performance View** 

## **Business Question** 

Which shipping methods experience longer delivery times? 

## **Chart Type** 

## **Bar Chart** 

## **Why This Chart** 

Bars effectively compare average delivery performance across shipping modes. 

## **Fields Used** 

- Ship Mode 

- Delivery Days 

3 

## **Design Principle** 

Simple layout with clear labels minimizes cognitive load. 

## **Mistake Avoided** 

Avoided overly complex visualizations for a straightforward comparison. 

## **6. Discount vs Profit View** 

## **Business Question** 

How does discount affect profitability? 

## **Chart Type** 

## **Scatter Plot** 

## **Why This Chart** 

Scatter plots are the most appropriate visualization for identifying relationships between two numerical variables. 

## **Fields Used** 

- **X-Axis:** Discount 

- **Y-Axis:** Profit 

- **Color:** Category 

- **Filter:** Region 

## **Design Principle** 

Individual points reveal trends, clusters, and outliers. 

## **Mistake Avoided** 

Avoided line charts because discount values are independent observations rather than time-series data. 

## **7. Return Analysis View** 

## **Business Question** 

Which categories or customer segments have the highest return rates? 

## **Chart Type** 

## **Horizontal Bar Chart** 

4 

## **Why This Chart** 

Horizontal bars enable easy ranking of return rates across multiple categories. 

## **Fields Used** 

- Return Status 

- Category 

- Customer Segment 

## **Design Principle** 

Sorted categories highlight the highest-risk areas immediately. 

## **Mistake Avoided** 

Avoided pie charts because ranking is more important than showing proportions. 

## **Dashboard Design Principles** 

The Executive Dashboard follows established data visualization best practices: 

- Appropriate chart selection for each business question. 

- Consistent colors throughout the dashboard. 

- Clear hierarchy using KPI cards and supporting charts. 

- Minimal visual clutter. 

- Readable labels and descriptive titles. 

- Interactive filters for Region, Category, Customer Segment, Date, and Ship Mode. 

- Dashboard actions enable users to explore data dynamically. 

- Charts are sorted to improve comparison and interpretation. 

## **Conclusion** 

Each visualization was selected to answer a specific business question while maximizing clarity and minimizing unnecessary complexity. The dashboard combines appropriate chart types, interactive features, and consistent design principles to provide leadership with an effective decision-support tool for monitoring retail performance. 

5 

