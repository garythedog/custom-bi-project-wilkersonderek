# custom-bi-project-wilkersonderek
Custom BI Project – Retail Product Attribute Analysis (CSIS 44632)

📘 Custom BI Project – Retail Product Attribute Analysis (CSIS 44632)

Author: Derek Wilkerson
Instructor: Dr. Denise Case
Course: Business Intelligence & Analytics (NWMSU)

📊 Project Overview

This project builds a complete end-to-end Business Intelligence solution using a real-world retail product dataset. The goal was to transform raw product attributes into meaningful insights through data cleaning, modeling, and interactive visual dashboards using Power BI.

The final deliverable includes:

Cleaned and modeled dataset

DAX measures for analysis

Interactive Power BI dashboards

Executive-level insights & recommendations

🧭 Business Goal

Identify high-value product categories and understand how product attributes—such as material, placement, and category—impact revenue and sales performance.

This helps retail managers optimize:

Product assortment

In-store placement

Material sourcing

Marketing strategy

Pricing and promotions

🛠️ Tech Stack
Component	Tools
Data Cleaning	Power Query
Data Modeling	Power BI
Calculations	DAX
Visualization	Power BI Desktop
Version Control	Git + GitHub
📁 Repository Structure
custom-bi-project-wilkersonderek/
│
├── data/
│   └── raw/
│        └── Business_sales_EDA.csv
│
├── custom-bi-project-wilkersonderek.pbix   ← final dashboard
├── README.md
└── LICENSE

📐 Data Model Highlights

Single fact table with key product attributes

Cleaned data types (text, numeric, date)

Added custom calculated columns:

Revenue (price × sales volume)

Product Type (based on keywords in “terms”)

Created DAX measures:

Total Revenue

Total Sales Volume

Distinct Products

Average Price

Average Revenue per Product

High Volume Products

📊 Dashboard Pages
📌 Page 1 — Overview

High-level KPIs:

Total Revenue

Total Sales Volume

Distinct Products

Average Revenue per Product

Visuals include revenue and volume comparisons by product type.

📌 Page 2 — Product Attribute Analysis

Breakdown by:

Material

Product Type

Product Position (Aisle, End-cap, Front of Store)

Season

Section (Men/Women)

Includes interactive slicers:

season, section, material, product position, brand

Provides a heatmap-style revenue matrix and multiple bar charts.

📌 Page 3 — Insights & Recommendations

Executive summary page with:

Three insight cards

Supporting visuals

Actionable recommendations

Key Insights Identified:

Jackets drive nearly half of all total revenue.

Aisle placement produces the highest revenue lift.

Material type dramatically impacts performance.

Actionable strategies accompany each insight.

💡 Key Findings

Jackets are the highest-performing category ($487M revenue).

Aisle positioning generates the most revenue across categories.

Wool, Cotton, and Wool Blend materials outperform low-tier materials.

T-Shirts and Shoes are reliable mid-tier performers.

Promotional effects vary heavily by product type.

🚀 Recommendations

Expand jacket product offerings (colors, fits, premium materials).

Increase Aisle placement for high-performing categories.

Reduce sourcing of low-performing materials (Silk, Satin).

Use targeted promotions rather than broad discounts.

Develop predictive models using placement, material, and category.

📈 Result

This project demonstrates a complete BI workflow:

Cleaning

Modeling

Visualization

Insight generation

Data storytelling

The Power BI file in this repo contains the entire solution.