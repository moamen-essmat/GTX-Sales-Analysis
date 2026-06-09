
# GTX Sales Analytics Dashboard 📊

An advanced, interactive Power BI dashboard designed to analyze and track sales performance for **GTX**. This project transforms raw corporate sales pipeline data into actionable business insights, focusing on key performance indicators (KPIs), regional distribution, product profitability, and sales team effectiveness.

🔗 **[Live Interactive Report Link]** *(Optional: Add your Power BI Service Publish to Web link here if available)*

---

## 🚀 Business Value & Key Insights
* **Revenue Overview:** Achieved total sales of **$20.94M** across **9K total orders**.
* **Top Performance Drivers:** Identified `GTX 500` as the highest driver for sales growth, with an average increase of **$24.50K** per deal.
* **Geographical Dominance:** The **West Region** leads company sales with **$7.51M**, followed closely by the East ($6.62M) and Central ($6.06M) offices.
* **Top Sales Talents:** Sales agent `Versie Hillebrand` emerged as the top performer, individually driving **$1.53M** in revenue.

---

## 🛠️ Tech Stack & Features Used
* **Power BI Desktop:** Dashboard design and interactive reporting.
* **Power Query:** Data cleaning, profiling, data type formatting, and merging text/date fields.
* **DAX (Data Analysis Expressions):** Created custom measures for `#of Orders`, `Total Sales`, and dynamic time-intelligence fields.
* **AI Visuals Implemented:** * *Key Influencers:* Interrogating data to find what drives product sales increases.
  * *Decomposition Tree:* Drilled down from Total Sales to find hidden performance patterns by region, office, account, and agent.

---

## 📸 Dashboard Preview

### 1. Main Executive Dashboard
*Provides a high-level overview of monthly sales trends, waterfall product analysis, top managers, and top-performing sales agents.*
![Main Dashboard](images/dashboard_main.png)

### 2. Geographical Sales Map
*An interactive map visual tracking global revenue distribution across office locations (with heavy concentration in the United States).*
![Sales Map](images/map_view.png)

### 3. Sales Decomposition Tree (Root Cause Analysis)
*An AI-powered drill-down path from Total Sales ($20.94M) breakdown across regions, accounts, and individual products.*
![Decomposition Tree](images/decomposition_tree.png)

### 4. Key Influencers (AI Insights)
*Automated machine learning insight showing that when a product is `GTK 500`, the average sales increase dramatically by $24.50K.*
![Key Influencers](images/key_influencers.png)

---

## 🗃️ Data Model & Schema
The project utilizes a relational schema structured across 4 main business dimensions:
1. **Accounts:** Account names, sectors, and office locations.
2. **Products:** Product names, series, and pricing.
3. **Sales Pipeline:** Core transactional table holding order dates, price, and order IDs.
4. **Sales Teams:** Sales agents, managers, and regional offices.

![Data Schema](images/data_model.png)

---

## ⚙️ How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have **Power BI Desktop** installed.
3. Open the `GTX_Sales_Dashboard.pbix` file.
4. If you wish to look at the raw data structure, explore the tables inside the `Data` pane.

---
💡 *Developed as part of my Data Analytics portfolio. Connect with me on [LinkedIn](https://linkedin.com/in/moamenessmat).*
