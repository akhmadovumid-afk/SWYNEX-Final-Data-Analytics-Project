# SWYNEX Technologies Internship - Final Data Analytics Case Study

## 📌 Executive Summary
This repository contains the comprehensive end-to-end data analytics project completed as the final task for the **SWYNEX Technologies Internship**. The project covers the entire data lifecycle: raw data cleaning, exploratory data analysis (EDA), interactive dashboard development, and business-driven recommendations based on overall sales performance.

---

## 🎯 Business Problem Statement
An e-commerce business required actionable insights into its sales operations, customer ratings, product category performance, and regional sales distribution. The raw dataset contained duplicate records, missing values, inconsistent formats, and needed data standardization before meaningful analysis could take place.

---

## 🛠️ Data Pipeline & Methodology

### Phase 1: Data Cleaning & Preparation (Task 1)
* **Missing Value Treatment:** Imputed missing values for numerical attributes and standardized categorical fields.
* **Deduplication:** Identified and eliminated duplicate transaction records to ensure accurate calculations.
* **Feature Engineering:** Verified and formatted currency fields, calculated line-item revenues, and cleaned date structures (`order_date`).

### Phase 2: Exploratory Data Analysis (Task 2)
* **Category Breakdown:** Discovered that **Electronics** ($1.83M) and **Clothing** ($1.53M) generate the highest proportion of total revenue.
* **Geographic Distribution:** Analyzed revenue across four key territories (**West, North, South, East**), revealing a well-balanced distribution with the West region leading slightly at $1.35M.
* **Summary Metrics:** Total dataset sales aggregated to **$5.11M** across **5,000 orders**.

### Phase 3: Interactive Visual Dashboard (Task 3)
* **Platform:** Microsoft Power BI Desktop.
* **Key Features:**
  * **Executive KPI Cards:** Total Revenue ($5.11M), Total Orders (5K), Average Customer Rating (2.97/5.0).
  * **Interactive Visuals:** Clustered Column Chart for category revenue and Donut Chart for regional revenue share.
  * **Dynamic Cross-Filtering:** Interactive region and date range slicers for real-time analysis.

---

## 📈 Key Business Insights & Recommendations
1. **Focus Marketing on Top Categories:** Electronics and Clothing generate >65% of overall sales. Prioritize inventory expansion and promotional campaigns in these segments.
2. **Address Customer Satisfaction:** The average customer rating of **2.97 / 5.0** indicates potential friction in product quality or delivery speed. Improving post-purchase service and shipping efficiency is recommended.
3. **Regional Marketing Alignment:** Sales are evenly distributed across regions, showing strong brand presence; targeted localized offers in the East region can help close the minor revenue gap.

---

## 📁 Repository Structure
