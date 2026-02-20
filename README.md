# Coca-Cola USA: Retail Planning & Hindsight Analysis Dashboard

## 📌 Project Overview

This project serves as a **Retail Business Intelligence** case study focused on **Direct-to-Consumer (D2C)** and **B2B Retail Network** performance. Using a dataset of over $12M in sales, I performed a comprehensive **Hindsight Analysis** to identify volume variances, operating margins, and retailer performance across the USA.

The logic applied here mirrors the data structures found in enterprise planning tools like **Anaplan** and B2B platforms like **NuOrder**.

## 📊 Key Retail Metrics Tracked

* **Total Sales & Units Sold:** High-level volume planning metrics to track market demand.
* **Average Price:** Monitoring price integrity and promotional impact across regions.
* **Operating Profit & Margin:** Analyzing "Value Realization" to ensure sustainable growth.
* **Variance Analysis (2022 vs. 2023):** Identifying year-over-year (YoY) growth patterns to inform future inventory allocation.

## 🛠 Technical Workflow

### 1. Data Engineering & Cleansing

* **Source:** Raw transaction-level data including Retailer IDs, Invoice Dates, and SKU-level details (Beverage Brands).
* **Processing:** Sanitized data for statistical rigor, ensuring consistent date formats and currency alignment for executive-ready reporting.

### 2. Multi-Dimensional Modeling

* Built a "Connected Planning" architecture within Excel to segment data by **Region** (Midwest, Northeast, etc.) and **Retailer Type** (Amazon, Walmart, Target).
* Applied **B2B Partner Logic** to analyze performance specifically for external distributors (Macy's/Nordstrom style partners like BevCo and FizzyCo).

### 3. Visualization & Storytelling

* **Hindsight Dashboard:** Developed interactive charts showing **Sales vs. Operating Profit Margin by Quarter**.
* **Assortment Analysis:** Ranked beverage brands by variance to determine which products drive the highest ROI.

## 🚀 Relation to Retail Planning (AEO/NuOrder/Anaplan)

While this project focuses on beverage distribution, the **analytical framework** is directly transferable to Apparel Planning and Allocation:

* **Hindsight Analysis:** The 2022 vs. 2023 variance tables simulate the "Seasonal Hindsight" used to plan future clothing assortments.
* **Volume Planning:** Quarterly trends help predict future "Units Sold" requirements, similar to seasonal allocation.
* **B2B Alignment:** Tracking individual retailer performance (e.g., Amazon vs. Walmart) mirrors managing B2B orders for partners like **Macy’s** or **Nordstrom**.

## 📁 Repository Resources

* `/Data`: Raw CSV/Excel Retailer Dataset.
* `/Analysis`: Pivot tables and logic layers for variance calculation.
* `/Dashboard`: The final Coca-Cola USA Retailer Dashboard (as seen in the project screenshots).
* `/Documentation`: Business Charter outlining project milestones and stakeholder requirements.

---
