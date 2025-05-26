# 📊 Excel Dashboard: Sales Analysis for Adventure Works

**🏢 Organization:** AI Variant  
**🧠 Role:** Business Analyst Intern  
**📁 Tools Used:** Excel (Pivot Tables, Charts, Slicers, Conditional Formatting, Formulas)

---

## 🔍 Project Objective

To analyze Adventure Works' global sales performance across various regions, products, and customer segments. The goal was to identify sales trends, high-performing categories, and potential business opportunities using an interactive Excel dashboard.

---

## 📈 Data Sources

- **Fact Table:** Internal sales records (sales date, revenue, quantity)
- **Dimension Tables:** Customers, Products, Sales Territory, Date, Product Category

---

## ⚙️ Techniques and Formulas Used

| Feature                 | Description                                           | Example                                                            |
|------------------------|-------------------------------------------------------|--------------------------------------------------------------------|
| **Pivot Tables**       | Summarized revenue, quantity, and profit              | Monthly sales by region                                            |
| **VLOOKUP / XLOOKUP**  | Mapped product/customer IDs to names                  | `=XLOOKUP(A2,DimProduct[ProductID],DimProduct[ProductName])`       |
| **IF Statements**      | Categorized performance levels                        | `=IF(Sales>10000,"High","Low")`                                    |
| **Slicers**            | Filtered dashboard views dynamically                  | Region and Year slicers                                            |
| **Conditional Formatting** | Highlighted top/bottom performers                | Red fill for low-profit items                                      |
| **Named Ranges**       | Clean data referencing                                | `=SUM(Sales_US)`                                                   |
| **Data Validation**    | Dropdown menus for filters                            | Product category filter                                            |

---

## 📊 Dashboard Features

- **KPIs Tracked:**
  - Total Revenue
  - Total Profit
  - Units Sold
  - Average Sales per Customer

- **Visualizations:**
  - 📊 Column Chart – Sales by Region  
  - 📈 Line Chart – Monthly Sales Trend  
  - 🥧 Pie Chart – Sales by Product Category  
  - 📋 Bar Chart – Top 5 Customers by Revenue

- **Interactive Elements:**
  - Year and Region slicers  
  - Hover tooltips for detailed values

---

## 💡 Key Insights

- 📈 **Western Europe** and **North America** had the highest revenue.
- 🏆 **Bikes** were the most profitable product category.
- 🕒 Sales peaked in **Q4**, suggesting strong seasonal demand.
- ⚠️ **Accessories** underperformed across most regions.
- 🌍 Growth potential observed in **Australia** and **Central America**.

---

## ✅ Business Impact

- Delivered actionable recommendations for regional marketing and inventory planning.
- Enhanced decision-making with visual, real-time analytics.
- Streamlined reporting using an easy-to-navigate dashboard.

---

## 📎 Preview

> 📷 Sales Analysis
![Image](https://github.com/user-attachments/assets/81de3cbc-98ed-4ebd-b93e-912e63a0e3a6)

> 📷 Customer Analysis
![Image](https://github.com/user-attachments/assets/42e5afdd-2bf9-427f-885f-bec675fda3e5)

> 📷 Region Analysis
![Image](https://github.com/user-attachments/assets/e7677041-af49-4e95-8036-2921fd1999ec)

> 📁 [Download the Excel Dashboard](https://docs.google.com/spreadsheets/d/1V_ZrkUMwfqu5Cns6FVsPmeg1MzM6D6Ze/edit?usp=drive_link&ouid=103514787384736655190&rtpof=true&sd=true)

---

## 🚀 Skills Demonstrated

`Excel Analytics` `Dashboard Design` `Pivot Tables` `Data Cleaning` `KPI Reporting` `Data Storytelling`
