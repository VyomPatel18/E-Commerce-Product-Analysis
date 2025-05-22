# E-Commerce-Product-Analysis

### 1. Project Overview

The **E-Commerce Product Analysis Dashboard** is a detailed and interactive business intelligence solution created using **Power BI** for visualization and **Python** for data preprocessing. This project explores key insights across sales trends, product performance, customer behavior, discount effects, time-based patterns, and payment analysis based on a cleansed dataset (`ecommerce product_dataset_clean.csv`).

### 2. Purpose

This dashboard serves the following key purposes:

* Evaluate overall and time-based sales performance.
* Identify top-performing products and categories.
* Understand purchasing behavior across users.
* Assess the impact of discounts on product performance.
* Track revenue by payment method.
* Support data-driven decisions in marketing, pricing, and customer engagement.

### 3. Data Preparation

* **Source File**: ecommerce product\_dataset\_clean.csv
* **Cleaning Method**: Performed in Python (handling missing values, formatting dates, calculating discount percentages, and deriving metrics like final price and day of the week).

### 4. Dashboard Sections & Questions Covered

#### 4.1 Sales Performance Analysis

* **Q1**: Total revenue across all periods is **Rs. 757.28K**.
* **Q2**: Top months and weeks show peak sales in January and week 2.
* **Q3**: A clear upward trend is visible via the line chart by month/year.
* **Q4**: The average sales per invoice is **Rs. 206.91**.

#### 4.2 Product Performance

* **Q5**: Highest selling products are visible via bar charts (top products by revenue).
* **Q6**: Top revenue-contributing categories are:

  * Clothing (15.23%)
  * Books (14.68%)
  * Home & Kitchen, Sports, and others follow closely.
* **Q7**: Average discount by category:

  * Home & Kitchen and Sports offer higher discounts (\~15-20%).

#### 4.3 Customer Behavior

* **Q8**: The platform had **3660 unique customers**.
* **Q9**: Average revenue per customer is **Rs. 206.91**.
* **Q10**: Bar chart of top customers highlights high-value users by User\_ID.
* **Q11**: Average products bought per customer were analyzed through purchase data and invoice values.

#### 4.4 Discounts & Pricing Insights

* **Q12**: Average discount across all sales is **18.83%**.
* **Q13**: Highest discounts are applied on select products shown via individual Product\_IDs.
* **Q14**: Visual correlation between discount percentage and final price suggests mixed results, indicating category-specific behavior.

#### 4.5 Time-Based Purchasing Patterns

* **Q15**: Highest purchases occur on **Thursday and Sunday**.
* **Q16**: Weekdays are more profitable, generating **70.06%** of total revenue.
* **Q17**: Peak sales recorded in **Week 2** and **January**.

#### 4.6 Payment Method Analysis

* **Q18**: Most used payment methods are:

  * Credit Card (20.6%)
  * UPI and Debit Card follow closely.
* **Q19**: Sales are fairly distributed across payment types, all contributing around 19-20%.
* **Q20**: Discounts vary slightly across payment methods, with Net Banking and UPI linked to slightly higher discount usage.

### 5. Tools & Technologies Used

* **Python** (Pandas, NumPy): For data cleaning and transformation.
* **Power BI Desktop**: For building interactive visualizations.
* **DAX**: To create calculated fields such as total sales, average invoice, discounts, and user insights.

### 6. Business Benefits

* Enables identification of best-selling products and categories.
* Optimizes discount strategy to align with sales performance.
* Helps understand user behavior and personalize marketing.
* Supports operational planning through weekday and time-based sales patterns.
* Informs decisions on preferred payment gateway partnerships.

### 7. Conclusion

This E-Commerce Product Analysis Dashboard integrates preprocessed data with advanced analytics to deliver 360-degree visibility into sales, customer preferences, and product dynamics. The combined use of Python and Power BI ensures clean, insightful, and decision-ready reporting for business optimization.
