# 🛍️ Amazon Store Sales Data Analysis (Power BI Project)

### 📘 Project Overview
This project presents an **interactive Power BI dashboard** built using the *Amazon Store Sales Dataset*.  
The dashboard provides a comprehensive analysis of **sales performance, profit trends, customer segments, and payment behavior** across different regions.  
It helps businesses uncover key insights to make **data-driven decisions** and optimize sales strategy.

---

## 🎯 Objectives
- Analyze **total sales**, **profit**, and **order trends** across different categories and segments.  
- Identify **top-performing regions**, **profitable sub-categories**, and **preferred payment modes**.  
- Track **shipping performance** and customer preferences.  
- Design an **interactive Power BI dashboard** for easy exploration and insights.

---

## 🧩 Tools & Technologies Used
- **Power BI Desktop**  
- **Microsoft Excel / CSV Dataset**  
- **Power Query Editor** for Data Cleaning & Transformation  
- **DAX (Data Analysis Expressions)** for Calculations and KPIs

---

## 📊 Key Performance Indicators (KPIs)
- 🏷️ **Total Sales:** ₹0.52M  
- 💰 **Total Profit:** ₹0.07M  
- 📦 **Total Orders:** 1,901  
- 👥 **Customer Segments:** Consumer, Corporate, Home Office

---

## 📈 Visualizations Used
### ✅ Displayed Visuals
1. **Order ID by Payment Mode (Donut Chart)** – Shows distribution of orders across COD, Online, and Card payments.  
2. **Product ID by Ship Mode (Donut Chart)** – Represents shipment breakdown by shipping method (Standard, First, Second Class).  
3. **Sales by Segment (Donut Chart)** – Highlights contribution of each customer segment.  
4. **Sales vs Profit by Quantity (Clustered Column Chart)** – Displays relationship between sales, profit, and quantity sold.  
5. **Profit by Sub-Category (Bar Chart)** – Identifies the most and least profitable sub-categories.  
6. **Sales by Category (Bar Chart)** – Shows total sales from Office Supplies, Furniture, and Technology.  
7. **Order ID by Returns (Pie Chart)** – Visualizes returned orders vs total orders.
8. **Sales by Region (Bar Chart)** *(Replaced Map Visual)*  
  
---

## 🧮 DAX Measures Used
```DAX
Total Sales = SUM('Amazon Sales Data'[Sales])

Total Profit = SUM('Amazon Sales Data'[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
```
These measures are used in KPIs, tooltips, and visuals for performance comparison.

---

## 🧾 Dataset Source
Dataset used in this project is a **sample sales dataset inspired by Amazon’s e-commerce transactions**, containing order details such as Order ID, Product Name, Category, Sales, Profit, Quantity, State, and Order Date.  

📂 **Source:** [Amazon Sales Dataset](https://github.com/Kamachari/Amazon-Store-Sales-Data-Analysis/blob/main/Amazon%20Store%20Sales%20Dataset.csv)

---

## 🖼️ Dashboard Preview
![Amazon Store Sales Dashboard](https://github.com/Kamachari/Amazon-Store-Sales-Data-Analysis/blob/main/Amazon%20Store%20Sales%20Data%20Dashboard.png)

*(Dashboard created in Microsoft Power BI Desktop — visualizing sales, profit, and order insights.)*

---

## 🧠 Insights Derived
- 💳 **Cash on Delivery (COD)** was the most used payment method.  
- 🏢 **Consumer Segment** generated the highest sales (₹228.8K).  
- 🚚 **Standard Class** shipping was used most frequently.  
- 📈 Sub-categories like **Copiers** and **Binders** contributed maximum profit.  
- 📅 Clear sales growth patterns observed over specific months.  
- 🌎 Regional sales visualization highlights performance variation by zone.

---

## 🧾 Steps Followed
1. Imported dataset into Power BI.  
2. Cleaned data using Power Query Editor.  
3. Built data model with relationships.  
4. Created DAX measures for KPIs and metrics.  
5. Designed interactive visuals for insights and storytelling.

---

## 🏁 Conclusion
The **Amazon Store Sales Dashboard** offers a detailed understanding of product performance, profit trends, and customer preferences.  
It enables data-driven strategies to improve overall sales efficiency and profitability.

---

## 👨‍💻 Author
**Buragapalli Kamachari**  
📍 Andhra Pradesh, India  
🔗 [LinkedIn](https://www.linkedin.com/in/boragapalli-kamachari)

