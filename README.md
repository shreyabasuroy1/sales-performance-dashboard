# Global Sales Performance Dashboard

An interactive Power BI dashboard analyzing global sales performance across products, regions, and customers — built to identify revenue trends, top-performing markets, and order fulfillment patterns.

## Business Problem

A sales organization operating across 19 countries needed a consolidated view of performance to answer key business questions:

- Which product lines drive the most revenue?
- What are the seasonal trends in sales?
- Which markets are the strongest, and where is there room to grow?
- How efficient is order fulfillment, and where are the bottlenecks?
- Who are the highest-value customers?

## Dataset

- **Source:** [Kaggle – Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
- **Records:** 2,823 transactions
- **Time period:** 2003–2005
- **Fields:** Order details, product line, sales amount, customer information, geography, deal size, and order status

## Tools Used

- **Power BI Service** (Microsoft Fabric) for data modeling and visualization
- **Power Query / Dataflow Gen2** for data transformation
- **DAX** for measures and calculated fields

## Dashboard Overview

The dashboard consists of six core visuals:

| Visual | Purpose |
|---|---|
| Total Revenue (KPI) | Headline revenue figure across all transactions |
| Monthly Sales Trend | Identifies seasonality in sales performance |
| Sales by Product Line | Compares revenue contribution across product categories |
| Sales by Country | Highlights top-performing and underperforming markets |
| Order Status Breakdown | Visualizes order fulfillment efficiency |
| Top Customers by Revenue | Surfaces highest-value accounts |

## Key Insights

1. **Total revenue across the dataset was $10.03M**, generated from 2,823 orders.
2. **November is the strongest sales month**, with revenue more than double the average month — indicating a clear seasonal peak, likely tied to holiday purchasing cycles.
3. **Classic Cars is the leading product line**, generating close to $4M — nearly double the second-highest category (Vintage Cars).
4. **The USA is the largest market by a significant margin**, followed by Spain and France, suggesting an opportunity to deepen investment in underrepresented markets like Asia-Pacific.
5. **92.6% of orders are successfully shipped**, with cancellations and disputes making up a small fraction — indicating a generally efficient fulfillment process, though disputed/cancelled orders are worth monitoring.

## Recommendations

- Plan inventory and marketing campaigns around the November sales peak to maximize seasonal revenue.
- Investigate why Classic Cars significantly outperforms other product lines — consider expanding this category or applying its success factors elsewhere.
- Evaluate growth opportunities in underrepresented regions, particularly Asia-Pacific markets.
- Review the root causes behind cancelled and disputed orders to further improve fulfillment rates.

## Skills Demonstrated

- Data cleaning and transformation (Power Query)
- Data modeling
- DAX measures
- Dashboard design and visual storytelling
- Business insight generation from raw transactional data

## Author

**Shreya Basu Roy**
MSc Business Analytics & Finance, University of Southampton
[LinkedIn](#) · [GitHub](#)
