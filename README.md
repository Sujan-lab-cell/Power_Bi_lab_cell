# 📊 E-commerce Sales Dashboard (Power BI)

## 🔹 Overview

This project is an **interactive Power BI dashboard** designed to analyze e-commerce sales performance.
It provides insights into **revenue, profit, customer behavior, and product performance** using dynamic visualizations and filters.

---

## 🎯 Objective

* Analyze **sales and profit trends**
* Identify **profitable vs loss-making regions**
* Understand **customer purchasing behavior**
* Evaluate **category and sub-category performance**

---

## 📁 Dataset Description

### 🧾 Orders Table

* Order ID
* Customer Name
* State, City
* Order Date

### 📦 Details Table

* Amount (Sales)
* Profit
* Quantity
* Category / Sub-Category
* Payment Mode
* ADV (Average Value)

🔗 Tables are connected using **Order ID**

---

## 📊 Key Metrics (KPIs)

* 💰 **Total Sales (Amount)**
* 📦 **Total Quantity Sold**
* 📉 **Total Profit**
* 📊 **Profit Margin (%)**
* 📈 **Average Order Value (ADV)**

---

## 📐 DAX Measure Used

```DAX
Profit Margin % = DIVIDE(SUM(Details[Profit]), SUM(Details[Amount]), 0)
```

---

## 📈 Dashboard Features

### 🎛️ Filters (Slicers)

* State
* Category
* Order Date

---

### 📊 Visualizations

* **Profit Margin by State**

  * Highlights profitable (green) and loss-making (red) regions

* **Profit by Month**

  * Shows monthly profit trends

* **Quantity by Category**

  * Distribution of sales across categories

* **Quantity by Payment Mode**

  * Customer payment preferences

* **Profit by Sub-Category**

  * Identifies high and low performing products

* **Sales vs Profit by State**

  * Compares revenue and profitability

---

## 🎨 Key Features

* ✔ Interactive dashboard with slicers
* ✔ Conditional formatting (Red–Yellow–Green logic)
* ✔ Clean and professional UI design
* ✔ Real-time filtering and insights
* ✔ Business-focused analytics

---

## 🧠 Key Insights

* Some regions are **loss-making despite good sales**
* Profit margins vary significantly across states
* Certain product categories generate **higher volume but lower profit**
* Payment modes like **COD and UPI dominate**
* Monthly profit trends show **fluctuations in business performance**

---

## 🚀 Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling

---

## 📸 Dashboard Preview

![Dashboard Screenshot](dashboard.png)

---

## 📌 Conclusion

This dashboard helps businesses:

* Identify **problem areas**
* Improve **profitability**
* Make **data-driven decisions**

---

## 👤 Author

**Sujan KS**

---
