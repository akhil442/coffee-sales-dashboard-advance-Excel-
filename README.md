# ☕ Coffee Sales Dashboard (Excel End-to-End Project)

## 📌 Overview

This project demonstrates an end-to-end data analysis workflow in Microsoft Excel, where raw transactional data is transformed into an interactive dashboard. The dashboard enables users to analyze coffee sales performance across time, regions, and customer segments using dynamic visualizations and filters.

---

## 🎯 Problem Statement

Raw sales data often exists across multiple tables and lacks structure for meaningful analysis. This project focuses on integrating, cleaning, and transforming such data to build a user-friendly dashboard that supports business decision-making.

---

## 🛠️ Tools & Techniques Used

* Microsoft Excel
* Pivot Tables & Pivot Charts
* XLOOKUP
* INDEX MATCH
* Data Cleaning & Transformation
* Slicers & Timeline Filters

---

## 🔄 Project Workflow

### 1. Data Gathering

* Combined data from **Orders, Customers, and Products tables**
* Used **XLOOKUP** to retrieve customer details
* Used **INDEX MATCH** to dynamically fetch product data

### 2. Data Cleaning & Transformation

* Handled missing values and inconsistencies
* Standardized date formats and numerical values
* Created calculated column:

  * **Sales = Quantity × Unit Price**
* Converted dataset into a structured Excel table

### 3. Data Preparation

* Created readable fields:

  * Coffee Type Names (Robusta, Arabica, etc.)
  * Roast Type Names (Light, Medium, Dark)
* Removed duplicates and ensured data consistency

### 4. Data Analysis

* Built pivot tables for:

  * Sales over time
  * Sales by country
  * Top customers

### 5. Dashboard Development

* Designed interactive dashboard with:

  * Line Chart → Sales over time
  * Bar Chart → Sales by country
  * Bar Chart → Top 5 customers
* Added interactivity:

  * Timeline filter
  * Slicers (Roast Type, Size, Loyalty Card)

---

## 📊 Step-by-Step Development

### 🔹 Orders Data Preparation

* Combined datasets using XLOOKUP and INDEX MATCH
* Created calculated Sales column
* Cleaned and formatted dataset

![Orders](screenshots/orders.png)

---

### 🔹 Total Sales Analysis

* Built pivot table grouped by Month & Year
* Created line chart for sales trends across coffee types

![Total Sales](screenshots/totalsales.png)

---

### 🔹 Sales by Country

* Built pivot table for regional comparison
* Created bar chart and sorted performance

![Country](screenshots/country.png)

---

### 🔹 Top 5 Customers

* Applied filters to identify top customers
* Visualized contribution using bar chart

![Customers](screenshots/customers.png)

---

## 📊 Dashboard Features

* Sales trend analysis over time
* Regional performance comparison
* Top customer identification
* Interactive filtering using slicers and timeline

---

## 📈 Key Insights

* Sales vary significantly across coffee types
* Certain regions contribute more to total revenue
* A small group of customers drives major revenue
* Filters help quickly identify trends and patterns

---

## 🖼️ Screenshots

### 🔹 Full Dashboard

![Dashboard](screenshots/dashboard.png)

### 🔹 Interactive Filters

![Filters](screenshots/filters.png)

### 🔹 Key Visualizations

![Charts](screenshots/charts.png)

---

## 🚀 Improvements Added

* Structured project into a clean repository
* Improved readability using meaningful labels
* Enhanced dashboard layout and usability
* Added documentation and workflow explanation

---

## 📚 Credits

This project was inspired by a YouTube tutorial.

Original Source:
(Add YouTube link here)

---

## 👤 Author

Your Name
GitHub: https://github.com/YOUR-USERNAME
LinkedIn: (optional)
