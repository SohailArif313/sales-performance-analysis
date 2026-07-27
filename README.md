# Sales Performance Analysis Report

## Project Overview

This report analyzes sales performance data to understand the company's
overall business performance, sales trends, customer behavior, product
performance, geographic distribution, and shipping operations.

The analysis is based on historical order data covering sales transactions
from 2015 to 2018.

The main objective of this analysis is to identify:

- Overall business performance
- Top-performing products and categories
- High-value customers
- Geographic sales patterns
- Sales trends and seasonality
- Shipping and delivery performance
- Actionable business opportunities



## Executive Summary

The business generated total sales of **$2,261,536.78** from **4,922** orders and served **793** unique customers.

The strongest sales performance came from the **Technology** category and the **West** region. Sales also showed strong growth after 2016, with 2017 and 2018 experiencing significant year-over-year growth.

The analysis also identified opportunities to improve customer retention, manage slow-moving products, reduce seasonal sales dips, and investigate delivery performance in the Central region.

### Key Metrics

| Metric | Value |
|---|---:|
| Total Sales | $2,261,536.78 |
| Total Orders | 4,922 |
| Unique Customers | 793 |
| Unique Products | 1,861 |
| Average Delivery Time | 4.0 days |
| Top Category | Technology |
| Top Region | West |
| Most Used Shipping Mode | Standard Class |



## 1. Business Performance

The overall business performance was evaluated using total sales, total
orders, unique customers, and unique products.

The business generated its highest annual sales in **2018**, with total sales
of **$722,052.02**.

Sales declined by **4.26%** in 2016 but recovered strongly in the following
years, growing by **30.64%** in 2017 and **20.30%** in 2018.

### Sales Trend


![Yearly Sales Trend](reports/charts/yearly_sales_trend.png)


## 2. Sales by Category

Technology was the strongest-performing category, contributing **36.59%** of
total revenue.

This indicates strong demand for technology-related products and suggests
that inventory planning and marketing efforts should continue to support this
category.

![Sales by Category](reports/charts/category_sales.png)



## 3. Sales by Region

The West region generated the highest sales, with total revenue of
**$710,219**.

This makes the West region the strongest geographic market in the dataset.
The business should continue monitoring demand in this region and ensure
sufficient product availability.

![Sales by Region](reports/charts/region_sales.png)

### Top States

![Top 10 States by Sales](reports/charts/top_states.png)

### Top Cities

![Top 10 Cities by Sales](reports/charts/top_cities.png)



## 4. Customer Analysis

Customer analysis was performed to understand high-value customers, customer
segments, and repeat purchasing behavior.

The top 10 customers contributed **6.80%** of total sales, indicating that a
small group of customers represents a meaningful share of total revenue.

Only **1.64%** of customers placed only one order, highlighting an opportunity
to improve customer retention and encourage repeat purchases.

### Top Customers

![Top 10 Customers by Sales](reports/charts/top10_customers.png)

### Customer Segment Performance

![Sales by Customer Segment](reports/charts/segment_sales.png)

### Repeat vs One-Time Customers

![Repeat vs One-Time Customers](reports/charts/repeat_vs_onetime.png)


## 5. Product Analysis

The top-selling product by sales was **Canon imageCLASS 2200 Advanced Copier**.

The **Technology** category was the strongest-performing category, while
**Phones** was the top-performing sub-category within Technology.

The analysis also identified **94 products** that were ordered only once,
indicating limited demand for these products.

### Top-Selling Products

![Top 10 Products by Sales](reports/charts/top10_products.png)

### Category and Sub-Category Performance

![Sales by Category and Sub-Category](reports/charts/category_subcategory_sales.png)



## 6. Time Trend Analysis

Sales performance varied significantly across years and months.

The best-performing year was **2018**, generating **$722,052.02** in sales.

The strongest months were **November** and **December**, while **January** and
**February** consistently showed the weakest performance.

This indicates a seasonal pattern in the business, with stronger demand toward
the end of the year.

### Monthly Sales Trend

![Monthly Sales Trend](reports/charts/monthly_sales_trend.png)

### Seasonal Sales Pattern

![Seasonal Sales Pattern](reports/charts/seasonal_pattern.png)

### Year vs Month Sales Heatmap

![Sales Heatmap](reports/charts/year_month_heatmap.png)


## 7. Shipping Analysis

Standard Class was the most commonly used shipping mode, accounting for
**59.79%** of all orders.

The overall average delivery time was **3.96 days**.

The Central region had the highest average delivery time at **4.07 days**,
compared with the overall average of **3.96 days**.

This difference is relatively small, but the Central region should still be
monitored for potential logistics inefficiencies.

### Shipping Mode Usage

![Shipping Mode Usage](reports/charts/shipmode_counts.png)

### Delivery Time Distribution

![Delivery Time Distribution](reports/charts/delivery_time_distribution.png)

### Average Delivery Time by Shipping Mode

![Delivery Time by Shipping Mode](reports/charts/delivery_by_shipmode.png)

### Average Delivery Time by Region

![Delivery Time by Region](reports/charts/delivery_by_region.png)

### Region and Shipping Mode Analysis

![Region Shipping Mode Heatmap](reports/charts/region_shipmode_heatmap.png)




## Final Business Recommendations

### 1. Focus Marketing on Top Region

**Finding:** `West` region generates `$710,219` in sales, the highest among all regions.

**Recommendation:** Increase marketing budget allocation and inventory
availability in the `West` region to capitalize on existing strong demand.

### 2. Strengthen the Leading Product Category

**Finding:** `Technology` contributes `36.59%` of total revenue.

**Recommendation:** Prioritize supplier relationships and stock levels for
`Technology` products, and explore expanding the product range within this
category.

### 3. Retain High-Value Customers

**Finding:** Top 10 customers contribute `6.80%` of total sales.

**Recommendation:** Launch a loyalty/rewards program targeting these
high-value customers to protect this critical revenue base.

### 4. Convert One-Time Buyers

**Finding:** `1.64%` of customers ordered only once.

**Recommendation:** Implement post-purchase email campaigns or first-time
buyer discounts to encourage repeat purchases.

### 5. Address Weak Product Performance

**Finding:** `94` products were ordered only once or generated minimal sales.

**Recommendation:** Consider bundling slow-moving products with bestsellers,
running clearance promotions, or discontinuing consistently underperforming
SKUs after further investigation.

### 6. Smooth Out Seasonal Revenue Dips

**Finding:** Sales consistently perform weakest in `January` and `February`.

**Recommendation:** Run targeted seasonal promotions or discounts during these
low-performing months to stabilize monthly revenue.

### 7. Investigate Slow Shipping in Specific Region

**Finding:** `Central` has the highest average delivery time at `4.07 days`,
compared to the overall average of `3.96 days`.

**Recommendation:** Review fulfillment and logistics processes for the `Central`
region to identify potential bottlenecks and improve delivery speed.

### 8. Promote Faster Shipping Options

**Finding:** `59.79%` of orders use `Standard Class`, which also has the
slowest average delivery time.

**Recommendation:** Highlight faster shipping options at checkout, potentially
with small incentives, to give customers more delivery choices and improve
the overall customer experience.

### 9. Leverage High-Performing Sub-Categories

**Finding:** `Phones` is the top performer within `Technology`.

**Recommendation:** Feature the `Phones` sub-category prominently in marketing
campaigns and consider cross-selling related products.

### 10. Improve Product Portfolio Decisions

**Finding:** `94` products were ordered only once, indicating limited demand
for these products.

**Recommendation:** Review the performance of rarely ordered products and
consider bundling them with popular products, offering clearance promotions,
or reducing future inventory investment in consistently underperforming items.




## Conclusion

This analysis provided a comprehensive overview of the business's sales
performance, customers, products, geographic markets, time trends, and
shipping operations.

The analysis identified strong performance in the Technology category and
West region, significant seasonal patterns in sales, valuable high-spending
customers, slow-moving products, and potential opportunities to improve
customer retention and shipping operations.

The findings and recommendations in this report can help support better
decisions related to marketing, inventory management, customer retention,
product planning, seasonal promotions, and logistics.
