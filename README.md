# 🛍️ Retail Customer Analysis

An end-to-end **Business Analytics project** focused on understanding **customer shopping behavior** in a retail environment. This project demonstrates how raw transactional data can be transformed into **actionable business insights** using Python, SQL, and Power BI.

---

## 📌 Project Objective

Retail businesses generate large volumes of transaction data but often struggle to convert it into meaningful insights. The objective of this project is to:

* Analyze customer purchasing behavior
* Identify high-value customer segments
* Evaluate the impact of discounts and subscriptions
* Understand product and category performance
* Support data-driven business decision-making

---

## 🧩 Business Problem Statement

The retail company wants to answer key business questions such as:

* Which customer segments contribute the most revenue?
* Do discounts actually drive higher-value purchases?
* How does subscription status affect customer spending?
* Which products and categories perform best?
* Are repeat buyers more likely to subscribe?

This project addresses these questions through structured data analysis and visualization.

---

## 🗂️ Dataset Overview

* **Total Records:** 3,900 transactions
* **Total Features:** 18 columns

### Key Data Attributes

* **Customer Details:** Age, Gender, Location, Subscription Status
* **Transaction Details:** Item Purchased, Category, Purchase Amount, Season
* **Behavioral Metrics:** Discount Applied, Review Rating, Previous Purchases, Shipping Type

---

## 🔄 Project Workflow

The project follows a clear, industry-standard analytics workflow:

1. Business Problem Understanding
2. Data Import & Cleaning (Python)
3. Exploratory Data Analysis (EDA)
4. Data Storage in SQL Database
5. Business Analysis using SQL
6. Data Visualization using Power BI
7. Key Findings & Business Recommendations
8. Documentation, GitHub Upload & Presentation

### 📊 Workflow Diagram

![Project Workflow](895182ae-3248-4a03-950d-e18391a0ee09.jpeg)

---

## 🛠️ Tools & Technologies

* **Python:** Pandas, NumPy (Data Cleaning & EDA)
* **SQL (PostgreSQL):** Business queries & analysis
* **Power BI:** Interactive dashboard & visualization
* **GitHub:** Version control & project documentation

---

## 🧪 Data Cleaning & EDA (Python)

Key preprocessing steps included:

* Handling missing values in review ratings using median imputation
* Standardizing column names (snake_case)
* Removing redundant features
* Feature engineering:

  * Age groups
  * Purchase frequency metrics

This ensured high-quality, analysis-ready data.

---

## 🧮 Business Analysis (SQL)

The cleaned dataset was loaded into a PostgreSQL database and analyzed using SQL to generate business insights.

### Key SQL Analyses

* Revenue contribution by gender and age group
* High-spending customers using discounts
* Subscriber vs non-subscriber comparison
* Top-rated and top-selling products
* Customer segmentation (New, Returning, Loyal)
* Repeat buyers vs subscription behavior

---

## 📈 Data Visualization (Power BI)

An interactive Power BI dashboard was created to visualize:

* Total customers & average purchase value
* Revenue by category and age group
* Subscription distribution
* Sales trends and customer segments

The dashboard enables stakeholders to explore insights dynamically using filters and slicers.

---

## 🔍 Key Business Findings

* Loyal customers contribute a significant share of total revenue
* Discount usage increases order volume without significantly reducing average order value
* Subscribers show higher engagement and repeat purchases
* Express shipping users tend to spend slightly more per order

---

## 💡 Business Recommendations

* Strengthen subscription programs with exclusive benefits
* Introduce loyalty rewards to retain high-value customers
* Apply targeted discounts instead of blanket offers
* Focus marketing efforts on high-revenue age groups and customer segments

---

## ✅ Conclusion

This project demonstrates a complete **retail analytics pipeline**, combining Python, SQL, and Power BI to deliver meaningful business insights. It reflects real-world data analysis practices and showcases the ability to translate d
