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

```text
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


---

### Segment 2 (next ~50 lines)

```markdown
---

## 📊 Dashboard Pages

Below are the three dashboard pages created for this project.

---

## 🔹 **Page 1 — Overview Dashboard**

This page provides high-level KPIs and quick-scan visuals:

- Total revenue  
- Total sales volume  
- Distinct product count  
- Average revenue per product  
- Revenue & sales volume by product type  

### 📸 Screenshot  
![Page 1 Overview](images/page1.png)

---

## 🔹 **Page 2 — Product Attribute Analysis**

This page breaks down performance by:

- **Material** (Cotton, Wool, Linen, etc.)  
- **Product Type** (Jackets, Shoes, T-Shirts…)  
- **Product Position** (Aisle, End-cap, Front of Store)  
- **Section** (Men/Women)  
- **Season**  
- **Brand**  

Interactive slicers allow you to explore how these attributes impact revenue and sales.

### 📸 Screenshot  
![Page 2 Attribute Analysis](images/page2.png)

---

## 🔹 **Page 3 — Insights & Recommendations**

This executive summary page consolidates key findings:

- Best-performing product types  
- Placement strategies that lift revenue  
- Material performance trends  
- Promotion effectiveness  
- Strategic opportunities to increase sales  

### 📸 Screenshot  
![Page 3 Insights](images/page3.png)

---

## 💡 Key Insights Developed

### ⭐ 1. Jackets dominate performance  
- Highest revenue (around **$487M**)  
- Highest sales volume (around **12.3M units**)  

### ⭐ 2. Aisle placement delivers the biggest lift  
- Outperforms End-cap and Front-of-Store placement  
- Customers prefer browsing organized shelves over impulse-only displays  

### ⭐ 3. Material strongly influences revenue  
- **Wool**, **Cotton**, and **Wool Blend** lead in revenue  
- **Silk** and **Satin** underperform and may warrant reduced sourcing  

### ⭐ 4. Seasonal patterns drive behavior  
- **Autumn** and **Winter** outperform Spring/Summer  
- Stronger demand for outerwear and cold-weather items  

### ⭐ 5. Promotions work selectively  
- Some categories show strong uplift from promotions  
- Others show minimal change → avoid blanket discounting  

---

## 🧭 Actionable Recommendations

### 📌 1. Expand Jacket Offerings
- Increase inventory depth for top-selling jacket styles  
- Add seasonal variations (colors, fits, materials)  
- Maintain premium pricing rather than frequent discounting  

---

### 📌 2. Prioritize Aisle Placement
- Place high-performing categories (Jackets, Sweaters) in aisle fixtures  
- Use End-caps for seasonal or promotional campaigns  
- Limit prime placement for low-performing categories  

---

### 📌 3. Optimize Material Mix
- Focus sourcing on **Wool, Cotton, and Wool Blend**  
- Reduce reliance on lower-performing materials like Silk and Satin  
- Align pricing strategy with perceived material quality  

---

### 📌 4. Use Targeted, Data-Driven Promotions
- Focus promotions on mid-tier categories (e.g., Shoes, T-Shirts)  
- Avoid discounting top performers unnecessarily  
- Test seasonal promotions based on historical performance  

---

### 📌 5. Develop Predictive Models
- Use product attributes (material, type, placement, season) to forecast demand  
- Improve inventory planning and reduce stockouts/overstock  
- Detect early trends in emerging products or categories  

---

## 🏁 Business Impact Summary

This project shows how retailers can use BI and analytics to improve:

- Product assortment and merchandising strategy  
- Store layout and product placement  
- Promotional planning and discount strategy  
- Material sourcing and pricing intelligence  

By transforming raw product data into meaningful insights, retailers can make **better, faster, and more profitable decisions**.

---

## 📎 Acknowledgments

This project was completed as part of:

**CSIS 44632 – Business Intelligence & Analytics**  
**Northwest Missouri State University**  
Instructor: **Dr. Denise Case**

---

## 📬 Contact

**Derek Wilkerson**  
📧 Email: *dwilkerson2012@gmail.com*  
🔗 GitHub: https://github.com/garythedog
