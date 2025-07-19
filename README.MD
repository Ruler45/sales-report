
# Automobile Sales Performance Dashboard

## 📊 Project Overview

This Power BI project provides a comprehensive and interactive dashboard to analyze automobile sales performance. The report offers a high-level overview of key business metrics and allows for a granular deep-dive into product performance, customer demographics, and sales trends over time. The primary goal is to empower business stakeholders to make data-driven decisions by identifying top/bottom performing products, key markets, and revenue trends.

---

## ✨ Dashboard Features

The report is composed of a main dashboard for a quick overview and a detailed secondary page for in-depth product analysis, accessible via bookmarks.

### KPIs (Key Performance Indicators)

The main dashboard highlights four critical business metrics at the top:

* **Total Orders:** 146K
* **Total Sales:** $13.74M
* **Total Profit:** $5.61M
* **Most Sold Product:** 1992 Ferrari 360 Spider red

---

## Visualizations and Interactivity

The report is highly interactive, featuring filters, bookmarks, and custom tooltips to enhance the user experience.

### Main Dashboard

![Main Dashboard](/images/main.png)

* **Filters:** The entire report can be dynamically filtered by:

  * Year
  * City
  * Employee Name
  * Product Line

* **Top 5 & 5 Least Sold Products:** These horizontal bar charts quickly identify the highest and lowest revenue-generating products, respectively.

* **Count of Customers by City:** A map visual that illustrates the geographic distribution of the customer base across continents.

* **Total Revenue by Product Line:** A pie chart that breaks down the percentage of total revenue contributed by each product category.

  * **Classic Cars** are the most significant contributor at **41.19%**.

* **Sum of Sales by Order Year:** A column chart that displays sales performance from 2003 to 2005, with a notable peak in **2004** ($6.4M).

### Advanced Interactivity

**1. Report Page Tooltip** 💡

To provide more context without cluttering the main view, a custom tooltip is implemented on the **Total Revenue by productLine** pie chart. When a user hovers over a slice of the pie (e.g., "Classic Cars"), a pop-up bar chart appears, showing the top-selling products within that specific category.

![Tooltip Example](/images/tooltip.png)

**2. Bookmarks for Detailed Analysis** 📖

The dashboard utilizes bookmarks to navigate to a secondary, more detailed page focused on product analysis. This allows users to seamlessly switch from a high-level overview to a granular examination.

![More information/Bookmark Page](/images/more_info.png)

The "Product Line Details" page includes:

* **Sum of Sales & Quantity Ordered by Product Line:** Bar charts providing absolute values for sales and units sold for each category.
* **Sum of Sales & Quantity Ordered by ProductName:** Bar charts that rank individual products by sales and units sold.
* **Sum of Sales by Year:** A line chart that visualizes the sales trend across the three years, reinforcing the insights from the main dashboard.

---

## 🚀 How to Use the Dashboard

1. **Get a High-Level View:** Start on the main dashboard to understand the overall business health through the KPIs and summary charts.
2. **Filter Data:** Use the slicers on the left-hand panel to narrow down the data to a specific year, city, employee, or product line.
3. **Explore Product Lines:** Hover your mouse over a segment in the **Total Revenue by productLine** pie chart to trigger the tooltip and see the top products within that line.
4. **Deep-Dive Analysis:** Click the designated bookmark to navigate to the detailed view for a more thorough breakdown of product sales and quantities.
