# Catalyst Academy Overview

Catalyst Academy, a (fictional) American edtech innovator founded in 2000, is dedicated to transforming education through cutting-edge technology and evidence-based pedagogy. Catalyst Academy provides personalized learning experiences that empower educators and learners to foster lifelong growth in a dynamic global landscape.

## Objective

This project aims to analyze 2023 sales and customer performance data to identify growth opportunities, optimize operations, and enhance customer engagement. Key areas of focus include:

- **Sales Performance**: Evaluating total sales, profit, and year-over-year growth.
- **Customer Insights**: Analyzing customer behavior, retention, and engagement metrics.

## Data Sources

- **Interactive Tableau Dashboard**: [Download here](https://public.tableau.com/app/profile/joshua.kendagor/viz/CatalystAcademySalesDashboard/CustomerDashboard)
- **SQL Queries**: The SQL queries utilized to clean, organize, and prepare data for analysis and visualization can be found [here](https://github.com/tirop/Catalyst_Academy/blob/main/SQL%20Cleaning.pdf).
- **Original Dataset**: Includes [customers](https://github.com/tirop/Catalyst_Academy/blob/main/ca_customers.csv), [locations](https://github.com/tirop/Catalyst_Academy/blob/main/ca_locations.csv), [orders](https://github.com/tirop/Catalyst_Academy/blob/main/ca_orders.csv), and [products](https://github.com/tirop/Catalyst_Academy/blob/main/ca_products.csv) 

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

The dataset was visualized in Tableau ([View here]([#](https://public.tableau.com/app/profile/joshua.kendagor/viz/CatalystAcademySalesDashboard/CustomerDashboard))), revealing trends in churn and retention by tenure, geography, and gender.
![Screenshot 2025-01-14 130451](https://github.com/user-attachments/assets/0f495a04-81a9-466f-853a-ab2d4f21aafc)
![Screenshot 2025-01-14 130516](https://github.com/user-attachments/assets/9e15b37d-8824-4dd0-8238-f2171101a9af)

---

# Executive Summary

Catalyst Academy grew sales to $732K in 2023, up 20.4% YoY, with profit increasing by 13.8%.
Sales were driven by strong growth in tablets, virtual labs, and timers. LMS and coding platforms, on the other hand, declined. This indicates product misalignment.
74% of customers placed only 1–3 orders, showing an opportunity to boost retention through targeted loyalty strategies.
I recommended increased investment in high-growth subcategories and retention campaigns for mid-tier customers to drive repeat purchases and long-term profitability.

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
  - Tablets, timers, and virtual labs showed strong growth and high profitability. These products represent key investment opportunities.
- **Underperforming Subcategories**:
  - Products like coding platforms and learning management systems experienced negative growth. This highlights a need for targeted marketing, product improvements, or repositioning efforts.

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
