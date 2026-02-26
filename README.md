# Myntra Product Analysis Project

> An end-to-end data analysis and business intelligence project on Myntra's e-commerce dataset — covering data cleaning, exploratory analysis in Excel, and an interactive Power BI dashboard for actionable retail insights.

---

## 📸 Dashboard Preview

<img width="1437" height="812" alt="POWERBI DASHBOARD" src="https://github.com/user-attachments/assets/9a06e8b4-b8b0-4217-ac6e-5cf791da35d6" />

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Key Insights](#-key-insights)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Data Analysis Workflow](#-data-analysis-workflow)
- [Dashboard Features](#-dashboard-features)
- [Action Plan](#-action-plan)

---

## 🎯 Project Overview

This project analyzes Myntra's fashion e-commerce data to uncover patterns in sales performance, customer behaviour, product category trends, and brand popularity. The goal was to translate raw transactional data into clear, decision-ready visuals for a business stakeholder audience.

**Business Questions Answered:**
- Which product categories and brands drive the most revenue?
- How do discounts affect purchase volume and profitability?
- What are the peak sales periods throughout the year?
- Which customer segments show the highest lifetime value?
- How does pricing strategy vary across categories?

---

## 💡 Key Insights

- **Top Brand:** `Roadster` contributes `8.95%` of total revenue
- **Top Category:** `tshirts` contributes `6.61%` of total revenue
- **Discount Sweet Spot:** Products with `50–60%` discount show the highest conversion rates
- **Brand Concentration:** Top 10 brands account for `19.30%` of total orders
- **Rating Impact:** Products rated above `4.0` sell `3.19 times` more than lower-rated alternatives

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, EDA, pivot tables, preliminary charts |
| **Power BI Desktop** | Interactive dashboard, DAX measures, data modelling |
| **Power Query** | Data transformation and shaping within Power BI |
| **DAX** | Custom KPI calculations and time intelligence |

---

## 📁 Project Structure

```
myntra-analytics-dashboard/
│
├── 📊 data/
│   ├── raw/
│   │   └── myntra_raw_data.xlsx          # Original dataset
│   └── processed/
│       └── myntra_cleaned_data.xlsx      # Cleaned & transformed data
│
├── 📈 analysis/
│   └── myntra_eda.xlsx                   # Excel EDA workbook (pivot tables, charts)
│
├── 📉 dashboard/
│   └── Myntra_PowerBI_Dashboard.pbix     # Power BI report file
│
├── 🖼️ screenshots/
│   ├── dashboard_overview.png
│   ├── category_breakdown.png
│   ├── customer_insights.png
│   └── sales_trends.png
│
├── 📄 docs/
│   └── data_dictionary.md               # Column definitions and data descriptions
│
├── README.md
```

## 🔄 Data Analysis Workflow

```
Raw Data (Excel)
      │
      ▼
Data Cleaning (Excel)
  • Remove duplicates
  • Handle nulls & outliers
  • Standardise column formats
  • Derive new columns (e.g., discount %, price bands)
      │
      ▼
Exploratory Data Analysis (Excel)
  • Pivot tables for category/brand summaries
  • Distribution analysis of ratings & prices
  • Trend analysis across time periods
      │
      ▼
Power BI Import & Modelling
  • Connect to cleaned Excel data
  • Power Query transformations
  • Build data model & relationships
  • Write DAX measures (KPIs, time intelligence)
      │
      ▼
Dashboard Design & Visualisation
  • Overview KPI cards
  • Category & brand breakdowns
  • Time-series trend charts
  • Customer behaviour visuals
  • Slicers & cross-filtering
```

---

## 📊 Dashboard Features

**Page 1 — Executive Overview**
- Total Revenue, Orders, Avg. Order Value, Avg. Discount % (KPI cards)
- Revenue trend over time (line chart)
- Top 5 categories by revenue (bar chart)

**Page 2 — Product & Category Analysis**
- Revenue and order volume by category (treemap / stacked bar)
- Brand performance leaderboard
- Price range distribution (histogram)
- Discount vs. rating scatter plot

**Page 3 — Customer Insights**
- Order volume segmented by customer rating
- Repeat vs. one-time purchase patterns
- High-value product clusters

**Page 4 — Sales Trends**
- Month-on-month and year-on-year comparisons
- Seasonal patterns
- Category-level trend lines

**Interactive Features**
- Cross-page slicers (Category, Brand, Date Range, Rating)
- Drill-through from summary to product-level detail
- Tooltips with contextual metrics on hover

---

## 🗺️ Action Plan

This section documents the project roadmap for transparency and reproducibility.

### ✅ Phase 1 — Data Collection & Understanding
- [x] Sourced Myntra e-commerce dataset
- [x] Reviewed schema: products, pricing, discounts, ratings, categories, brands
- [x] Defined key business questions

### ✅ Phase 2 — Data Cleaning (Excel)
- [x] Removed duplicate product entries
- [x] Handled missing values in ratings and pricing columns
- [x] Standardised category and brand name formats
- [x] Created derived columns: `Discount %`, `Revenue`, `Product Category`
- [x] Exported cleaned dataset for Power BI import

### ✅ Phase 3 — Exploratory Data Analysis (Excel)
- [x] Pivot table: Revenue by Category
- [x] Pivot table: Top Brands by Order Volume
- [x] Distribution charts: Price & Discount ranges
- [x] Correlation check: Discount % vs. Customer Rating

### ✅ Phase 4 — Power BI Dashboard Development
- [x] Connected Power BI to cleaned Excel data
- [x] Transformed and shaped data in Power Query
- [x] Built DAX measures for KPIs
- [x] Designed multi-page interactive report
- [x] Added slicers, drill-through, and tooltips

### 🔲 Phase 5 — Portfolio Publishing (In Progress)
- [x] Structured GitHub repository
- [ ] Add screenshots to `screenshots/` folder
- [ ] Complete data dictionary (`docs/data_dictionary.md`)
- [ ] Publish to GitHub
- [ ] Add repository link to LinkedIn / portfolio

### 🔮 Future Enhancements
- [ ] Incorporate Python (Pandas/Seaborn) for deeper statistical analysis
- [ ] Build a predictive model for sales forecasting
- [ ] Publish report to Power BI Service for live web sharing
- [ ] Add RFM (Recency, Frequency, Monetary) customer segmentation

---

## 📄 Data Dictionary

See [`docs/data_dictionary.md`](./docs/data_dictionary.md) for full column definitions.

| Column | Description |
|---|---|
| `product_id` | Unique identifier for each product |
| `product_name` | Name of the product |
| `product_category` | Product category (e.g., tshirts, tops, heels, trousers,etc.) |
| `brand_name` | Name of the Brand |
| `marked_price` | Listed price before discount (₹) |
| `discounted_price` | Final selling price after discount (₹) |
| `discount_percentage` | Discount percentage applied |
| `revenue` | Total revenue generated from all units of product (₹) |
| `rating` | Average customer rating (1–5 scale) |
| `rating_count` | Number of customer ratings |

---

## 🤝 Connect

**[Amrit Kaur Saini]** —  Data Analyst

[![LinkedIn](https://www.linkedin.com/in/amrit-kaur-saini-259783294?)

[![GitHub](https://github.com/AmritKSaini)

---

*⭐ If you found this project useful or insightful, consider starring the repository!*
