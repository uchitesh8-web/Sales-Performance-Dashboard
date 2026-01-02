# Sales Performance Analysis Dashboard

## 📌 Project Overview

This project analyzes historical sales data to evaluate **business performance, revenue trends, customer contribution, and product-level profitability**.
The project uses **Python for data preprocessing** to create a clean and reliable dataset, followed by **Power BI** to design an interactive dashboard for executive-level decision-making.

The goal is to convert raw transactional data into a **single source of truth** and provide actionable insights for sales and management teams.

---

## 🎯 Business Objectives

* Measure overall sales performance and revenue trends
* Identify top-performing product categories and customers
* Analyze discount patterns and pricing effectiveness
* Track sales growth and seasonality over time
* Enable quick, interactive decision-making through dashboards

---

## 📂 Dataset Overview

* **Dataset Name:** DQLab Store Sales Performance
* **Time Period:** 4 years (2009–2012)
* **Total Revenue:** ₹18 Billion
* **Total Orders:** 5,424
* **Total Quantity Sold:** 138,227 units
* **Product Categories:** Technology, Furniture, Office Supplies 

Each row in the dataset represents an individual customer order.

---

## 🛠 Tools & Technologies Used

* **Python (Pandas, NumPy)** – Data preprocessing & feature engineering
* **Power BI** – Interactive dashboard creation and analysis

---

## 🧹 Data Preprocessing (Python)

Python was used to clean and structure the raw sales data before visualization:

### Key Steps Performed:

* Loaded pipe-separated raw data and skipped non-data header rows
* Manually defined column headers to ensure correct business mapping
* Selected only valid business columns from the raw file
* Removed extra spaces from text fields to avoid category mismatches
* Converted order dates into proper datetime format
* Converted sales, discount, and quantity fields into numeric format
* Created a **Net Sales** metric:

  ```
  Net Sales = Sales − Discount Value
  ```
* Removed blank and invalid order records
* Exported the cleaned dataset for Power BI analysis 

This process ensured accurate reporting and eliminated noise from the raw data.

---

## 📊 Key Performance Indicators (KPIs)

* **Total Net Revenue:** ₹18 Billion
* **Total Quantity Sold:** 138K
* **Total Orders:** 5,424

These KPIs are placed in the dashboard’s **high-value zone** to give decision-makers instant visibility into business performance .

---

## 🔍 Key Analysis & Insights

### 📈 Revenue Trend Analysis

* Visualized net revenue trends over 4 years (2009–2012)
* Identified revenue peaks and dips across months and years
* March consistently shows strong sales performance
* Mid-year dips indicate opportunities for promotional campaigns 

---

### 🧩 Category Market Share

* Technology is the **largest revenue contributor**
* Furniture and Office Supplies contribute smaller shares
* Treemap visualization highlights category dominance clearly 

---

### 💸 Discount Analysis

* Analyzed **average discount** by product sub-category
* Copiers & Fax products have the highest average discount (~5.7%)
* Highlights potential profit leakage and pricing optimization opportunities 

---

### ⭐ Top 10 Customers

* Identified top revenue-generating customers using Top-N filtering
* Revenue is driven by a small group of high-value customers
* Enables account management and targeted retention strategies 

---

## 🎛 Interactive Dashboard Features

The Power BI dashboard includes slicers for:

* Year
* Product Category
* Order Status (Finished, Cancelled, Returned)

All visuals update dynamically, allowing users to:

* Filter performance by specific years
* Analyze only completed orders
* Drill down into product and category performance 

---

## 📈 Business Recommendations

* Ensure higher inventory and staffing during **March sales peaks**
* Launch mid-year promotional campaigns to address revenue dips
* Reevaluate discount strategy for highly discounted sub-categories
* Focus relationship management on top revenue-generating customers
* Prioritize Technology category as the main growth engine 

---

## ✅ Conclusion

This project demonstrates how **Python-based data preprocessing** combined with **Power BI dashboards** can deliver accurate, interactive, and business-focused sales insights.
The dashboard enables management to move from static reporting to **fast, data-driven decision-making**.

---

## 📚 Learning Outcomes

* Real-world data cleaning using Python
* Business logic implementation (Net Sales calculation)
* KPI-driven dashboard design
* Sales trend, category, and customer analysis

