# Sales-Analysis
Sales Customer Behavior Analysis using Python, MySQL And Power Bi

**Overview**

This project analyzes customer shopping behavior using a transactional dataset of retail purchases. The workflow includes:

1.Raw data ingestion

2.Python-based cleaning, feature engineering & EDA

3.SQL analytical querying

4.Power BI dashboard visualization

The goal is to understand how customers shop, which products are popular, the effect of discounts, segment behavior, and spending patterns across demographics and shipping choices.

**Project Pipeline**

Raw CSV → Python (Cleaning & EDA) → Clean Dataset → SQL Database
        → Analytical Queries → Power BI Dashboard

**Tools & Technologies**

| Tool                                            | Purpose                                                                 |
| ----------------------------------------------- | ----------------------------------------------------------------------- |
| **Python (Pandas, NumPy, Matplotlib, Seaborn)** | Data cleaning, preprocessing, feature engineering, exploratory analysis |
| **SQL (MySQL )**                                | Business queries, segmentation, aggregation                             |
| **Power BI**                                    | KPI dashboards, segmentation visuals, interactive analysis              |
| **MS Word**                                     | SOP documentation & reporting                                           |


**Python Cleaning Phase**

 Load raw CSV
 Handle missing values (especially review_rating)
 Standardize column names
 Feature engineering:

1.Age groups (18–25, 26–35, 36–50, 50+)

2.Purchase frequency

3.Flags for subscriber & discount usage

**Exploratory analysis:**

1.purchase_amount distribution

2.spend by age group

3.purchase frequency vs spend

**Export: customer_clean.csv**

📄 Notebook: notebooks/cleaning_and_EDA.ipynb

**Visual Explorations**

Histogram: purchase_amount distribution

Boxplot: age_group vs spending

Scatter: frequency vs average order value

Trend analysis: category-level spending

**SQL Analysis Phase**

After uploading the cleaned dataset into a customer_behaviour database, SQL scripts were used to answer key business questions:

**Core Queries**

Revenue by gender

Subscriber vs non-subscriber spending patterns

New, returning, and loyal segmentation

Top 3 products per category

Discount-dependent products

Average spend by shipping type

High-value discount users

**Power BI Dashboard**


**Executive Summary**

Total revenue, average purchase, distinct customers

Revenue by gender and subscription status

**Customer Segmentation**

New vs Returning vs Loyal distribution

Average spend by each segment

**Product Analytics**

Top sellers and best-rated products

**Discount Analytics**

Discount dependency and product pricing sensitivity

**Checkout & Shipping**
Revenue contribution by shipping type (express vs standard)


**Key Insights**

1.Subscribers spend more per transaction and represent high LTV.

2.Loyal customers are primary repeat buyers, supporting retention strategies.

3.Some products are heavily discount-dependent, requiring margin optimization.

4.Express shipping customers are premium buyers, indicating upsell potential.

5.Ages 26–40 are high-contribution shoppers, ideal for targeted campaigns.

6.Top-rated and top-selling products should be amplified through cross-selling.

