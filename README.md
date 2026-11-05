# ShopFast Online Sales Analysis


## 1. Project Overview

This project focuses on analysing ShopFast's online sales data to evaluate business performance, identify profitability trends, and understand sales performance across different regions, product categories, and customer segments.

The analysis uses Python (Pandas) for data exploration and analysis, and Tableau for data visualisation and dashboard development.

The ultimate goal is to provide meaningful insights that can help management make informed, data-driven business decisions.

## 2. Project Objectives

The main objectives of this project are to:

- Evaluate overall sales and profitability.
- Compare total profit across different geographical regions.
- Analyse monthly sales and profit trends.
- Identify customer segments contributing the highest average profit.
- Evaluate product category performance.
- Develop interactive Tableau dashboards to communicate findings.
- Provide actionable recommendations to improve business performance.

## 3. Dataset Description

The dataset contains 5,000 sales records with the following variables:

| Column | Description |
|---|---|
| order_id | Unique order identification number |
| order_date | Date when an order was placed |
| region | Geographical sales region |
| category | Product category |
| customer_segment | Classification of customers |
| sales | Revenue generated from each order |
| profit | Profit or loss generated from each order |
| quantity | Number of products purchased |

## 4. Tools and Technologies

The following tools were used:

- **Python:** Data cleaning, manipulation and analysis.
- **Pandas:** Data exploration and statistical analysis.
- **Matplotlib:** Data visualisation.
- **Tableau:** Interactive dashboards and business reporting.
- **Jupyter Notebook:** Data analysis environment.
- **GitHub:** Project documentation and version control.

## 5. Data Cleaning and Preparation

The dataset was examined and prepared before conducting the analysis.

Key preparation activities included:

- Inspecting the dataset structure and data types.
- Checking for missing values.
- Identifying and handling missing regional information.
- Converting order dates into a consistent datetime format.
- Examining numerical variables for consistency.
- Creating a profit margin variable for profitability analysis.
- Checking for potential data quality issues.

## 6. Exploratory Data Analysis

The analysis focused on the following areas:

### A. Regional Profitability

Compared total profit across the five regional groupings, including records classified as Unknown.

### B. Monthly Profit Trends

Examined monthly profit performance to identify fluctuations and changes in profitability over time.

### C. Customer Segment Analysis

Evaluated average profit per order across customer segments within product categories.

### D. Product Category Performance

Examined the contribution of different product categories to overall business profitability.

### E. Sales and Profit Relationships

Investigated relationships between sales, profit and quantity to understand the factors associated with business performance.

## 7. Key Findings

### Regional Profit Performance

The North region recorded the highest total profit of approximately 59,655.12, followed by South at 55,838.21.

The East region recorded approximately 54,603.48, while West recorded approximately 51,062.19.

Records classified as Unknown contributed approximately 564.11 in total profit.

### Monthly Profitability

The monthly analysis indicated that January started with a relatively high profit margin, followed by a significant decline in February. Profitability subsequently improved, although it did not return to January's level during the period examined.

### Profit Margin by Product Category

The analysis of median profit margins showed differences across product categories:

- Office Supplies: 23.73%
- Furniture: 18.54%
- Electronics: 13.88%

Office Supplies recorded the highest median profit margin among the three categories.

## 8. Tableau Dashboard Development

Interactive Tableau dashboards were developed to present the findings in a clear and accessible format.

The planned dashboard components include:

- Regional sales vs profit-Presented in Bar grapgh
- Sales vs profit by product-presented in Horizontal Bar graph
- Total sales by region-line gragh
- Profit by product category-Pie Chart
- Total sales KPI

These visualisations enable management to monitor performance and identify areas requiring attention.

## 9. Recommendations for ShopFast online sales

Recommendation 1: Regional Profitability Performance

From the analysis, the North region emerged as the best-performing region, recording the highest total profit of KSh 59,655.12, followed by South at KSh 55,838.21, East at KSh 54,603.48 and West at KSh 51,062.19. Although North ranked first among the four regions, the differences in total profit were relatively small, suggesting that regional profitability was fairly comparable.

North's performance nevertheless presents an opportunity for further comparative analysis to establish the factors contributing to its relatively higher profitability. In particular, examining differences in product sales mix, customer purchasing patterns, product combinations and sales volumes across regions could reveal whether North's performance is driven by particular products or customer segments. Additionally, comparing sales performance across regions could help establish whether differences in sales-team productivity contribute to the observed profitability gap.

These comparisons would provide a clearer understanding of the factors associated with North's stronger performance and establish whether similar patterns exist in the other regions.

Recommendation 2: customer segment with the highest average profit

Analysis of Profit Performance by Customer Segment within Electronics

The analysis indicates that the Small Business customer segment recorded the highest average profit per order within the Electronics category, at 140.54, followed by Consumer at 64.25, Home Office at 60.91, and Corporate at 52.30.

Interestingly, despite recording the highest average profit per order, the Small Business segment had only 3 orders. This is considerably lower than the other customer segments, which recorded substantially higher order volumes. Corporate had the highest number of orders at 578, followed by Consumer with 549 and Home Office with 548.

Despite having the highest order volume, Corporate recorded the lowest average profit per order and a total profit of 30,226.61. Consumer, on the other hand, generated the highest total profit of 35,272.68, followed by Home Office at 33,381.03 and Corporate at 30,226.61.

These findings suggest that a higher order volume does not necessarily translate into higher average profit per order or higher total profit. The profitability of each customer segment may also depend on factors such as order value, product pricing, discounts, and operating costs.

Although Small Business recorded the highest average profit per order, its total contribution to profit was only 421.62 because of its very low order volume. This demonstrates the importance of considering both average profit per order and total profit when evaluating customer segment performance.

Recommendations

Investigate the Small Business segment on why Small Business orders generate significantly higher average profits than other customer segments. Particular attention should be given to pricing, order values, discount levels, and product combinations. However, since the finding is based on only three orders, more data should be collected before making major business decisions.

Strengthening the Consumer segment should remain a key focus because this segment generated the highest total profit of 35,272.68. The busness should explore strategies to retain these customers, increase repeat purchases, and identify opportunities to improve their average profit per order and also help other segments learn from this if the aim is to maximize total profit.

Review Corporate segment profitability although Corporate recorded the highest number of orders (578), it generated the lowest average profit per order (52.30) among the three major segments. This should be investigated whether to find out whether high discounts, lower selling prices, or other costs are reducing profitability. Strategies should focus on improving profit margins without necessarily sacrificing order volume.

Balancing of order volumes versus profitability should be done avoid relying solely on order volume when assessing business performance. Instead, decisions should consider average profit per order alongside total profit to identify customer segments that offer both sustainable sales volumes and stronger profit contributions.

Recommendation 3: Profit trends over 3 months

The analysis indicates that January recorded the highest total profit of 76,265.84, followed by March at 74,258.58, while February recorded the lowest total profit of 71,198.69. This shows a decline in profitability from January to February, followed by a recovery in March. However, March's profit did not fully return to January's level. Overall, the three months reflect relatively consistent profit performance, although the figures suggest some fluctuations in monthly profitability.

I recommend that ShopFast management investigate the factors that contributed to the sharp decline in profitability in February. Additionally, management should identify the strategies or operational measures that contributed to the recovery in March and assess whether they can be sustained or replicated in subsequent months to improve overall profitability.

The ShopFast Online Sales Analysis project demonstrates how data analytics can be used to transform raw sales data into meaningful business insights.

By combining Python-based analysis with Tableau visualisation, the project provides a foundation for monitoring sales performance, understanding profitability and supporting informed management decisions.

The findings can help ShopFast identify opportunities for improvement, strengthen regional performance and develop more effective business strategies.

---

**Project:** ShopFast Online Sales Analysis  
**Domain:** E-commerce / Business Intelligence  
**Author:** Justin Owino  
**Tools:** Python, Pandas, Matplotlib, Tableau and GitHub
