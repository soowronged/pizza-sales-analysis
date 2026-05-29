# pizza-sales-analysis
A project investigating a weekend drop in pizza delivery orders.
# 🍕 Pizza Sales Delivery Analysis

## 📌 Business Problem
Our local pizza shop noticed a significant drop in customer satisfaction ratings over the weekend. This project analyzes recent transaction and delivery data to pinpoint the operational bottleneck causing the issue.

## 🛠️ Tools Used
* **Excel / CSV:** For initial data gathering.
* **Python (Pandas):** For calculating average delivery times.

## 🧼 Data Cleaning Process
* Formatted the `order_date` column into a standardized YYYY-MM-DD template.
* Flagged and isolated delivery times that exceeded the company's 30-minute target.

## 📊 Key Insights
* **The Bottleneck:** On May 2nd, the average delivery time spiked to **47.5 minutes** (well above our 30-minute guarantee).
* **The Impact:** As delivery times crossed the 40-minute mark, average customer ratings plummeted from a perfect 5 stars down to 1.5 stars.

## 💡 Recommendations
* **Increase Kitchen Staffing:** The data shows delays occur heavily during weekend peak hours, implying the kitchen cannot keep up with order volume.
* **Driver Re-routing:** Optimize delivery routes for multi-order trips on Saturday nights.
