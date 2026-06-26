# Tableau Executive Dashboard & Data Storytelling

## Project Overview

This project presents an interactive **Tableau Executive Dashboard** designed to help retail leadership monitor business performance and support data-driven decision-making. The dashboard combines sales, profitability, customer behavior, shipping performance, discount analysis, and return patterns into a single executive reporting solution.

The objective is to identify business opportunities, operational risks, and performance trends through interactive visualizations and KPI monitoring.

---

# Repository Structure

```text
part4_tableau_dashboard/
│
├── data/
│   └── dashboard_sales_data.xlsx
│
├── tableau/
│   └── executive_dashboard.twbx
│
├── outputs/
│   ├── dashboard_story.md
│   ├── business_insights.md
│   └── chart_selection_justification.md
│
├── screenshots/
│   ├── full_dashboard.png
│   ├── sales_trend_view.png
│   ├── regional_performance_view.png
│   ├── category_profitability_view.png
│   └── filter_interaction_view.png
│
└── README.md
```

---

# Business Problem Summary

Retail leadership requires a centralized dashboard to monitor key business metrics and identify areas requiring strategic attention. This project addresses that need by providing an executive dashboard that enables users to:

* Monitor sales performance.
* Track profitability across categories and regions.
* Evaluate customer segment performance.
* Analyze shipping efficiency.
* Assess discount impact on profitability.
* Monitor product return patterns.
* Support executive decision-making through interactive analytics.

---

# Dataset Description

The dashboard is built using the provided retail sales dataset, which contains information on:

* Order Date
* Ship Date
* Region
* State
* City
* Customer Segment
* Category
* Sub-Category
* Product Name
* Sales
* Profit
* Discount
* Quantity
* Ship Mode
* Return Status
* Customer Rating
* Delivery Days
* Campaign Channel

The dataset includes both numerical and categorical variables suitable for business intelligence analysis.

---

# Tableau Workbook Description

The Tableau packaged workbook (`executive_dashboard.twbx`) contains:

* Sales Trend View
* Regional Performance View
* Category Profitability View
* Customer Segment View
* Shipping Performance View
* Discount vs Profit Analysis
* Return Analysis View
* KPI Cards
* Interactive Dashboard

The workbook enables users to explore business performance through filters and dashboard actions.

---

# Calculated Fields Created

The following calculated fields were created in Tableau:

### Profit Margin

```text
Profit / Sales
```

Measures the percentage of profit generated from total sales.

---

### Cost

```text
Sales - Profit
```

Calculates the estimated product cost.

---

### Average Order Value

```text
SUM(Sales) / COUNTD(Order ID)
```

Measures the average revenue generated per order.

---

### Return Rate

```text
Returned Orders / Total Orders
```

Measures the percentage of returned orders.

---

### Shipping Delay Bucket

Delivery Days are categorized into:

* Same Day
* 1–2 Days
* 3–5 Days
* More than 5 Days

This field supports shipping performance analysis.

---

# Dashboard Components

The executive dashboard contains:

* Sales Trend Line Chart
* Regional Sales & Profit Bar Chart
* Category Profitability Chart
* Customer Segment Comparison
* Shipping Performance Analysis
* Discount vs Profit Scatter Plot
* Return Analysis Chart
* KPI Cards

  * Total Sales
  * Total Profit
  * Profit Margin
* Interactive Filters
* Dashboard Actions

---

# Filters and Dashboard Interactions

The dashboard includes interactive filters for:

* Region
* Category
* Customer Segment
* Date
* Ship Mode

Dashboard actions allow users to click on one visualization and automatically filter the remaining charts, improving data exploration and business analysis.

---

# Key Business Insights

Major findings from the dashboard include:

* Sales show an overall upward trend over time.
* Business performance varies significantly across regions.
* Some product categories generate high revenue but relatively low profit.
* Customer segments contribute differently to overall profitability.
* High discounts reduce profit margins.
* Shipping delays negatively affect operational performance.
* Certain products and regions experience higher return rates.
* Interactive filtering enables detailed exploration of business performance.

Detailed insights are provided in **outputs/business_insights.md**.

---

# Dashboard Story Summary

The dashboard tells a complete business story by connecting sales performance, profitability, customer behavior, shipping efficiency, and return analysis into a unified executive reporting solution.

Rather than presenting isolated charts, the dashboard highlights relationships between business metrics and supports evidence-based decision-making.

A detailed leadership narrative is available in **outputs/dashboard_story.md**.

---

# Assumptions

* Sales and Profit values are correctly recorded.
* Delivery Days accurately represent shipping duration.
* Return records correctly identify returned orders.
* Customer ratings reflect actual customer feedback.
* The dataset is complete and suitable for business analysis.

---

# Limitations

* The dashboard analyzes historical data only.
* External economic factors are not included.
* Customer satisfaction is inferred from available operational metrics.
* Results depend on the completeness and quality of the dataset.
* Future performance may differ from historical trends.

---

# Screenshots Included

The repository contains the following screenshots:

* `full_dashboard.png`
* `sales_trend_view.png`
* `regional_performance_view.png`
* `category_profitability_view.png`
* `filter_interaction_view.png`

These screenshots demonstrate the completed dashboard, supporting visualizations, and interactive filtering capabilities.

---

# Conclusion

The Tableau Executive Dashboard provides leadership with an integrated view of retail business performance by combining sales, profitability, customer behavior, shipping efficiency, discount analysis, and return patterns into a single interactive reporting solution.

The dashboard supports strategic planning, operational monitoring, and evidence-based decision-making through well-designed visualizations, KPI tracking, interactive filters, and actionable business insights.
