# Excel Portfolio

A collection of Excel-based data analysis and dashboard projects created to demonstrate practical skills in data cleaning, data preparation, exploratory analysis, KPI development, data visualization, and business insight generation.

This repository currently features an **E-Commerce Sales Performance Analysis & Dashboard** project, built using transaction-level e-commerce data covering the period from **2020 to 2025**. The project transforms raw transactional data into structured analysis and an interactive Excel dashboard designed to provide a clear overview of sales performance.

## 📊 Featured Project: E-Commerce Sales Performance Analysis & Dashboard

### Project Overview

This project analyzes e-commerce transaction data to evaluate sales performance across different time periods, product categories, regions, payment methods, and customer-related metrics.

The main goal is to transform raw transaction data into meaningful business information that can help identify sales trends, major revenue contributors, regional performance differences, peak sales periods, and potential customer experience concerns.

The analysis is presented through an interactive Excel dashboard that allows users to explore the data dynamically using filters and visualizations.

### Business Problem

The business has accumulated transaction data containing information about orders, customers, products, regions, revenue, discounts, payment methods, delivery performance, and customer ratings. However, raw transaction data does not provide an efficient way to understand overall sales performance or identify areas that may require further investigation.

This project therefore focuses on evaluating sales performance and identifying important patterns within the data, particularly across:

* Sales performance over time
* Product category contribution
* Regional performance
* Monthly and quarterly sales patterns
* Payment method usage
* Customer ratings
* Delivery performance

### Business Questions

The analysis was designed to answer several key business questions:

1. How has revenue and order volume changed from 2020 to 2025?
2. Which product categories contribute the most to total revenue?
3. Which regions generate the highest revenue?
4. Which months show the strongest sales performance?
5. How does customer satisfaction vary across product categories?
6. Are there noticeable patterns in discounts, delivery performance, customer ratings, and sales that warrant further investigation?

## 🗂️ Dataset

The project uses an e-commerce transaction dataset containing **2,192 transaction records** and information related to sales, customers, products, regions, payments, delivery, and customer ratings.

Key variables include:

* Order ID
* Order Date
* Year
* Quarter
* Month
* Month Number
* Customer ID
* Product Category
* Region
* Quantity Sold
* Unit Price
* Discount
* Total Unit Price After Discount
* Total Revenue
* Payment Method
* Delivery Days
* Customer Rating

The dataset is used as a practice/simulated dataset for portfolio and analytical learning purposes.

## 🧹 Data Cleaning & Preparation

Before performing the analysis, the dataset was reviewed and prepared to ensure that it could be used consistently for analysis and visualization.

The preparation process included:

* Checking the dataset structure and data types
* Checking for missing values
* Checking for duplicate records
* Validating date-related fields
* Reviewing categorical values
* Checking numerical value ranges
* Preparing time-based fields such as Year, Quarter, Month, and Month Number
* Preparing calculated fields for sales analysis
* Applying appropriate number and display formats

The prepared dataset was then used as the foundation for Pivot Tables, KPI calculations, and dashboard visualizations.

## 🔎 Exploratory Data Analysis

Exploratory analysis was performed to understand the overall characteristics and performance patterns within the dataset.

The analysis covered several dimensions:

### Time Analysis

Revenue and order performance were analyzed across:

* Year
* Quarter
* Month

This analysis helps identify changes in sales performance over time and highlight periods with relatively high or low performance.

### Product Analysis

Product categories were compared based on:

* Revenue
* Quantity sold
* Customer rating

This helps identify the main contributors to revenue while also considering customer experience.

### Regional Analysis

Revenue performance was compared across:

* East
* North
* South
* West

This provides an overview of geographic sales distribution and highlights regions that may require further investigation.

### Customer & Operational Analysis

The project also explores:

* Customer rating
* Payment method
* Delivery days

These variables provide additional context beyond sales volume and revenue.

## 📈 Key Performance Indicators

The dashboard includes several key performance indicators designed to provide a high-level overview of business performance.

### Sales KPIs

* **Total Revenue:** $2,224,095.65
* **Total Orders:** 2,192
* **Total Quantity Sold:** 8,892
* **Average Order Value:** $1,014.64
* **Unique Customers:** 874

These KPIs provide a concise summary of the overall scale and performance of the transactions included in the dataset.

## 📊 Excel Dashboard

The project includes an interactive Excel dashboard developed using Pivot Tables, Pivot Charts, KPI calculations, and Slicers.

The dashboard provides a high-level view of:

* Total Revenue
* Total Orders
* Total Quantity Sold
* Average Order Value
* Total Unique Customers
* Revenue by Year
* Monthly Revenue Trend
* Revenue by Region
* Revenue by Product Category
* Payment Method Distribution
* Orders Trend by Year
* Average Customer Rating by Product Category

### Interactive Filters

The dashboard includes Slicers for:

* **Year**
* **Region**
* **Product Category**

These filters allow users to dynamically explore the dashboard and perform more focused analysis.

For example, users can select a specific year, region, or product category to investigate how sales performance changes across different segments.

## 💡 Key Insights

Several notable patterns were identified from the analysis.

### Revenue Trend

Revenue declined gradually from 2020 to 2023 before recovering in 2024. Revenue remained relatively stable between 2024 and 2025.

### Product Category

**Electronics** generated the highest revenue at approximately **$783.5K**, representing around **35.2% of total revenue**.

### Regional Performance

**West** recorded the highest regional revenue at approximately **$581.2K**, while **South** recorded the lowest at approximately **$506.2K**. Overall regional performance was relatively balanced.

### Quarterly Performance

**Q3** generated the highest quarterly revenue at approximately **$589.7K**, but also recorded the longest average delivery time at 6.26 days.

### August Performance

August generated the highest monthly revenue at **$217.7K**, while simultaneously recording the **lowest average customer rating (2.89)** and **longest average delivery time (6.76 days)**.

This pattern represents an area that may require further investigation, particularly around fulfillment capacity and customer experience during high-sales periods.

### Payment Channel

Card transactions generated **46.0% of total revenue** and had the shortest average delivery time (**5.84 days**), while COD had the longest (**6.36 days**).

### Customer Experience

Although Electronics was the highest-revenue category, Clothing recorded the highest average customer rating. Meanwhile, Home had the lowest average rating among the product categories.

This indicates that revenue performance and customer satisfaction do not necessarily move together.

## 🎯 Business Recommendations

Based on the observed patterns, several areas can be considered for further business investigation:

1. **Protect key revenue contributors**
   Monitor Electronics performance at a more detailed product level and evaluate inventory availability for high-contributing products.

2. **Review peak-period fulfillment capacity**
   Investigate fulfillment and delivery capacity during Q3 and August, where high sales activity coincides with longer delivery times.

3. **Investigate customer experience gaps**
   Investigate the relationship between delivery performance and customer ratings, especially during August and within the Home category, where customer ratings are relatively low.

4. **Investigate regional performance**
   Conduct deeper analysis of the South region to determine whether its lower revenue is associated with differences in order volume, product mix, or other transaction characteristics.

These recommendations are intended as areas for further investigation rather than definitive causal conclusions, as the dataset does not contain variables such as marketing expenditure, profit margin, inventory levels, or competitor activity.

## 🛠️ Tools & Skills

### Tools

* Microsoft Excel

### Skills Demonstrated

* Data Cleaning
* Data Validation
* Data Preparation
* Exploratory Data Analysis
* Pivot Tables
* Pivot Charts
* KPI Development
* Data Aggregation
* Data Visualization
* Interactive Dashboard Development
* Business Insight Generation
* Business Recommendations

## 📁 Project Structure

```text
E-commerce Sales Performance Analysis & Dashboard/
│
├── E-Commerce Sales Performance Dashboard.xlsx
├── Project Case Study.pdf
├── Dashboard Preview.png
└── README.md
```

The Excel workbook contains the data, analytical worksheets, Pivot Tables, and interactive dashboard. The accompanying case study documents the business problem, analytical approach, key findings, and recommendations.

## 📌 Project Purpose

This project is part of a personal data analytics portfolio and is intended to demonstrate the ability to move from raw transactional data to structured analysis, visualization, and business-oriented insights using Microsoft Excel.

Future projects in this repository may expand the portfolio into other areas of data analysis and visualization.
