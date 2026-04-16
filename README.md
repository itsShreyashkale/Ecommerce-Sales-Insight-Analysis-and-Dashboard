# 🛒 E-Commerce Data Analysis & Dashboard

![Dashboard Preview](C:\Users\shrey\Downloads\interview da\Ecommerce Dashboard\preview.png)

---

## 📌 Project Overview

This project focuses on analyzing an e-commerce dataset to uncover insights related to **sales performance, customer behavior, product demand, and operational efficiency**.

The analysis is performed using **Python (Google Colab)** for data processing and **Power BI** for building an interactive and business-oriented dashboard.

The goal is to transform raw transactional data into **actionable insights** that support data-driven decision-making.

---

## 🎯 Objectives

* Analyze revenue trends and overall business performance
* Understand customer purchasing behavior (B2B vs B2C)
* Identify high-performing products, categories, and sizes
* Evaluate cancellation trends and customer satisfaction
* Optimize logistics and fulfillment efficiency
* Provide actionable recommendations for business growth

---

## 🧹 Data Cleaning & Preparation

* Handled missing values in `Amount` using **median imputation**
* Applied business logic: **set Amount = 0 for cancelled orders**
* Converted `Date` column to proper datetime format
* Removed duplicate records while preserving valid transactions
* Standardized categorical fields (Status, Category, etc.)
* Resolved inconsistencies in order status (case sensitivity issues)
* Created derived columns:

  * Month
  * Weekday
  * Cleaned Status Categories

---

## 📊 Key Analysis Performed

### 🔹 Financial Performance

* Total Revenue Analysis
* Monthly Revenue Trends
* Weekly Sales Patterns (Weekend spike observed)
* Average Order Value (AOV)

---

### 🔹 Product & Inventory Analysis

* Best-Selling Categories (Set, Kurta dominate)
* Size-wise Demand (M & L highest)
* Quantity Distribution
* Identification of high-demand vs low-performing products

---

### 🔹 Customer Insights

* B2B vs B2C Analysis (B2C dominates revenue)
* Top Cities & States by Sales
* Regional demand patterns
* Customer purchase behavior (mostly single-item orders)

---

### 🔹 Logistics & Fulfillment

* Fulfillment Type Comparison (Amazon vs Merchant)
* Shipping Service Level Analysis
* Identification of inefficiencies in Easy Ship

---

### 🔹 Customer Satisfaction & Returns

* Monthly Cancellation Trend
* Cancellation Rate Analysis (~14–15%)
* Problematic Categories Identification
* Impact of logistics on cancellations

---

## 📈 Power BI Dashboard

An interactive dashboard designed to provide a **complete business overview**.

### 🔹 KPI Cards

* Total Revenue
* Total Orders
* Average Order Value
* Cancellation Rate
* Delivery Rate

---

### 🔹 Visualizations

* Revenue Trend Over Time
* Sales by Category
* Top States by Revenue
* Revenue Split (B2B vs B2C)
* Order Distribution by Fulfillment
* Cancellation Trend
* Category-wise Quantity & Returns

---

### 🔹 Filters / Slicers

* Month
* State
* Customer Type (B2B / B2C)

---

## 🔍 Key Insights

* Revenue peaks in April and shows **seasonal variation**
* Sales are higher during **weekends**, especially Sundays
* Business is heavily dependent on **B2C customers**
* Categories like **Set and Kurta contribute majority of revenue**
* Demand is concentrated in **Maharashtra, Karnataka, Bengaluru**
* Customers mostly purchase **single items per order**
* Cancellation rates (~14–15%) highlight **logistics challenges**
* Easy Ship shows higher cancellations compared to Merchant fulfillment

---

## 💡 Recommendations

* Improve logistics efficiency, especially in **Easy Ship**, to reduce cancellations
* Strengthen demand forecasting and inventory planning during peak periods
* Increase AOV through **bundling and cross-selling strategies**
* Focus on high-performing categories while improving low-performing ones
* Align inventory with demand (focus on M & L sizes)
* Expand presence in underperforming regions
* Enhance delivery speed and tracking to improve customer satisfaction

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy, Matplotlib)
* Google Colab
* Power BI
* Excel / CSV

---

## ⚠️ Challenges Faced

* Handling missing values and inconsistent data formats
* Resolving status inconsistencies affecting key metrics
* Debugging differences between Colab and Power BI results
* Applying correct business logic for cancellations and revenue
* Designing meaningful KPIs and DAX measures
* Structuring the dashboard based on business problem areas

---

## 🧠 Key Learnings

* Importance of data cleaning order and validation
* Impact of business logic on KPIs (e.g., cancellations & revenue)
* Practical use of DAX for real-world metrics
* Designing dashboards aligned with business objectives
* Converting raw data into actionable insights

---

## ✅ Conclusion

This project demonstrates how data analysis can drive business decisions by:

* Identifying revenue trends and customer behavior
* Highlighting operational inefficiencies
* Providing actionable recommendations

The combination of **Python-based analysis** and an **interactive Power BI dashboard** delivers a complete solution for evaluating and improving e-commerce performance.

---
