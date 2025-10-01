# 🚴 Power BI Capstone Project – Dataline Bike Company

## 🔹 Project Overview
This project analyzes **Dataline Bike Company’s global sales (2017–2020)**.  
The goal was to replace manual Excel/PDF reports with an **interactive Power BI dashboard** designed for two audiences:
- **CEO & Managers** – high-level KPIs and profitability insights
- **Marketing & Product Teams** – customer analysis, product performance, detailed drill-throughs

---

## 🔹 Data Sources
- 4 CSV files: Sales Orders (2017–2020)  
- 1 Excel file: Customer, Product, and other dimension tables  

---

## 🔹 Data Preparation & Modeling
- Cleaned raw sales data (fixed missing values, removed duplicates, standardized dates).  
- Built a **star schema** with Fact (Sales) and Dimensions (Customer, Product, Calendar).  
- Created calculated columns and DAX measures:  
  - `Revenue = Order Quantity × Unit Price`  
  - `Profit = Order Quantity × (Unit Price – Standard Cost)`  
  - `YTD Revenue`, `Profit Margin %`, `Profit Difference`  

---

## 🔹 Dashboard Pages
### 🏢 CEO Overview
- KPIs: **$110M Revenue, $13.08M Profit, 11.9% Profit Margin**  
- Profit by Category & Country  
- Revenue trend over years (2017–2020)  
- Tooltip: Profit development on country hover  

### 📦 Marketing & Products
- YTD Revenue & Profit difference vs previous year  
- Drillthrough to detailed order-level data (date, product, country, revenue, profit, quantity)  
- Most Ordered Product: **AWC Logo Cap (8,311 units)**  

### 👥 Customer Analysis
- **Top 10 Customers by Revenue** (Jordan Turner leading at $15,999)  
- Average Profit per Customer over time  
- Total Customers: **18,484**
-   Average profit: **$653.6**

### 📂 Category Performance
- Revenue & Profit by Category (Bikes, Components, Accessories, Clothing)  
- Profit Margin trends over time  
- Drilldown by Region, State, City, Postal Code  

---

## 🔹 Key Insights
- **Bikes** drive most revenue but lower margins (11.6%).  
- **Accessories** have the highest profit margin (50.1%).  
- Customer revenue is concentrated among top buyers.  
- Revenue grew steadily until 2019, then dipped in 2020.  

---

## 🔹 Tools Used
- Power BI Desktop  
- Power Query (ETL)  
- DAX (measures & calculations)  
- Excel (data source)  

---

## 🔹 How to Use
1. Download the `.pbix` file from this repo.  
2. Open in **Power BI Desktop**.  
3. Explore dashboards with slicers, drilldowns, and tooltips.  

---

## 🔹 Screenshots
<img width="590" height="334" alt="Screenshot 2" src="https://github.com/user-attachments/assets/2f46e0fd-9fe0-4d13-a0ef-4a92f522e53d" />
<img width="599" height="338" alt="Screenshot 3" src="https://github.com/user-attachments/assets/9429e810-eac1-446b-8ea3-0bd2a727f697" />
<img width="602" height="333" alt="Screenshot 4" src="https://github.com/user-attachments/assets/81de3afd-284b-467d-91c4-907b435e9be7" />

---

## 🔹 Author
👤 Rohini R
