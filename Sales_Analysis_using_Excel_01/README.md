# 🌸 Ferns N Petals Sales Analysis – Excel Dashboard

## 📊 Project Overview
This project is an end-to-end **Sales Analysis Dashboard** built using **Microsoft Excel**.  
It analyzes the sales performance of **Ferns N Petals (FNP)** to uncover insights on revenue, product trends, customer spending, and order delivery timelines.  
The dashboard provides an interactive and visual summary of business performance across various parameters like **occasions, categories, products, and cities**.

---

## 🎯 Objective
To analyze and visualize the overall sales performance of FNP by:
- Tracking total orders, revenue, and customer spending.
- Identifying top-performing products, cities, and categories.
- Measuring order-to-delivery time.
- Highlighting seasonal sales trends and customer purchase patterns.

---

## 🧠 Key Insights
- **Anniversary** and **Raksha Bandhan** generated the highest revenues.  
- **Soft Toys**, **Sweets**, and **Colors** were the most profitable product categories.  
- **Dhanbad**, **Kavali**, and **Imphal** recorded the highest number of orders.  
- Sales peaked during **February** and **September**, reflecting festive demand.  
- The **average delivery time** was **5.53 days**, and **average customer spend** was **₹3,520.98**.

---

## ⚙️ Project Workflow
### **1. Data Extraction (ETL)**
- Imported datasets using Excel’s **Power Query** from multiple CSV files.
- Automated data updates by importing data from a folder.

### **2. Data Cleaning & Transformation**
- Checked for **duplicates**, **null values**, and corrected **data types**.  
- Extracted new columns:
  - Month, Year, Hour, Day Name
  - Order–Delivery difference (in days)
  - Merged `Products` and `Orders` to calculate **Revenue = Price × Quantity**
- Removed unnecessary columns like *Address*, *Description*, *Email*, etc.

### **3. Data Modeling (Power Pivot)**
- Built relationships between:
  - `Customers[Customer_ID] → Orders[Customer_ID]`
  - `Products[Product_ID] → Orders[Product_ID]`
- Added **calculated columns** and **DAX measures** for KPIs and date formatting.

### **4. Data Analysis (Pivot Tables)**
- Analyzed:
  - Total Revenue  
  - Average Delivery Time  
  - Top Products by Revenue  
  - Monthly Sales Trends  
  - City-wise Orders  
  - Revenue by Occasion and Category  
  - Correlation between Quantity and Delivery Time

### **5. Dashboard Creation**
- Designed an interactive dashboard with:
  - **KPIs:** Total Orders, Total Revenue, Avg. Delivery Time, Avg. Spend  
  - **Charts:**  
    - Revenue by Occasion  
    - Revenue by Category  
    - Top 10 Cities by Orders  
    - Top 5 Products by Revenue  
    - Monthly and Hourly Revenue Trends  
  - **Slicers:** Occasion  
  - **Timelines:** Order Date, Delivery Date  
- Applied color themes, branding logo, and clear labels for readability.

---

## 💻 Tools & Technologies
- **Microsoft Excel**
  - Power Query Editor
  - Power Pivot
  - Pivot Tables & Charts
  - DAX Calculations
  - Slicers and Timeline Filters
- **Functions Used:** `SUMIFS`, `AVERAGEIFS`, `COUNTIFS`, `FORMAT`, `CORREL`

---

## 📈 Key Metrics
| Metric | Value |
|--------|--------|
| Total Orders | 1,000 |
| Total Revenue | ₹35,20,984 |
| Avg. Delivery Time | 5.53 days |
| Avg. Customer Spend | ₹3,520.98 |

---

## 🧩 Dataset Information
**Datasets Used:**
1. `customers.csv` – Customer details  
2. `orders.csv` – Order details  
3. `products.csv` – Product details  

Dataset Source: [GitHub – FNP Excel Project](https://github.com/Ayushi0214/FNP---Excel-Project/blob/main/Ferns%20and%20Petals%20Sales%20Analysis.pdf)

---

## 🗂️ Folder Structure
```
📁 Ferns-N-Petals-Sales-Analysis
│
├── 📄 README.md
├── 📄 Ferns_and_Petals_Sales_Analysis_Dashboard.xlsx
├── 📄 Ferns_and_Petals_Sales_Analysis.pdf
│
├── 📁 Data
│ ├── customers.csv
│ ├── orders.csv
│ └── products.csv
│
└── 📁 Images
└── Dashboard_Screenshot.png
```

---

## 🚀 Results
The final dashboard provides business intelligence through interactive visuals, helping stakeholders:
- Identify sales opportunities during festive seasons.
- Improve logistics and delivery performance.
- Focus on top-selling products and profitable categories.

---

## 🧩 Project Reference
Tutorial: [Excel Full Project for Data Analysis with AI (WsCube Tech - English)](https://www.youtube.com/watch?v=Wom-eVrE4RY)

---

## 👩‍💻 Author
**Mounika Seelam**  
*Data Analytics Enthusiast | Python | Excel | Power BI | Tableau*  
🔗 [LinkedIn Profile](https://linkedin.com) *(add your link here)*

---
