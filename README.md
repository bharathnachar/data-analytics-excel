# 🛒 Data Analytics for Freshco Hypermarket (November 2024)

This project focuses on analyzing sales, order, delivery, and customer data for Freshco Hypermarket using Microsoft Excel. The objective was to uncover inefficiencies, improve delivery operations, analyze customer behavior, and enable data-driven business decisions.

---

## 📌 Project Overview

- **Client/Scenario:** Freshco Hypermarket – a large retail chain
- **Goal:** Analyze operational metrics across orders, delivery, and customer activity
- **Technology:** Microsoft Excel (Formulas, PivotTables, Charts, Conditional Formatting)

---

## 🎯 Problem Statement

Freshco Hypermarket needed visibility into:

- Order patterns across time slots and geographies  
- Completion and cancellation trends  
- Customer behavior and lifetime value  
- Delivery time optimization and rating patterns  
- Areas of high discounts, delivery charges, or inefficiencies  

---

## 🗂️ Dataset Attributes

| Field                          | Description                                                                 |
|--------------------------------|-----------------------------------------------------------------------------|
| Order Timestamp                | Order placed time                                                          |
| User ID                        | Unique ID of the customer                                                  |
| Order Pickup Geo               | Pickup area location                                                       |
| Order Drop Geo                 | Drop area location                                                         |
| Order ID                       | Unique identifier for an order                                             |
| Products                       | List of products in each order                                             |
| Partner Store Reach Time       | Time when the delivery partner reached the pickup location                 |
| Partner Start for Delivery Time| Time when delivery partner started the journey                             |
| Completed/Cancelled Timestamp  | Time when delivery was completed or cancelled                             |
| Completion Flag                | Status of delivery (Completed or Not)                                      |
| Order Rating                   | Customer rating for order and delivery                                     |
| Product Amount                 | Total product value before discount                                        |
| Delivery Charges               | Transport cost which may vary by location                                  |
| Discount                       | Reduction offered on product/service                                       |

---

## ✅ Key Task Categories & Activities

### 📦 Order Level Analysis
- Analyze order distribution by slot and delivery area
- Identify areas with highest month-over-month order growth (Jan–Sep)
- Calculate delivery charges as % of product amount (by slot and month)
- Analyze discount % by product and time slot
- Evaluate discounts across drop area and slot level

### ✔️ Completion Rate Analysis
- Analyze completion rate by slot vs. day of week (Sunday to Saturday)
- Completion rate at drop area level
- Completion rate by product count (required column creation)
- Provide insights on completion trends and anomalies

### 👥 Customer Level Analysis
- Identify completion rate by acquisition source
- Calculate LTV per customer
- Aggregate LTV at acquisition source level
- Evaluate revenue (Product Amount – Discount) per acquisition source and month
- Identify trends in revenue, items per order, and delivery charges across acquisition levels
- Detect rating patterns based on order size, time, and charges

### 🚚 Delivery Analysis
- Calculate overall delivery time by slot and area
- Compare delivery times: weekdays vs weekends (requires new column)
- Analyze delivery delays based on delivery start time vs completion
- Detect delivery time patterns across slots and areas

---

## 📊 Tools & Techniques Used

- Excel Functions: `VLOOKUP`, `IF`, `COUNTIFS`, `SUMIFS`, `DATEDIF`, `TEXT`, `WEEKDAY`
- PivotTables & PivotCharts
- Conditional Formatting for trends and flags
- Dashboard layout for insights and KPIs

---

## 🔍 Sample Insights

- 📉 Weekend orders had higher completion delays in northern zones
- 🕒 Late-night orders showed lower ratings but higher average value
- 🛍️ Customers acquired via referral had better LTV and larger basket size
- 📈 High discount levels impacted delivery success negatively in certain slots

---

## 🧠 Outcome

- Improved understanding of time-based order fulfillment issues
- Uncovered customer segments driving high LTV
- Pinpointed zones requiring delivery ops improvement
- Enabled Freshco to take actionable steps to boost satisfaction and reduce costs

---

## 📁 Files Included

- `data_analysis_report_summary.pdf` – Project documentation

---

## 💡 Skills Demonstrated

- Data Cleaning and Transformation
- Business Operations Analysis
- Delivery Performance Metrics
- Customer Segmentation and LTV
- Excel-based Dashboarding
- Pivot Tables


