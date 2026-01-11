# 📊 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional retail data to uncover insights into spending patterns, customer segments, product performance, and subscription behavior.  
The goal is to convert raw data into actionable business insights that support marketing, pricing, and retention decisions.

**Dataset:**  
- 3,900 transactions  
- 18 features (demographics, purchases, discounts, subscriptions, reviews)

---

## 🧩 Business Questions
- Which customer groups generate the most revenue?
- Do discounts attract high-value customers?
- Are subscribers more valuable than non-subscribers?
- Which products and categories perform best?
- Does shipping type influence spending?

---

## 🗂 Dataset Summary
**Feature groups:**
- Customer demographics (age, gender, location, subscription status)
- Transaction details (item, category, amount, season, size, color)
- Behavioral signals (discounts, reviews, shipping type, purchase frequency)

**Data quality:**
- 37 missing values in review ratings
- Handled using median imputation by product category

---

## 🔍 Analysis Workflow

### 1. Data Preparation (Python)
- Data cleaning and exploration using pandas
- Column standardization (snake_case)
- Feature engineering:
  - Age groups
  - Purchase frequency
- Removed redundant columns after validation
- Loaded cleaned data into PostgreSQL

### 2. Business Analysis (SQL – PostgreSQL)
- Revenue by gender
- High-spending discount users
- Top-rated products
- Shipping type vs spend
- Subscribers vs non-subscribers
- Discount-dependent products
- Customer segmentation (New, Returning, Loyal)
- Repeat buyers vs subscriptions
- Revenue by age group

### 3. Visualization (Power BI)
- Interactive dashboard with KPIs
- Revenue by category and age group
- Subscription and shipping insights
- Filters for stakeholder exploration

---

## 📈 Key Insights
- Non-subscribers generate higher total revenue due to volume
- Express shipping users spend slightly more per order
- Loyal customers dominate transaction volume
- Some products are highly discount-dependent
- Younger and middle-aged customers contribute the most revenue

---

## 💡 Business Recommendations
- Strengthen subscription incentives
- Launch loyalty programs for repeat buyers
- Reassess discount-heavy products
- Promote top-rated and best-selling items
- Use targeted marketing for high-value segments

---

## 🛠 Tools & Skills
- Python (pandas)
- SQL (PostgreSQL)
- Power BI
- Exploratory Data Analysis
- Business Analytics & Segmentation

---

## 🎯 Why This Project
This project demonstrates end-to-end data analytics skills — from cleaning and querying data to building dashboards and delivering business-ready insights.
