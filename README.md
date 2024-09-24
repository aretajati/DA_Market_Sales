# DA_MarketSales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into the sales performance of a market chain company over the past year  in Europe. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.

![Screenshot 2024-09-24 140652](https://github.com/user-attachments/assets/9ac33acf-dbff-4463-a6fd-ac7ea401ba68)

### Business Requirement

To conduct a comprehensive analysis of WeCart's sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualizations in PowerBI.

### KPI's Requirements
- Total Sales: The overall revenue generated from all items sold.
- Average Sales: The average revenue per sale.
- Number of Items: The total count of different items sold.
- Average Rating: The average customer rating for items sold.


### Data Sources

Sales Data: The primary dataset used for this analysis is the "WeCart_grocery_data.csv" file, containing detailed information about each sale made by the company.

### Tools

- Excel - Data Cleaning
  - [Download here](https://microsoft.com)
- SQL Server - Data Analysis
- PowerBI - DAX Calculation and Creating reports

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

Total Sales:
- Are there any outliers or anomalies in the total sales?
- Do sales vary significantly across different time periods or categories?
- How is total sales influenced by the number of items sold or their ratings?

Average Sales:
- Are there consistent average sales values across categories or time periods?
- Are certain product categories associated with higher average sales?
- Do any sales outliers (extremely high or low) skew the average?

Number of Items:
- What items or categories contribute the most to overall sales?
- Are certain items consistently sold in higher volumes?
- Are there seasonal trends in the number of items sold?

Average Rating:
- Are there patterns between customer ratings and product sales?
- Are items with higher ratings consistently generating more sales or revenue?
- Are there any significant outliers in the rating distribution (e.g., very low ratings)?
- Do certain categories/products consistently receive higher or lower ratings?
	
### Data Analysis

Include some interesting code/features worked with SQL, DAX expressions, and PowerBI dashboard.

### Results/Findings

- The total sales reached $1.20M, with an average sales value of $141 across 8523 items. This indicates a robust sales performance across various product categories and outlet types. The top-selling items include fruits, snack foods, and household products, with **fruits and snacks each contributing $0.18M.

- The outlet size plays a significant role in sales performance. Large outlets (high-tier) lead in total sales, generating over $507.90K, while medium and small outlets contribute to $248.99K and $444.79K respectively. The higher-performing outlets are clustered in Tier 3 locations, which are responsible for $472.1K in total sales.

- Regular-fat products outperform low-fat alternatives, contributing to **$776.32K** in total sales compared to low-fat products at $425.36K. The data suggests that customer preference leans toward regular-fat items.

- Key contributors to sales include household products, dairy, and canned foods, all showing consistently high figures across various metrics such as total sales, average sales, and the number of items.

- Outlets located in Tier 3 areas showed higher sales figures compared to Tier 1 and Tier 2 locations. This suggests that Tier 3 areas, likely representing more populated or urban areas, perform better in terms of customer engagement.

- The overall average rating across outlets is 3.9, indicating a satisfactory level of customer satisfaction. However, there is room for improvement to elevate this to a higher customer approval rate.

- Supermarket Type 1 outlets performed the best in terms of both sales and visibility, with a total sales figure of $787.55K and 339 visible items. The grocery store segment, while having lower sales of $151.94K, still maintains a reasonable performance in terms of average sales and customer ratings.


### Recommendations

1. Expand the Portfolio in High-Performing Categories: Focus on increasing the variety and availability of high-demand categories such as fruits, snacks, and household products, which consistently show strong sales. Introducing more product options within these categories could further boost sales and customer satisfaction.

2. Target Regular Fat Products for Promotion: Regular-fat products lead in sales performance, which suggests that promotional efforts could focus on these items. Marketing campaigns centered around popular regular-fat products may help increase average sales per customer.

3. Improve Customer Experience and Ratings: While the average rating of 3.9 is acceptable, implementing strategies to improve customer service, product quality, and in-store experience could raise this to a higher level. Incentivizing customer feedback and addressing common issues may lead to better customer retention.

4. Optimize Tier 1 and 2 Locations: Tier 1 and Tier 2 locations are underperforming in comparison to Tier 3. Consider enhancing the product selection, store layout, or promotional strategies in these areas to close the performance gap. Additionally, analyzing why Tier 3 locations perform better could yield insights into improving customer engagement in lower-tier areas.

5. Leverage Data-Driven Promotions: The data offers clear insights into which products and outlets perform the best. Leveraging this data to create **personalized promotions (e.g., offering discounts or bundle deals on popular items in high-performing outlet sizes or locations) can help drive sales and improve customer satisfaction.

6. Boost Visibility in Underperforming Categories: Some categories, like breads, seafood, and soft drinks, show lower performance. Efforts could be made to improve their visibility and customer engagement, either through shelf placement, in-store displays, or promotional efforts.

By focusing on these strategic areas, **WeCart** can continue to optimize performance, improve customer satisfaction, and expand its market share.


### References

1. SQL for Data Analysis by Cathy Tanimura.
2. [Stack Overflow](https://stack.com)

