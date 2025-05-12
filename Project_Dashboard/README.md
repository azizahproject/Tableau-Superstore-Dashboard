# 📈 Superstore Dashboard — Technical Overview

This folder contains the Tableau workbook file for the Superstore Dashboard project.
![Image](https://github.com/user-attachments/assets/c889d1d2-e1d6-4ec2-b45f-436545e304d6)

## 📌 Objective
To visualize sales data in a way that highlights key performance indicators, identifies high-performing segments and products, explores sales and profit trends over time, and presents geographical distribution of sales and profit through a map view.

## 🛠️ Tools & Files
- **Tool**: Tableau
- **File**: [Superstore Dashboard#1.twbx](https://github.com/azizahproject/Tableau-Superstore-Dashboard/blob/main/Project_Dashboard/Superstore%20Dashboard%20%231.twbx) — contains all visualizations and dashboard layouts. [Superstore Dataset](https://github.com/azizahproject/Tableau-Superstore-Dashboard/tree/main/0_Resources/Dataset) — contains all data.

## ⚙️ Dashboard Build

### 📊 KPI Cards
![Image](https://github.com/user-attachments/assets/7ac890f8-23c7-432f-b499-0e77e4fa5c41)
- 🛠️ **Dashboard Feature**: Includes four key KPI cards — Total Sales, Total Profit, Total Orders, and Total Customers.
- 📈 **Comparison Logic**: Each KPI compares the selected year with the previous year to highlight growth or decline.
- 📉 **Trend Visualization**: Sparklines added for each KPI to display performance over time at a glance.
- 💡 **Insights Gained**: Provides quick understanding of overall business health, with noticeable increases or drops helping to guide further analysis.

### 📊 Bar Chart – Segment, Category, and Top 10 Sub-Category
![Image](https://github.com/user-attachments/assets/11338eee-48e3-4827-a251-62a26164e8e0)
- 📊 **Dashboard Feature**: Displays sales and profit performance across three business levels: Segment, Category, and Sub-Category.
- 📌 **Design Choice**: Segment & Category: Simple horizontal bar charts for easy comparison across fewer groups. Top 10 Sub-Category: Focused view to highlight only the best-performing sub-categories, improving clarity and impact.
- 🔍 **Sorting Logic**: All charts sorted in descending order by sales to emphasize the most impactful areas first.
- 💡 **Insights Gained**: Allows users to quickly identify which customer segments and product groups drive the highest revenue and profit.

### 🧾 Product Table – Top 10 Best-Selling Products
![Image](https://github.com/user-attachments/assets/09b337c1-6351-4aea-9f93-0abd652b87dd)
- 📊 **Dashboard Feature**: A data table showcasing the top 10 products with the highest sales.
- 📌 **Design Choice**: Tabular format chosen to present detailed information such as product name, sales, profit, and order count in a clear and compact layout.
- 🔍 **Sorting Logic**: Sorted by descending sales to immediately surface best-sellers.
- 💡 **Insights Gained**: Helps identify high-demand products and evaluate whether strong sales are aligned with profitability.

### 🗺️ Sales & Profit Map
![Image](https://github.com/user-attachments/assets/cd52f51a-8f81-498a-a63e-42930479ab23)
- 📊 **Dashboard Feature**: A filled map that visualizes sales and profit distribution across different states.
- 🌍 **Design Choice**: Geographic visualization helps in quickly identifying regional performance patterns.
- 🎯 **Color Encoding**: Sales and profit values are represented through color gradients, enabling easy comparison across locations.
- 💡 **Insights Gained**: Reveals states with the highest contributions to sales and those potentially experiencing losses or low profit, supporting location-based business decisions.

### 📈 Weekly Sales Trend
![Image](https://github.com/user-attachments/assets/94c2deca-4919-42c7-b4b1-ba20b40bfa72)
- 📊 **Dashboard Feature**: A line chart that tracks weekly sales performance from 2021 to 2023.
- 📅 **Design Choice**: Weekly granularity provides a detailed view of seasonality and fluctuations in sales over time.
- 🔍 **Data Aggregation**: Dates are grouped by week number and year, allowing trend analysis across different periods.
- 💡 **Insights Gained**: Highlights sales peaks and dips, enabling businesses to identify recurring patterns or anomalies throughout the year.

### 📄 Order Details Table
![Image](https://github.com/user-attachments/assets/2956724d-c444-4166-a715-0d99f3d02d6d)
- 📊 **Dashboard Feature**: An interactive table displaying detailed order-level data including product name, category, segment, quantity, sales, and profit.
- 🔧 **Design Choice**: A tabular format allows users to deep-dive into individual transactions beyond aggregated visuals.
- 🔍 **Filter & Interaction**: Linked to parameters and filters from the main dashboard, ensuring consistency across views.
- 💡 **Insights Gained**: Useful for verifying specific orders, identifying outlier transactions, and reviewing granular performance metrics per product or customer.



---

💡 *This is a learning project — feedback and suggestions are welcome!*


