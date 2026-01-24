# 📊 End-to-End Data Analytics Business Report

## 1. Executive Summary

This project demonstrates a complete, real-world **data analytics lifecycle**, transforming a single messy and unstructured CSV file into a **business-ready analytics solution**. Using **Python for data cleaning and exploratory data analysis (EDA)** and **Power BI for modeling and visualization**, the project delivers a **5-page executive dashboard** focused on explaining **revenue and profit movements**, identifying **operational inefficiencies**, and supporting **data-driven decision-making**.

The final output enables stakeholders to clearly understand **why revenue and profit increased or decreased**, rather than simply observing the numbers.

---

## 2. Business Problem


The core business challenges addressed in this project:

* Why is revenue increasing or decreasing?
* Is profit growth aligned with revenue growth?
* Which products, categories, and discounts are eroding margins?
* How much profit is lost due to shipping delays?
* Which operational areas require immediate action?

---

## 3. Data Overview

### 3.1 Raw Data Source

* Single raw CSV file
* Contained mixed transactional, customer, product, and shipping information
* Highly unnormalized and inconsistent

### 3.2 Final Data Model (6 Datasets)

The raw file was split and normalized into the following datasets:

1. **Orders** – Order dates, shipping details, delivery risk
2. **Order Items** – Revenue, profit, quantity, discounts
3. **Products** – Product pricing and category mapping
4. **Categories** – Product categorization
5. **Customers** – Customer demographics and segmentation
6. **Departments** – Organizational structure

This structure supports a **star schema**, optimized for analytics and Power BI performance.

---

## 4. Data Cleaning & Preparation (Python)

### 4.1 Tools Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn (EDA)

### 4.2 Key Cleaning Steps

* Removed duplicates and invalid records
* Standardized date formats
* Handled missing and null values
* Corrected data types (dates, numeric fields)
* Validated revenue and profit calculations
* Split raw data into normalized CSV files

### 4.3 Output

* Clean, analytics-ready datasets
* Reliable foundation for EDA and BI reporting

---

## 5. Exploratory Data Analysis (EDA)

EDA was performed in Python to understand patterns, anomalies, and relationships before dashboard development.

### Key EDA Insights:

* Revenue growth does not always translate into profit growth
* High discounts correlate with lower profit margins
* Certain products consistently generate low or negative profit
* Shipping delays significantly impact profitability
* Profit volatility increases during high-discount periods

EDA findings directly influenced **KPI design and dashboard structure**.

---

## 6. Power BI Data Model

### 6.1 Schema Design

* Fact Table: **Order Items**
* Dimension Tables: Orders, Products, Categories, Customers, Departments

### 6.2 Relationships

* One-to-many relationships
* Single-direction filtering
* Optimized for performance and clarity

### 6.3 Why This Model?

* Faster DAX calculations
* Easier KPI creation
* Clear business logic

---

## 7. KPI Framework

The dashboard uses business-focused KPIs rather than raw metrics.

### Core KPIs Include:

* Total Revenue
* Total Profit
* Profit Margin %
* Revenue Growth %
* Profit Growth %
* Low Margin Product %
* Profit Loss Due to Late Delivery
* Late Delivery Rate

Each KPI is designed to answer a **specific business question**, not just display a number.

---

## 8. Dashboard Structure (5 Pages)

### Page 1: Executive Revenue & Profit Overview

**Purpose:** Assess overall business health

* Revenue vs Profit Trend
* Growth indicators
* High-level performance KPIs
  
<img width="1287" height="727" alt="Screenshot 2026-01-25 041135" src="https://github.com/user-attachments/assets/ff547a10-313f-442e-ad81-3bd583591a1a" />


---

### Page 2: Revenue Quality & Growth Drivers

**Purpose:** Understand whether growth is sustainable

* Revenue growth vs volatility
* Category and region contribution
* Discount impact analysis

<img width="1291" height="724" alt="Screenshot 2026-01-25 041203" src="https://github.com/user-attachments/assets/e4497303-9393-4d32-818b-24b52bf26d5e" />

---

### Page 3: Margin & Discount Analysis

**Purpose:** Identify margin erosion

* Low-margin products
* Discount vs profit relationships
* Pricing inefficiencies

<img width="1291" height="719" alt="Screenshot 2026-01-25 041229" src="https://github.com/user-attachments/assets/05c13ff8-2f73-4492-a7d6-95af99ad47e4" />

---

### Page 4: Shipping & Operational Losses

**Purpose:** Quantify operational inefficiencies

* Profit loss due to late deliveries
* Shipping method performance
* Operational bottlenecks

<img width="1293" height="724" alt="Screenshot 2026-01-25 041247" src="https://github.com/user-attachments/assets/546a8925-75eb-4ae9-ab97-1d7355ec5c78" />

---

### Page 5: Root Cause & Deep Dive Analysis

**Purpose:** Explain *why* performance changes

* Decomposition tree
* Drill-down analysis
* Action-oriented insights

<img width="1292" height="720" alt="Screenshot 2026-01-25 041309" src="https://github.com/user-attachments/assets/8f5a002d-f8e5-41eb-a142-401fd53796b5" />

---

## 9. Business Insights Delivered

### Key Findings:

* Revenue growth is partially driven by aggressive discounting
* Several high-volume products operate at dangerously low margins
* Late deliveries cause measurable profit erosion
* Certain shipping methods consistently underperform
* Operational inefficiencies vary by region

---

## 10. Business Recommendations

* Re-evaluate discount strategies for low-margin products
* Optimize or renegotiate underperforming shipping methods
* Monitor late delivery KPIs weekly
* Focus growth on high-margin categories
* Introduce margin thresholds before applying promotions

---

## 11. Tools & Technologies

* **Python:** Data cleaning & EDA
* **Power BI:** Data modeling, DAX, visualization
* **DAX:** KPI and business logic creation
* **CSV:** Data storage & normalization

---

## 12. Project Deliverables

* Cleaned and normalized CSV datasets
* Python EDA notebooks
* Power BI (.pbix) dashboard
* Business-focused KPI framework
* Executive-ready analytics report

---

## 13. Conclusion

This project demonstrates how **raw, messy data** can be transformed into **clear, actionable business insights** using a structured analytics approach. By combining Python-based EDA with Power BI storytelling, the final solution goes beyond reporting and enables **decision-making grounded in data**.

---
