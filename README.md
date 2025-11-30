# custom-bi-project-wilkersonderek
Custom BI Project – Retail Product Attribute Analysis (CSIS 44632)

# Custom BI Project – Retail Product Attribute Analysis  
**Author:** Derek Wilkerson  
**Course:** CSIS 44632 – Business Intelligence & Analytics (NWMSU)  
**Instructor:** Dr. Denise Case  

This project is a **P7 Custom BI Project** that delivers an end-to-end Business Intelligence solution using a real retail product dataset.  
It demonstrates how to clean and model data, create DAX measures, and design interactive **Power BI dashboards** that support real business decisions.

---

## 💡 What This Project Does

- Uses a real-world style **product catalog** with attributes such as material, product type, placement, section, season, promotion, and brand.  
- Cleans and models the data into a structure that is ready for analysis in Power BI.  
- Adds **calculated columns** (e.g., `Revenue`, `Product Type`) and **DAX measures** for KPIs.  
- Builds a multi-page **Power BI report** with:
  - Overview KPI dashboard  
  - Product attribute analysis  
  - Executive summary with insights & recommendations  
- Shows how to use **slicers, tooltips, and visuals** to support business questions about:
  - Which products drive the most revenue  
  - How placement, material, and promotions affect performance  
  - Where retailers should focus to grow sales

---

## 🧰 Tech Stack

- **Power BI Desktop** – Data model, DAX, and dashboards  
- **Power Query** – Data cleaning and transformation  
- **DAX** – Calculated columns and measures  
- **CSV / Flat File** – Source dataset  
- **Git & GitHub** – Version control and project sharing  

---

## 🗂️ Repository Structure

```text
custom-bi-project-wilkersonderek/
│
├─ data/
│   ├─ raw/
│   │   └─ Business_sales_EDA.csv        # Original dataset
│   └─ prepared/                         # (Optional) cleaned exports
│
├─ docs/                                 # Any notes or documentation
├─ images/                               # README screenshots
│   ├─ page1.png                         # Page 1 – Overview dashboard
│   ├─ page2.png                         # Page 2 – Attribute analysis
│   └─ page3.png                         # Page 3 – Insights summary
│
├─ powerbi/                              # (Optional) supporting files
├─ Reports/                              # (Optional) exports
│
├─ custom-bi-project-wilkersonderek.pbix # Final Power BI report
├─ LICENSE
└─ README.md
