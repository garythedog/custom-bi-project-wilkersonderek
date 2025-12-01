Custom BI Project – Retail Product Attribute Analysis

Author: Derek Wilkerson
Course: CSIS 44632 – Business Intelligence & Analytics (NWMSU)
Instructor: Dr. Denise Case

This project is a P7 Custom BI Project that delivers an end-to-end Business Intelligence solution using a retail product dataset.
It demonstrates how to clean and model data, create DAX measures, and design interactive Power BI dashboards to support real business decisions.

🧠 What This Project Does

Uses a real-world style product catalog with attributes such as material, product type, placement, section, season, promotion, and brand.

Cleans and models the data into an analysis-ready structure using Power Query.

Adds calculated columns (e.g., Revenue) and DAX measures for KPIs and comparisons.

Builds a multi-page Power BI report including:

Executive KPI overview

Product attribute performance analysis

Insights & recommendations summary

Uses slicers, tooltips, and visuals to answer key retail strategy questions:

Which products drive revenue?

How do placement, material, and promotions impact sales?

Where should retailers focus to grow revenue?

💼 Tech Stack

Power BI Desktop – Data model, DAX, dashboards

Power Query – Data cleaning and transformation

DAX (Data Analysis Expressions) – Measures, KPIs, and analytics

CSV / Flat File – Source raw dataset

Git & GitHub – Version control and project sharing

📁 Repository Structure
custom-bi-project-wilkersonderek/
│
├─ data/
│  ├─ raw/
│  │   └─ Business_sales_EDA.csv        # Original dataset
│  └─ prepared/                         # (Optional) cleaned exports
│
├─ docs/                                # Documentation & notes
│
├─ images/                              # Screenshots for README
│  ├─ page1.png
│  ├─ page2.png
│  └─ page3.png
│
├─ powerbi/                             # (Optional) PBIX resources
├─ reports/                             # (Optional) exported reports
│
├─ custom-bi-project-wilkersonderek.pbix # Final Power BI report
├─ LICENSE
└─ README.md

🧭 How to Open & Explore the Report
1. Clone the repo
git clone https://github.com/garythedog/custom-bi-project-wilkersonderek.git
cd custom-bi-project-wilkersonderek

2. Open the Power BI file

Open:

custom-bi-project-wilkersonderek.pbix


in Power BI Desktop.

📊 Dashboard Pages

Below are the three dashboard pages created for this project, each highlighting key performance areas.

🔹 Page 1 — Overview Dashboard

This page provides high-level KPIs and quick-scan visuals:

Total revenue

Total sales volume

Distinct product count

Average revenue per product

Revenue & sales volume by product type

📸 Screenshot

🔹 Page 2 — Product Attribute Analysis

Breaks down performance by:

Material (Cotton, Wool, Linen, etc.)

Product Type (Jackets, Shoes, T-Shirts…)

Product Position (Aisle, End-cap, Front of Store)

Section (Men/Women)

Season

Brand

Includes interactive slicers for drilling into patterns.

📸 Screenshot

🔹 Page 3 — Insights & Recommendations

This executive summary page consolidates insights including:

Best-performing product types

Placement strategies that lift revenue

Material performance

Promotion effectiveness

Opportunities for growth

📸 Screenshot

💡 Key Insights Developed
⭐ 1. Jackets dominate performance

Highest revenue (~$487M)

Highest sales volume (~12.3M units)

⭐ 2. Aisle placement delivers the biggest lift

Outperforms End-cap and Front-of-Store placement

Customers prefer organized shelf browsing

⭐ 3. Material strongly influences revenue

Wool, Cotton, and Wool Blend lead revenue

Silk and Satin underperform

⭐ 4. Seasonal patterns drive buying behavior

Autumn and Winter outperform Spring/Summer

Demand aligns with outerwear and cold-weather apparel

⭐ 5. Promotions work selectively

Some categories benefit greatly

Others show little uplift → avoid blanket discounts

🧭 Actionable Recommendations
📌 1. Expand Jacket Offerings

Increase inventory depth

Add seasonal variations

Maintain premium pricing

📌 2. Prioritize Aisle Placement

Place high performers (Jackets, Sweaters) in aisle fixtures

Use End-cap for seasonal/promotional items

Reduce prime placement for weak categories

📌 3. Optimize Material Mix

Focus on Wool, Cotton, Wool Blend

Reduce low performers like Silk

Align pricing to material quality

📌 4. Use Targeted Promotions

Promote mid-tier categories (Shoes, T-Shirts)

Avoid discounting strong sellers

Test seasonal promotions

📌 5. Develop Predictive Models

Use material, type, and placement to forecast demand

Improve inventory planning

Detect early trends

🏁 Business Impact Summary

This project demonstrates how retailers can use BI to improve:

Merchandising strategy

Product assortment

Promotional planning

Material sourcing

Store layout optimization

Pricing intelligence

Data-driven insights allow retailers to make better, faster, more profitable decisions.

📎 Acknowledgments

Completed for:

CSIS 44632 – Business Intelligence & Analytics
Northwest Missouri State University
Instructor: Dr. Denise Case

📬 Contact

Derek Wilkerson
📧 Email: dwilkerson2012@gmail.com

🔗 GitHub: https://github.com/garythedog
