# Retail Customer Insights & Segmentation Analysis

An end-to-end data analytics project analyzing customer shopping behavior across 3,900 transactions to uncover spending patterns, customer segments, and subscription drivers.

---


## Dataset

Public retail transactions dataset sourced from Kaggle — 3,900 rows, 18 columns covering customer demographics, purchase details, and shopping behaviour.

---

## Tools & Technologies

- **Python** — Data cleaning, EDA, and feature engineering
- **MySQL** — Business queries and customer segmentation
- **Power BI** — Interactive dashboard for stakeholder reporting

---

## Project Structure

```
├── customer_shopping_behavior.csv        # Raw dataset
├── eda_cleaning.ipynb                    # Python notebook (EDA + cleaning)
├── queries.sql                           # All 14 MySQL queries
├── dashboard.pbix                        # Power BI dashboard file
└── Customer_Insights_Segmentation.pdf   # Full project report
```

---

## What Was Analyzed

- Revenue breakdown by gender, age group, season, and category
- Customer segmentation — New, Returning, and Loyal (via CTE)
- Discount dependency by product and age group
- Repeat buyer vs subscription behaviour
- Top products per category using window functions
- Category rating ranking using `RANK()` window function

---

## Key Findings

- **2,518 repeat buyers are not subscribed** — the biggest untapped growth opportunity
- Loyal customers use discounts the most (43.65%) despite being the most committed segment
- Clothing dominates revenue ($104K) but ranks last in customer ratings
- Footwear is rated highest but contributes the least revenue
- Fall is the strongest season; Summer the weakest

---
