#  The Sugar Wagon: Supply Chain & Operations Analytics Dashboard

- Live Dashboard: https://public.tableau.com/views/Book1_17518668743090/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link  

## Project Summary
- A comprehensive supply chain analytics project for The Sugar Wagon, a national sweets distributor, aimed at reducing logistics costs and improving operational performance. Built using Tableau and SQL, the project integrates sales, customer, product, and geospatial data to deliver executive-level insights.

## Objectives
- Model data across sales, products, factories, and geographies.
- Visualize shipping routes and delivery metrics using geospatial analytics.
- Identify supply chain inefficiencies and high-cost segments.
- Analyze customer behavior and drive retention improvement.

## Dataset Features Used
- Sales Orders: Order Date, Ship Date, Cost, Units, Profit
- Factories: Location (Lat, Long), Utilization
- Customers: Region, Retention, CLV, Order Frequency
- Products: Category, Unit Price/Cost, Margin %, Shipping Cost
- Geospatial ZIP Mapping: State/City, Distance, Density
- Derived Features: Shpping cost, customer distance, LTV, Cogs, Utilization rate, returning customers, order frequency, avgordervalue, delivery time, 

## Solution Steps Overview
- **SQL**: Data extraction, joins, and transformation
- **Tableau**: Dashboard design and interactive visualizations
- **Geospatial Analysis**: ZIP code mapping and distance metrics
- **Customer Analytics**: CLV, RFM, retention modeling
- **Operations Analytics**: Cost optimization, shipping cost trends, Utilization rates

## Dashboards Created
1. **Operations Dashboard**: Order fulfillment, delivery time, factory utilization, cost efficiency.
2. **Customers Dashboard**: Customer segmentation, LTV, retention rate, top-performing cities.
3. **Sales Dashboard**: Revenue trends, order value, sales vs. targets, performance by region.
4. **Product Dashboard**: SKU profitability, shipping cost per unit, inventory turnover,recency, units per order etc. 

## Key Performance Metrics 
- $117 Avg Shipping Cost | 1,243 mi Avg Distance | 34% Cost Efficiency | 34% COGS
- $139K Revenue | 38K Units | 5.3% Sales Target Achievement YTD
- 13% Retention | $28 LTV | 67% Product Margin
  
## Insights Overview
- **Factory Imbalance**: ‘Lot’s O’ Nuts’ fulfilled the majority of orders, while other factories were underutilized—prompting factory load balancing opportunities.
- **High Delivery Distance**: Avg. delivery span of **1,243 miles** contributed to increased costs and inconsistent delivery times (up to **13 days** in some states).
- **Shipping Cost Outliers**: Products like "Fudge Mallows" incurred avg. shipping costs of **$538/unit**, while efficient products like "Gobstopper" cost just **$17/unit**.
- **Low Retention Rate**: Only **13% of customers** were retained, with Loyal customers forming a small but high-value segment (7 orders per customer).
- **Sales Target Underperformance**: Despite $139K in sales and 27% YoY growth, the YTD sales target was only **5.3% achieved**, pointing to goal misalignment.
- **Inventory Turnover**: Just **5%**, suggesting stock overaccumulation or slow-moving SKUs impacting supply chain agility.

## Outcome & Recommendations
- Proposed factory load balancing and regional warehousing
- Identified costly products for route optimization
- Suggested targeted retention strategies by customer type and geography
- Optimized product focus to improve margins and inventory turnover

## Contact
For collaboration or inquiries, connect with me on [LinkedIn](https://www.linkedin.com/in/adithya-prahasith) or email: [adithyaprahasith@gmail.com](mailto:adithyaprahasith@gmail.com)
