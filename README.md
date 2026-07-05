# 📊 Analisis Kinerja Bisnis Kimia Farma Tahun 2020–2023

## 📌 Project Overview
This project was developed as part of the Big Data Analytics Virtual Internship Program at Kimia Farma. The project aims to analyze Kimia Farma's business performance during the period of 2020–2023 by utilizing BigQuery SQL for data processing and Google Looker Studio for dashboard visualization.

The analysis integrates transaction, product, inventory, and branch data to provide insights into revenue performance, profit, branch performance, and geographical sales distribution across Indonesia.

---

## 🎯 Project Objectives

- Analyze business performance trends from 2020 to 2023.
- Identify the top-performing provinces based on total transactions and net sales.
- Evaluate branch performance using customer ratings and transaction ratings.
- Analyze the geographical distribution of profit across Indonesia.
- Transform raw data into actionable business insights through interactive dashboards.

---

## 🛠️ Tools & Technologies

- Google BigQuery
- SQL
- Google Looker Studio
- Data Cleaning & Transformation
- Data Visualization

---

## 📂 Dataset Used

The project utilizes four datasets:

- `kf_final_transaction`
- `kf_product`
- `kf_inventory`
- `kf_kantor_cabang`

These datasets were imported into BigQuery and combined through SQL queries using JOIN operations and calculated columns to create the final analytical table (`kf_analisa`). :contentReference[oaicite:1]{index=1}

---

## 🔄 Data Processing

The data processing steps include:

### 1. Data Import
- Create a new project and dataset in Google BigQuery.
- Import all CSV files into BigQuery.
- Create an analytical table (`kf_analisa`).

### 2. Data Transformation
- Perform data integration using SQL JOIN.
- Create calculated columns:
  - Gross Profit Percentage
  - Nett Sales
  - Nett Profit

### 3. Data Validation
- Verify data consistency.
- Ensure no duplicate records.
- Validate transaction and branch information.

---

## 📊 Dashboard Features

### Performance Overview
- Total Transactions
- Total Revenue
- Total Profit

### Revenue Trend Analysis
- Revenue comparison from 2020–2023.

### Provincial Performance Analysis
- Top 10 Provinces by Total Transactions.
- Top 10 Provinces by Nett Sales.

### Branch Performance Analysis
- Branches with the highest branch rating but lowest transaction rating.

### Geographical Analysis
- Interactive Indonesia Geo Map showing profit distribution by province.

The dashboard is equipped with interactive filters:

- Province
- City
- Year

All visualizations and KPI cards update dynamically based on the selected filters.

---

## 📈 Key Performance Indicators (2020–2023)

- **Total Transactions:** 672,458
- **Total Revenue:** Rp321.2 Billion
- **Total Profit:** Rp26.1 Billion

Kimia Farma recorded strong business performance with a high transaction volume and significant revenue generation during the period analyzed. :contentReference[oaicite:2]{index=2}

---

## 🔍 Key Business Insights

### 1. Business Performance Remained Relatively Stable
Revenue during 2020–2023 remained relatively stable, with the highest achievement recorded in 2022. However, the decline in 2023 may indicate a slowdown in business growth. :contentReference[oaicite:3]{index=3}

### 2. West Java Became the Largest Contributor
West Java generated the highest number of transactions and the highest net sales among all provinces, indicating a high concentration of business activity in the region. :contentReference[oaicite:4]{index=4}

### 3. Several Branches Need Service Evaluation
Several branches received the highest branch ratings but relatively low transaction ratings, indicating potential issues in service consistency and customer experience. :contentReference[oaicite:5]{index=5}

### 4. Profit Distribution is Uneven Across Provinces
The geographical analysis shows that profits are concentrated in several provinces, suggesting opportunities for market expansion in underperforming regions. :contentReference[oaicite:6]{index=6}

---

## 💡 Business Recommendations

### Optimize High-Performing Regions
Increase inventory allocation and marketing investment in provinces with high transaction volumes, particularly West Java.

### Improve Customer Experience
Conduct service quality evaluations for branches with low transaction ratings despite receiving high branch ratings.

### Develop Underperforming Provinces
Implement region-specific marketing strategies and expand market penetration in provinces with lower profitability.

### Monitor Revenue Trends
Investigate the decline in revenue during 2023 and develop strategies to restore growth momentum.

---

## 📊 Skills Demonstrated

- Data Cleaning and Transformation
- SQL Querying and Data Integration
- Data Modeling
- KPI Development
- Business Intelligence
- Interactive Dashboard Design
- Geographical Data Visualization
- Business Insight Generation
- Data-Driven Decision Making

---

## 📷 Dashboard Preview

![Kimia Farma Dashboard](dashboard-kimia-farma.png)

---
## 🔗 Live Dashboard
[View Dashboard](https://datastudio.google.com/reporting/c17295e6-a34a-46a0-8b58-68398de354c8)


---

## 📌 Conclusion

This project demonstrates end-to-end business performance analysis using BigQuery SQL and Google Looker Studio. By integrating multiple datasets and transforming them into interactive dashboards, the project provides valuable insights into revenue trends, regional performance, and business opportunities for Kimia Farma.

⭐ This project showcases practical skills in data analytics, business intelligence, and dashboard development by transforming raw business data into actionable insights and strategic recommendations.
