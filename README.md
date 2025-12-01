# Custom BI Project – Retail Product Attribute Analysis

**Author:** Derek Wilkerson  
**Course:** CSIS 44632 – Business Intelligence & Analytics (NWMSU)  
**Instructor:** Dr. Denise Case  

This project is a **P7 Custom BI Project** that delivers an end-to-end Business Intelligence solution using a real retail product dataset.  
It demonstrates how to clean and model data, create DAX measures, and design interactive **Power BI dashboards** that support real business decisions.

---

## 🧠 What This Project Does

- Uses a real-world style **product catalog** with attributes such as material, product type, placement, section, season, promotion, and brand.  
- Cleans and models the data into a structure that is ready for analysis in Power BI.  
- Adds **calculated columns** (e.g., `Revenue`, `Product Type`) and **DAX measures** for KPI creation.  
- Builds a multi-page **Power BI report** with:
  - Overview KPI dashboard  
  - Product attribute analysis  
  - Executive summary with insights & recommendations  
- Shows how to use **slicers, tooltips, and visuals** to support business questions about:
  - Which products drive the most revenue  
  - How placement, material, and promotions affect performance  
  - Where retailers should focus to grow sales  

---
## 💼 Tech Stack

- **Power BI Desktop** – Data model, DAX, and dashboards  
- **Power Query** – Data cleaning and transformation  
- **DAX** – Calculated columns and measures  
- **CSV / Flat File** – Source dataset  
- **Git & GitHub** – Version control and project sharing  

---

## 📁 Repository Structure

```text
custom-bi-project-wilkersonderek/
│
├─ data/
│  ├─ raw/
│  │   └─ Business_sales_EDA.csv        # Original dataset
│  └─ prepared/                         # (Optional) cleaned exports
│
├─ docs/                                # Any notes or documentation
│
├─ images/                              # README screenshots
│  ├─ page1.png                         # Page 1 – Overview dashboard
│  ├─ page2.png                         # Page 2 – Attribute analysis
│  └─ page3.png                         # Page 3 – Insights summary
│
├─ powerbi/                             # (Optional) supporting files
├─ Reports/                             # (Optional) exports
│
├─ custom-bi-project-wilkersonderek.pbix # Final Power BI report
├─ LICENSE
└─ README.md

## 🧭 How to Open & Explore the Report

### 1. Clone the Repo

From a terminal (PowerShell on Windows):

```powershell
git clone https://github.com/garythedog/custom-bi-project-wilkersonderek.git
cd custom-bi-project-wilkersonderek

## 📊 Dashboard Pages

Below are the three dashboard pages created for this project.  
Each page highlights a different aspect of product performance and business insight.

---

## 🔹 **Page 1 — Overview Dashboard**

This page provides high-level KPIs followed by quick-scan visuals that show:

- Total revenue  
- Total sales volume  
- Distinct product count  
- Average revenue per product  
- Revenue and sales volume by product type  

### 📸 Screenshot  
![Page 1 Overview](docs/images/page1.png)

---

## 🔹 **Page 2 — Product Attribute Analysis**

This page breaks down performance by key product attributes:

- **Material** (Wool, Cotton, Linen, Polyester, etc.)  
- **Product Type** (Jackets, Sweaters, T-Shirts, Shoes, Jeans)  
- **Product Position** (Aisle, End-cap, Front of Store)  
- **Section** (Men/Women)  
- **Season**  
- **Brand**  

Interactive slicers allow users to explore how placement, season, and material impact revenue.

### 📸 Screenshot  
![Page 2 Attribute Analysis](docs/images/page2.png)

---

## 🔹 **Page 3 — Insights & Recommendations**

This is the executive summary page.  
It consolidates the most important findings and gives actionable next steps:

- Best-performing materials and product types  
- Placement patterns that generate lifting revenue  
- Promotion effectiveness  
- Strategic opportunities to increase sales  

### 📸 Screenshot  
![Page 3 Insights](docs/images/page3.png)

---
## 💡 Key Insights Developed

During the analysis, several clear performance patterns emerged across product types, materials, and placement.

### ⭐ 1. Jackets dominate overall performance
- Jackets generate **the highest revenue (~$487M)** across all product types.  
- They also lead in **sales volume (~12.3M units)**, confirming broad customer demand.

### ⭐ 2. Aisle placement drives the strongest revenue lift
- Products placed in the **Aisle** consistently outperform **End-cap** and **Front of Store**.  
- This suggests customers prefer browsing through organized shelves rather than impulse displays.

### ⭐ 3. High-quality materials deliver the most revenue
- Top materials such as **Wool**, **Cotton**, and **Wool Blend** account for the highest revenue totals.  
- Lower-tier materials like **Silk** and **Satin** contribute significantly less and may warrant reduced sourcing.

### ⭐ 4. Seasonal trends impact buying behavior
- Autumn and Winter products outperform Spring and Summer.  
- This suggests stronger demand for outerwear and cold-weather apparel.

### ⭐ 5. Promotions vary in effectiveness
- Some product categories show significant uplift from promotions, while others show little change.  
- This indicates a need for **targeted**, not broad, promotional strategies.

---
## 🧭 Actionable Recommendations

Based on the insights from this project, the following data-driven recommendations are proposed for retail decision-makers:

---

### 📌 **1. Expand Jacket Offerings**
Jackets are the most profitable and highest-volume category.  
Recommended actions:

- Increase inventory depth in top-selling styles  
- Add seasonal variations (colors, fits, materials)  
- Maintain premium pricing—no broad discounts needed  

---

### 📌 **2. Prioritize Aisle Placement for High-Performing Items**
Aisle placement delivers the largest revenue impact across product types.

- Position top-performing categories (Jackets, Sweaters) on aisle fixtures  
- Use end-caps strategically for seasonal or promotional items  
- Reduce placement of low performers (Jeans) in high-visibility areas  

---

### 📌 **3. Optimize Material Mix Toward High-Performing Fabrics**
Materials significantly influence profitability.

- Increase sourcing of **Wool, Cotton, and Wool Blend**  
- Reduce low-performing materials like **Silk** and **Satin**  
- Align pricing strategy with material quality  

---

### 📌 **4. Use Targeted, Data-Driven Promotions**
Promotions should not be applied uniformly.

- Focus promotions on mid-tier products (Shoes, T-Shirts)  
- Avoid discounting high performers such as Jackets unnecessarily  
- Test seasonal promotions based on historical trends  

---

### 📌 **5. Develop Predictive Models for Inventory and Pricing**
The dataset provides a foundation for more advanced analytics.

- Use Material, Product Type, and Placement as predictive variables  
- Forecast future demand to optimize inventory levels  
- Identify potential emerging products before peak seasons  

---

## 🏁 Business Impact Summary

This project demonstrates how retailers can use BI and analytics to improve:

- Product assortment  
- Merchandising strategy  
- Material sourcing decisions  
- Promotional planning  
- Pricing intelligence  
- Store layout and product placement  

By transforming raw product data into meaningful insights, businesses gain the ability to make **faster, smarter, and more profitable decisions**.

---

## 📎 Acknowledgments

This project was completed as part of:

**CSIS 44632 – Business Intelligence & Analytics**  
**Northwest Missouri State University**  
Instructor: **Dr. Denise Case**

Special thanks for guidance, best practices, and project structure provided throughout the course.

---

## 📬 Contact

If you have questions about this project or would like to discuss BI or analytics solutions:

**Derek Wilkerson**  
**Email:** dwilkerson2012@gmail.com  
**GitHub:** https://github.com/garythedog

---

