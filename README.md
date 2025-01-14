# Catalyst Academy Overview

Catalyst Academy, an American edtech innovator founded in 2020, is dedicated to transforming education through cutting-edge technology and evidence-based pedagogy. Catalyst Academy provides personalized learning experiences that empower educators and learners to foster lifelong growth in a dynamic global landscape.

## Objective

This project aims to analyze 2023 sales and customer performance data to identify growth opportunities, optimize operations, and enhance customer engagement. Key areas of focus include:

- **Sales Performance**: Evaluating total sales, profit, and year-over-year growth.
- **Customer Insights**: Analyzing customer behavior, retention, and engagement metrics.

## Data Sources

- **Interactive Tableau Dashboard**: [Download here](#)
- **SQL Queries**: The SQL queries utilized to clean, organize, and prepare data for analysis and visualization can be found [here](#).
- **Original Dataset**: Includes `customers`, `locations`, `orders`, and `products` (raw data) on [GitHub](#).

---

## Dataset Overview

The dataset consists of **5,368 records** across four interconnected tables:

- **Customers**: IDs, names, and related orders.
- **Location**: Geographic details including postal codes, cities, and states.
- **Orders**: Transactional data with IDs, dates, and financial metrics.
- **Products**: Categories, subcategories, and descriptions.

---

## Data Cleaning Highlights

Preprocessing was applied to ensure data quality and usability:

1. **Duplicate Records**: Resolved duplicate IDs across customers, orders, and products.
2. **Missing Values**: Nulls in key fields were replaced with defaults (e.g., `'UNKNOWN'`) or flagged for further review.
3. **Standardization**: Fields like dates, strings, and numeric formats were unified for consistency.
4. **Referential Integrity**: Validated cross-table relationships to remove orphaned records.

These steps reduced inconsistencies by **98%**, ensuring the dataset was reliable for analysis and visualization.

---

## Analysis Tools and Deliverables

- **SQL**: Data cleaning, organization, and transformation.
- **Tableau**: Interactive dashboard for exploring trends by geography, customer behavior, and order patterns.
- **GitHub Repository**: Contains SQL queries, raw data, and data cleaning scripts.

---

## Business Value

The insights derived from this analysis provide actionable strategies to:

- **Increase customer retention** by targeting high-value segments.
- **Optimize category-level marketing** to capitalize on growth opportunities.
- **Address declining profitability trends** through pricing and inventory adjustments.

---

## Interactive Dashboard Preview

The dataset was visualized in Tableau ([View here](#)), revealing trends in churn and retention by tenure, geography, and gender.

---

# Executive Summary

Catalyst Academy’s 2023 Sales and Customer Insights Report identified key opportunities for increasing growth and enhancing customer engagement in the edtech space. The analysis used cleaned and validated data from **5,368 records** across `customers`, `orders`, `locations`, and `products`. This provided actionable insights on sales performance and customer behavior.

### Key Findings

- **Sales Growth**: Total sales reached **$732K**, a **20.4% year-over-year increase**, with profits rising by **13.8%** to **$93K**. The strongest growth occurred in Q4, led by subcategories like tablets and virtual labs.
- **Customer Engagement**: The total customer base grew by **8.7%** to **689**, with sales per customer increasing by **10.8%** to **$1,062**. **74%** of customers placed between 1–3 orders, while a highly engaged segment placed 4+ orders.
- **Profit Trends**: Weekly profits averaged **$2K**, with occasional negative weeks suggesting opportunities for operational or pricing optimizations.

### Key Recommendations

1. **Focus on High-Growth Subcategories**: Increase investments in tablets and virtual labs and address declines in coding platforms and LMS products through targeted marketing and product realignment.
2. **Enhance Mid-Tier Customer Engagement**: Introduce loyalty programs and incentives to encourage repeat purchases among mid-tier customers to increase overall profitability.
3. **Optimize Weekly Profitability**: Investigate and address factors that drive negative profit weeks to maintain consistent financial performance.
4. **Leverage High-Value Customers**: Develop personalized retention strategies for the top 10% of customers, who account for a significant share of overall profits.

By implementing these strategies, Catalyst Academy can strengthen its market position, maximize customer lifetime value, and drive sustained growth in the competitive edtech sector.

---

## Insights Deep Dive

### 1. Sales Performance

- **Total Sales and Profit**: Catalyst Academy achieved **$732K** in total sales in 2023, reflecting a **20.4% year-over-year increase**. Total profit rose to **$93K**, up by **13.8%**.
- **Quarterly Trends**: Q4 emerged as the strongest period, driven by exceptional performance in subcategories such as tablets, virtual labs, and projectors. Conversely, coding platforms and LMS products showed declining sales, indicating areas requiring strategic adjustments.
- **Weekly Profit Trends**: Weekly profits averaged **$2K**, with notable peaks during high-sales periods. Occasional weeks of negative profitability suggest opportunities to optimize pricing strategies, inventory management, or operational efficiencies.

### 2. Customer Insights

- **Customer Growth and Engagement**:
  - Total customers increased by **8.7%** to **689**, with sales per customer rising by **10.8%** to **$1,062**.
  - **Order Patterns**: **74%** of customers placed 1–3 orders, while a smaller, highly engaged group placed 4+ orders.
  - **High-Value Customers**: The top 4 customers contributed over **$43K** in combined sales, underscoring the importance of retention strategies to maximize their lifetime value.

### 3. Geographic Trends

- Geographic analysis showed no significant disparities in sales or customer distribution across regions. However, further segmentation by specific markets or demographics could yield actionable insights for future campaigns.

### 4. Subcategory Performance

- **Top-Performing Subcategories**:
  - Tablets and virtual labs exhibited strong growth and high profitability, representing key investment opportunities.
- **Underperforming Subcategories**:
  - Products like coding platforms and attendance trackers experienced negative growth, highlighting a need for targeted marketing, product improvements, or repositioning efforts.

---

## Opportunities for Growth

- **Enhance Subcategory Strategies**:
  - Capitalize on high-growth subcategories by increasing investment in tablets, virtual labs, and related products.
  - Address underperforming categories like coding platforms through market research and tailored campaigns.
- **Target Mid-Tier Customers**:
  - Design loyalty programs to encourage repeat purchases, especially from customers with moderate engagement.
  - Analyze order patterns to identify cross-sell or upsell opportunities.
- **Optimize Profitability**:
  - Investigate root causes of negative weekly profits to align inventory, operations, and pricing strategies effectively.
- **Leverage Customer Segmentation**:
  - Focus retention efforts on high-value customers to strengthen relationships and drive sustained profitability.
