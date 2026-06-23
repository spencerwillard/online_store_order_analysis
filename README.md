# Online Store Order Analysis

## Project Overview

This project analyzes a fictional online retail dataset to identify trends in revenue, customer behavior, product performance, return rates, and data quality issues.

The project follows a structured analytics workflow:

1. Data Understanding
2. Data Quality Assessment
3. Data Cleaning
4. Feature Engineering
5. Exploratory Analysis
6. Filtering Analysis
7. Aggregation Analysis
8. Customer Analysis
9. Data Visualization
10. Executive Summary

---

## Business Questions

This analysis aims to answer questions such as:

- Which states generate the most revenue?
- Which product categories perform best?
- Which categories experience the highest return rates?
- How do customers behave?
- Are there significant data quality issues?
- What impact do outliers have on business metrics?

---

## Dataset Overview

The dataset contains approximately:

- 10,000 orders
- 2,876 unique customers
- Order-level transaction information
- Product categories
- Shipping information
- Return indicators
- Customer identifiers

---

## Data Cleaning Highlights

Several data quality issues were identified and addressed:

- Removed 50 duplicate records
- Standardized state values
- Standardized product category values
- Corrected data types
- Investigated suspicious quantities and prices
- Evaluated extreme outlier orders

---

## Key Findings

### Business Performance

### Business Performance

- Total Orders Analyzed: **9,990**
- Total Revenue (Outliers Removed): **$26.99M**
- Average Order Value: **$2,728**
- Average Shipping Time: **5.03 Days**
- Overall Return Rate: **11%**

### Revenue Performance

- Highest Revenue State: **Colorado ($3.51M)**
- Highest Revenue Category: **Electronics ($5.66M)**

### Customer Insights

- Unique Customers: **2,874**
- Average Customer Spend: **$2,726**

### Operational Insights

- Highest Return Rate Category: **Clothing (12.2%)**
- No strong relationship was identified between returns and discounts, shipping times, or payment status.

### Outlier Analysis

- 10 extreme orders accounted for approximately **94% of total revenue**
- These records materially distorted business metrics and were excluded from primary analysis

---

## Visualizations

The project includes:

- Revenue by Product Category
- Revenue by State
- Monthly Revenue Trend
- Distribution of Order Values
- Return Rate by Product Category

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Structure

```
project/
│
├── data/
├── notebooks/
│   └── online_store_analysis.ipynb
├── images/
├── README.md
```

---

## Key Takeaways

This project demonstrates:

- Data cleaning and validation
- Feature engineering
- Exploratory data analysis
- Grouped aggregations
- Business-focused analysis
- Data visualization
- Executive-level communication of findings