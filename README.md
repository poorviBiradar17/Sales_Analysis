# 📊 Sales Performance Analysis (Power BI)

## 📘 Overview
A Power BI dashboard analyzing **Superstore sales data (2014–2017)**.
Includes KPIs, category-wise performance, customer segment insights, regional analysis, monthly trends, and top product performance.

---

## 🗂 Dataset Includes
- Order Date  
- Sales, Profit, Quantity, Discount  
- Category, Sub-Category  
- Segment  
- Region  
- Ship Mode  
- Product Name  

---

## 📌 Features
- **KPI Cards:** Sales, Profit, Quantity, Discount  
- **Sales by Category & Segment**  
- **Sales by Ship Mode**  
- **Monthly Sales Trend (Time Series)**  
- **Regional Performance**  
- **Top 10 Products**  
- **Sales vs Profit Scatter Plot**  
- **Year Slicers (2014–2017)**  

---

## 🔢 DAX Measures
```DAX
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Total Quantity = SUM(Orders[Quantity])
Total Discount = SUM(Orders[Discount])
```

## 🔍 Insights
- Technology category yields the highest sales & profit.  
- Corporate segment contributes ~50% of total revenue.  
- Standard Class is the most used shipping mode.  
- Sales peak in Nov–Dec every year.  
- West region performs the best overall.  

---

## 🛠 Tools Used
- Power BI Desktop  
- Power Query  
- DAX  
- Superstore Dataset  

---

## 🚀 How to Use
1. Clone the repository  
2. Open **Sales_Analysis.pbix** in Power BI Desktop  
3. Use slicers (Year, Region, Category) to explore insights  
