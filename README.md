# retail_orders_analysis
# Retail Sales Performance Using Python and SQL
# Project Overview
Retail companies generate a large amount of transaction data every day, but raw data alone does not always make it easy to understand what is actually happening in the business. The purpose of this project was to analyze retail order data in order to uncover patterns in product performance, regional demand, and sales growth over time.
Through this analysis, I wanted to answer a few key questions that are important for any retail business:
- Which products are generating the most revenue?
- How does product performance vary across different regions?
- Are sales improving over time?
- Which product segments are growing the fastest?

By exploring these questions, the goal of the project was to turn raw sales data into insights that could help a business make better decisions about inventory, marketing, and product strategy.

**Business Context**

Imagine a retail company that sells thousands of products across different regions in the United States. Every day, orders are placed by customers from different cities and markets, creating a large dataset of transactions.
However, simply having the data is not enough. Business leaders still need clear answers to important questions such as:
- What products are actually driving revenue?
- Are certain regions performing better than others?
- Which product categories are growing and which are slowing down?
This project simulates the type of work a data analyst might perform in a retail organization, where the goal is to analyze historical sales data and uncover insights that can support better decision-making.

# Key Business Insights
## Top Revenue Generating Products

One of the first things I looked at was which products generate the highest total revenue. Identifying these products is important because they represent the company's strongest contributors to overall sales.
If a business knows which products consistently perform well, it can prioritize them in areas like marketing promotions, inventory planning, and supplier management.

By aggregating sales by product, the analysis identifies the top 10 products generating the highest revenue. These products represent the company’s core revenue drivers and may require special attention in areas such as:
- inventory management
- marketing promotion
- supply chain prioritization

<img width="188" height="209" alt="image" src="https://github.com/user-attachments/assets/135f27e0-28f5-4420-b672-ac322a1d7fe7" />


## Regional Differences in Product Performance

Another interesting insight came from comparing product performance across different regions. Not all products perform equally everywhere. Some products may be very popular in one region but less successful in another.
By identifying the best-selling products in each region, businesses can better understand regional preferences and tailor their strategies accordingly. This can help improve inventory distribution and create more targeted marketing campaigns.
<img width="266" height="401" alt="image" src="https://github.com/user-attachments/assets/f011a450-2bff-4265-b8dc-727ec86270fc" /> 
Sales patterns often vary across different regions. Using SQL window functions, this project identifies the top 5 best-selling products in each region. This insight allows the business to:
- Understand regional customer preferences
- Adjust regional inventory distribution
- Tailor marketing strategies to local demand

For example, a product performing well in the West region may not perform equally well in the South, highlighting opportunities for region-specific strategie
Sales Trends Over Time

# Year-over-Year Monthly Sales Trends
Retail businesses often experience seasonal patterns in sales. Some months perform much better than others depending on consumer behavior, holidays, or promotional cycles. By comparing sales trends over time, it becomes easier to see whether the business is growing and which periods tend to generate the highest revenue. This type of insight can help companies prepare for high-demand periods and plan marketing or promotions more effectively.
<img width="250" height="245" alt="image" src="https://github.com/user-attachments/assets/3cdaa0d5-0371-475d-b5b4-364ca04dc14e" />
By comparing monthly sales between 2022 and 2023, the analysis reveals how sales performance changes over time.
This helps answer questions such as:
- Are sales increasing year over year?
- Which months experience peak demand?
- Are there periods of declining revenue?
Understanding these trends helps companies plan:
- Promotional campaigns
- Inventory levels
- Seasonal marketing strategies
- 
## Category Performance
Each product category has its own sales cycles. The analysis identifies the highest revenue month for each product category. For example:
- Technology products may peak during back-to-school seasons.
- Office supplies may increase during corporate purchasing cycles.
These insights help businesses better align their sales strategies with customer demand cycles.
<img width="293" height="76" alt="image" src="https://github.com/user-attachments/assets/270fc5aa-b12c-4df2-b583-6219deaf3d7f" />

## Sub-Category Growth Analysis
One of the most valuable insights in this project is identifying which sub-categories experienced the highest growth between 2022 and 2023. By calculating the percentage growth in sales, the analysis reveals which product segments are expanding and which ones are declining.
For instance, some categories such as Machines and Supplies showed strong growth, while others experienced declining performance.
This information is extremely valuable for strategic decisions such as:
- Product expansion
- Marketing investments
- Pricing strategies
- Inventory planning
<img width="369" height="340" alt="image" src="https://github.com/user-attachments/assets/3575db82-f464-49a1-9ac7-0a98fcba9787" />


# Who Can Benefit From This Analysis

The insights from this analysis can be useful for different teams within a retail organization.
Executives and managers can use the results to understand overall business performance and identify areas with strong growth potential.
Sales and marketing teams can focus their efforts on promoting the products that generate the most revenue or show strong growth trends.
Supply chain and inventory teams can use the insights to better plan inventory levels and avoid shortages for high-demand products.
Overall, this type of analysis helps teams make more informed decisions based on actual sales data rather than assumptions.

# Conclusion

This project highlights how analyzing sales data can provide valuable insights into product performance, customer demand, and business growth. By looking at product revenue, regional performance, and growth trends across categories, it becomes easier to understand where the business is performing well and where there may be opportunities for improvement.
In many ways, the real value of data is not just collecting it, but learning how to use it to guide smarter decisions. This project is a small example of how data analysis can help turn everyday transaction data into meaningful insights for a business.
