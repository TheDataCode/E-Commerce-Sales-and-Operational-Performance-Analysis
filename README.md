### Sales and Operational Performance Analysis
This analysis focuses on a U.S.-based e-commerce business operating across four regions and 268 cities in 2014. Leveraging transactional data, the project explores key drivers of sales and profitability by examining customer behaviour, product performance, demographics, and operational efficiency. The objective is to generate insights that enhance profitability, improve customer satisfaction, and optimise logistics across the business.

[View detailed analysis here](https://github.com/TheDataCode/E-Commerce-Sales-and-Operational-Performance-Analysis/blob/main/Sales%20analysis.ipynb)



### Table of Contents

- [Executive Summary](#executive-summary)  
- [Insights](#insights-deep-dive)
  - [Sales Trend and Profitability](#sales-trend-and-profitability)
  - [Customer Purchase Behaviour](#customer-purchase-behaviour)
  - [Product Metrics](#product-metrics)
  - [Market Segmentation](#market-segmentation)
  - [Fulfilment Efficiency](#fulfilment-efficiency)
- [Recommendations](#recommendations)


### Executive Summary
##### Monthly Sales Trend
The monthly sales trend for 2014 demonstrated significant variability, with pronounced peaks in months like March, September, and November, and noticeable troughs in other months. This pattern suggests the presence of seasonal demand cycles, promotional influences, or external market factors affecting customer purchasing behaviour. The peak months accounted for 45% of the total annual sales.
Sales exhibited a consistent upward trajectory across all four quarters, indicating sustained growth momentum throughout the year.

##### Product Segment Performance
The Consumer segment accounted for the highest total revenue, contributing 55% of overall sales. However, this heavy reliance on a single segment presents a potential risk, particularly if market dynamics shift or competitive pressures increase.
However, the Home Office segment recorded the highest Average Order Value. This indicates potential for high-margin premium offerings.

##### Impact of Discount on Profitability
The discounting strategy significantly undermined profitability, especially within the 21–50% discount range, where increased sales volumes failed to yield corresponding profits. This trend is particularly pronounced in the Consumer segment, which received the most substantial discounts — over 70% of sales in this segment involved discounts exceeding 50%, yet it generated the lowest profit margins. Within this segment, the Furniture and Office Supplies categories were notably unprofitable, with profit margins as low as 1% and 9%, respectively.

##### Market Segmentation and Opportunity
Cities in the Southern and Central regions appear less frequently in the top rankings, which shows potential for market development.
Cities such as Springfield and Richmond, despite ranking among the top 15 in customer density, contributed minimally to overall sales and profit. This discrepancy suggests a potential gap in brand affinity.

##### Shipping Preferences and Operational Risk
Across all regions and product categories, the majority of shipping modes consistently met standard delivery timelines. Same-day delivery performed reliably with minimal delays, as expected. However, occasional delays were observed in the West region, particularly within the Technology category.                                                                    
Standard Shipping accounted for 63% of total sales, and the highest customer preference for cost-effective delivery options. While this indicates high adoption of the Standard Class, it also suggests a potential operational risk, as overreliance on a single shipping mode may increase vulnerability to service disruptions or delays.


### Insights Deep-Dive
#### Sales Trend and Profitability
- Sales peaked in March, September, and November, with September showing the highest spike.
- Quarter-over-quarter sales growth was steady and progressive, highlighting a positive business trend.
-  Discounts (21–50%) drove the highest average sales, but consistently resulted in negative profit margins.  
- Deep discounts (51–100%) generated lower sales volumes and also yielded negative profits, indicating diminishing returns.
- No discount (0%) tiers contributed modest sales, yet delivered the highest profit margins, suggesting healthier unit economics.
- Deep discounts were ineffective at boosting sales and further intensified the loss.
- The most profitable transactions occurred without any discount, highlighting the potential of full-price sales when value is communicated.
![profitability](https://github.com/user-attachments/assets/e9bcb236-6a69-4eab-b484-f3362c6bc7c4)


#### Customer Purchase Behaviour
- The Consumer segment was the primary revenue driver, reflecting better market penetration and customer engagement, largely driven by consistent discounting across all tiers
- The Home Office segment recorded the highest Average Order Value, indicating that while it had fewer transactions, each order was of relatively higher value on average.
![segment_distribution](https://github.com/user-attachments/assets/363aa617-f9f8-4ac2-baaf-e18df860719a)


#### Product Metrics
- The Home Office segment dominated in profit margins across all categories, especially in Office Supplies and Technology, which contributed 20% each.
- The Corporate segment achieved profit margins of 18% in the Technology category and 17% in Office Supplies.
- The Consumer segment had the lowest profit margin share, especially in Furniture (1%) and Office Supplies (9%) categories. Consumer segments with poor profit margins reflect an over-reliance on  discounts.
- Office Supplies were distributed relatively evenly across discount thresholds ranging from 20% to 80%, indicating broad promotional coverage. In contrast, most Furniture products received average discounts of 50% or less, suggesting a more conservative discounting approach within that category.
![profit_margin](https://github.com/user-attachments/assets/255ca42e-3230-43dd-84eb-e8ba9a2c8bc6)


#### Market segmentation
 _City-Level Performance Across Order Count, Profit, Sales_
- Cities in the Southern and Central regions appeared less frequently in the top rankings.
- New York City dominated across all metrics. The highest in sales, profit, and order count, making it the most valuable market overall.
- San Francisco and Los Angeles consistently ranked in the top 3 for sales and order volume, but San Francisco outperformed in profit.
- Seattle demonstrated strong profitability despite a lower order volume, suggesting the presence of high-value transactions.
![sales_profit_order](https://github.com/user-attachments/assets/70e93023-fbe9-4234-a985-84d43f3c09e6)


#### Fulfilment Efficiency
- All shipping modes across regions and categories met the standard delivery timeline. Same-day delivery performed as expected with no delays, though slight disruptions were noted in the West region for the Technology category.
- Standard Shipping accounted for 63% of total sales and showed a high volume of shipments, indicating a strong customer preference for cost-effective delivery options.
- Low adoption of Same Day shipping	suggests limited availability or pricing barriers.
  ![ADT_SM_CAT_REG](https://github.com/user-attachments/assets/4754bbb2-51ec-4af2-9f94-fb8f577330bc)

  
### Recommendations
- Inventory Planning: High-demand months like March,September and November may require increased stock levels and logistics readiness.
- Explore cross-segment opportunities: identify overlaps between Consumer and Corporate/Home Office needs to create hybrid offerings.
- Promote value over price: Shift the focus toward product quality, exclusivity, and service differentiation to reduce dependency on discounting. Where discounts are necessary, consider testing lower thresholds (5–15%) to strike a more sustainable balance between driving sales and preserving profit margins.
- Introduce limited-time offers or bundle deals to stimulate demand without compromising profitability.
- Delivery delays could benefit from warehouse proximity in the Western region, especially for products in the Technology category.
