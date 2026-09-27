# FMCG Sales Data Cleaning & Preparation

## 📌 Overview

This project focuses on **data cleaning, validation, and feature engineering** for an FMCG sales dataset using Python. The objective was to transform raw transactional data into a structured, consistent, and analysis-ready dataset for downstream business analytics and visualization.

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**

## 🔍 Data Preparation

The dataset contains **50,750 records and 15 attributes** covering orders, customers/companies, locations, products, pricing, payments, discounts, GST, and delivery information.

Key data preparation activities included:

* Dataset profiling and structural validation
* Missing-value identification and treatment
* Duplicate record detection and removal
* Date standardization and conversion
* Categorical data normalization
* Numeric type conversion and validation
* Product-level median imputation for missing unit prices
* Correction of negative quantity values
* Handling missing payment methods
* Identification and correction of abnormal delivery-day values
* Range and anomaly validation

## 📊 Feature Engineering

The following business metrics were created from the cleaned transactional data:

* **Gross Amount**
* **Discount Amount**
* **Net Sales (INR)**

These calculated fields prepare the dataset for further sales analysis and reporting.

## 📁 Output

The cleaned dataset is exported as:

`cleaned_Fmcg_Sales.csv`

## 🎯 Project Outcome

The final output is a **clean, standardized, and analysis-ready FMCG sales dataset** that can be used as a foundation for further **SQL analysis, Excel reporting, and Power BI dashboard development**.

---

**Project Focus:** Data Cleaning • Data Quality • Feature Engineering • Business Analytics

## Exploratory Data Analysis — Python

After cleaning the dataset, I performed exploratory data analysis using Python to understand sales performance, identify trends and patterns, and find unusual sales records.

### Analysis Performed

* Checked dataset structure and data quality
* Calculated descriptive statistics
* Calculated key business KPIs
* Analyzed sales by product category
* Analyzed sales by state
* Analyzed sales by store type
* Analyzed sales by city tier
* Analyzed monthly sales trends
* Examined high-value sales records
* Checked the relationship between discounts and net sales

### Key KPIs

* **Total Orders:** 50,000
* **Total Net Sales:** Approximately ₹160.87 million
* **Average Order Value:** Approximately ₹3,217
* **Total Quantity Sold:** Calculated from the cleaned dataset

### Key Insights

1. Dairy & Staples is one of the largest contributors to total sales.
2. Sales vary significantly across states.
3. Kirana Stores generate the highest sales among the store types.
4. Tier 1 cities generate the highest sales compared with Tier 2 and Tier 3 cities.
5. Monthly sales vary throughout the analysis period.
6. Some orders have unusually high sales values and require further investigation.
7. The relationship between discount percentage and net sales is weakly negative.

### Python Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

### Notebook

The complete Python EDA is available here:

`python/FMCG_Sales_EDA.ipynb`

# FMCG Sales Analysis – Power BI Dashboard

## 📊 Project Overview

This Power BI project presents an interactive business dashboard built on an FMCG sales dataset containing approximately **50,000 sales transactions** across multiple companies, products, categories, cities, states, store types, and payment methods.

The dashboard is the visualization and business intelligence stage of the overall FMCG Sales Analysis project.

The analysis workflow was:

**Python → Exploratory Data Analysis → SQL Analysis → Power BI Dashboard → Business Insights**

The Python and Python EDA analysis was completed separately before building the Power BI dashboard. This Power BI project focuses on converting the analyzed data into interactive dashboards that can help business users understand sales performance and identify important trends and opportunities.

---

# 🎯 Business Objective

The main objective of this dashboard is to provide a clear view of FMCG sales performance and answer important business questions such as:

- How much revenue is the business generating?
- How are sales changing over time?
- Which product categories and products generate the most sales?
- Which states, cities, and city tiers contribute the most revenue?
- Which store types perform better?
- How many orders and units are being sold?
- What is the average order value?
- How much discount is being given?
- How does sales performance change across different business dimensions?
- What operational patterns can be identified from delivery performance?

---

# 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Interactive Data Visualization**
- **Python & Pandas** – data preparation and EDA
- **SQL** – business analysis and validation

---

# 📁 Dataset

The dashboard is based on an FMCG sales dataset containing approximately **50,000 rows**.

The dataset includes information about:

- Order ID
- Company
- Order Date
- State
- City
- City Tier
- Store Type
- Product Category
- Product Name
- Quantity Sold
- Unit Price
- Payment Method
- GST Rate
- Discount
- Delivery Days
- Gross Amount
- Discount Amount
- Net Sales

The data covers sales activity across **2024 and 2025**.

---

# 📊 Dashboard Structure

The Power BI report contains **5 main dashboard pages**, each designed to answer a different group of business questions.

---

## 1. Executive Sales Overview

This page provides a high-level summary of the overall business performance.

### Key KPIs

- Total Net Sales
- Total Orders
- Total Quantity Sold
- Average Order Value
- YoY Sales Growth
- Average Delivery Days

### Key Visuals

- Monthly Sales Trend
- Sales by Product Category
- Sales by Store Type
- Interactive business filters

### Business Questions Answered

- What is the overall sales performance?
- How many orders and units were sold?
- What is the average value of an order?
- How are sales changing over time?
- Which categories contribute significantly to total sales?
- How are different store types performing?

This page is designed as the **management-level overview** of the business.

---

# 2. Sales & Trend Analysis

This page focuses on understanding sales movement over time.

### Analysis Includes

- Monthly sales performance
- Yearly comparison
- Quarterly performance
- YoY growth
- Sales growth amount
- Discount impact
- Payment method analysis

### Business Questions Answered

- How does sales performance change month by month?
- How does 2025 compare with 2024?
- Which periods generate higher sales?
- How significant are discounts in the overall sales structure?
- Which payment methods are being used across orders?

This page helps identify **sales trends and changes in business performance over time**.

---

# 3. Product & Category Analysis

This page focuses on product-level and category-level performance.

### Analysis Includes

- Sales by product category
- Sales by individual product
- Quantity sold by product
- Category performance
- Product ranking
- Sales and quantity comparison

### Business Questions Answered

- Which product categories generate the highest sales?
- Which individual products are major contributors?
- Which products have high sales volume?
- Are high-volume products also generating high revenue?
- Which products or categories may require additional business attention?

This page provides a detailed view of **product portfolio performance**.

---

# 4. Geographic & Store Analysis

This page analyzes sales across different geographic locations and store types.

### Analysis Includes

- Sales by state
- Sales by city
- Sales by city tier
- Sales by store type
- Quantity by store type
- Company performance

### Business Questions Answered

- Which states generate the highest sales?
- Which cities contribute the most revenue?
- How does performance differ between Tier 1, Tier 2, and Tier 3 cities?
- Which store types generate significant sales?
- How does company performance vary across the business?

This analysis helps understand **where sales are being generated and through which retail channels**.

---

# 5. Operations & Business Insights

The final dashboard page focuses on operational metrics and business-level relationships.

### Key Metrics

- Average Delivery Days
- Average Order Value
- Discount Percentage
- Sales per Unit
- Sales per Order

### Analysis Includes

- Delivery performance
- Payment method distribution
- Discount-related analysis
- Sales and quantity relationships
- Operational performance indicators

### Business Questions Answered

- How efficiently are orders being delivered?
- What is the average value generated per order?
- How much of gross sales is represented by discounts?
- How does sales value relate to quantity sold?
- What operational patterns can be identified from the dataset?

This page connects sales performance with **operational and commercial metrics**.

---

# 📈 Key DAX Measures

Several DAX measures were created to support the dashboard, including:

- Total Sales
- Gross Sales
- Total Discount
- Total Quantity
- Total Orders
- Average Order Value
- Average Unit Price
- Average Delivery Days
- Discount %
- Previous Year Sales
- YoY Growth %
- Sales Growth Amount
- Sales per Unit
- Average Discount per Order
- Orders per City
- Sales per Order
- Product Rank

These measures allow the dashboard to dynamically respond to filters and provide meaningful business calculations.

---

# 🗓️ Time Intelligence

A dedicated date table was created to support time-based analysis.

The dashboard uses:

- Year
- Month
- Month-Year
- Quarter
- Year-Quarter
- Previous Year Sales
- YoY Growth

This allows users to analyze sales chronologically and compare performance across different periods.

---

# 🎛️ Interactive Analysis

The dashboard includes interactive filters that allow users to analyze the business from different perspectives.

Users can filter the report based on dimensions such as:

- Year
- State
- Product Category
- Store Type
- Company
- City Tier

When filters are applied, the KPI cards and visualizations update dynamically.

---

# 💡 Business Value

The dashboard transforms raw FMCG transaction data into an interactive business reporting solution.

It allows business users to:

- Monitor overall sales performance
- Track sales trends
- Identify important products and categories
- Understand geographic performance
- Compare different store types
- Monitor operational metrics
- Analyze discounts and order value
- Compare current performance with previous periods
- Explore the data interactively

The objective is not only to visualize data, but to make the data easier to use for **business analysis and decision-making**.


