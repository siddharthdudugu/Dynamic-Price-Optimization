# Dynamic-Price-Optimization
Price Optimization using Dynamic Pricing Model, Price Elasticity Analysis &amp; Sales Analysis by Price Bracket

Price optimization is a strategic approach that uses data analysis and modelling to determine the optimal pricing of products or services. This process involves considering various factors, including market demand, competition, costs, and customer behaviour, to set prices that maximize profitability and market share. So, if you want to learn how to optimize prices for a product or service, this article is for you. In this article, I’ll take you through the task of Price Optimization using Python.

## Price Optimization: Overview
Price optimization is a strategic approach that uses data collection on sales, costs, competition, and market trends to predict demand changes and analyze price elasticity, which enables businesses to set optimal prices. It involves competitive analysis to monitor market positioning, customer segmentation to identify varying willingness to pay, and the use of mathematical optimization algorithms to determine the best price points.


## Problem Statement
The goal is to create a dynamic pricing model that adjusts item prices based on various factors such as competitor pricing, demand elasticity, and market trends. The primary objectives include:

- Analyzing the current pricing strategy and its impact on sales and revenue.
- Comparing our pricing strategy with competitors to identify gaps and opportunities.
- Developing a dynamic pricing model that responds to real-time market factors.
- Implementing and simulating the dynamic pricing model to evaluate its performance against the existing pricing strategy.


## Dataset
The dataset used for this project contains pricing information for various items sold at a retail store, along with their corresponding prices at competing stores. The dataset includes the following columns:

- Fiscal_Week_Id: The fiscal week identifier.
- Store_Id: The store identifier.
- Item_Id: The item identifier.
- Price: The price of the item at our store.
- Item_Quantity: The quantity of the item sold.
- Sales_Amount_No_Discount: Sales amount without discount.
- Sales_Amount: Sales amount after discounts.
- Competition_Price: The price of the item at a competing store.

The data spans multiple fiscal weeks and includes various items across different categories, providing a comprehensive view of pricing strategies and sales performance.


## Methodology and Observations
### 1. Price Distribution Comparison
#### Observation:

Competition's Price Distribution: Higher prices with peaks in the 100-150 and 200-250 price ranges suggest a focus on higher-priced items to maximize profit margins.
Our Store's Price Distribution: More evenly distributed prices across the 50-300 range, with peaks around 100-150, indicating a more diverse pricing strategy targeting a wider customer base.
#### Insight:

The competition targets higher price brackets with a focused strategy, likely contributing to superior sales performance. Our store’s dispersed pricing strategy may lead to inconsistent sales.
### 2. Relationship Between Price and Sales
#### Observation:

Our Store: Wide dispersion of sales amounts across various price points without a clear trend, indicating a potentially suboptimal pricing strategy.
Competition: Dense clustering of sales amounts around higher values, suggesting a well-tuned pricing strategy that maintains higher sales volumes more consistently.
#### Insight:

The competition’s more effective pricing strategy consistently drives higher sales amounts, indicating they have identified optimal price points that resonate better with their customer base.
### 3. Price Changes Over Time
#### Observation:

Competition: Maintains higher and stable average prices above 170, indicating a confident and stable pricing strategy.
Our Store: Fluctuating prices suggest an unstable strategy that may cause consumer uncertainty and impact sales performance.
#### Insight:

The competition's stable pricing could be contributing to higher and more consistent sales, whereas our store’s price fluctuations may lead to less predictable sales outcomes.
### 4. Price Elasticity Analysis
#### Observation:

- Elasticity Over Time: Significant variability in elasticity, ranging from highly negative to highly positive, reflects an inconsistent market response to price changes.
- High Positive Elasticity: Demand increased with price hikes.
- High Negative Elasticity: Demand dropped with price hikes.
#### Insight:

The broad spread of elasticity values suggests other factors like promotions, seasonality, or market conditions might influence demand, indicating that our pricing strategy may not align well with market dynamics.
### 5. Sales Analysis by Price Bracket
#### Observation:

- 0-50 Bracket: Competition has significantly higher sales, showing better pricing for budget-conscious customers.
- 51-100 Bracket: Competition outperforms our store by a wide margin.
- 101-150 Bracket: Competition’s sales are much higher, showing strong market dominance.
- 151-200 Bracket: Competition consistently outperforms our store.
- 201-250 Bracket: Competition’s sales are nearly double those of our store.
- 251-300 Bracket: Competition still leads, but the gap is smaller.
- 301-350 Bracket: Competition has higher sales, though sales amount is lower compared to other brackets.
#### Insight:

The competition consistently outperforms our store across all price brackets, particularly in lower and mid-range categories, suggesting a more effective pricing strategy in capturing market share.
### 6. Dynamic Pricing Model Simulation
#### Observation:

- Medium Segment: Inelastic demand with an average elasticity of -0.192951, indicating small price changes won’t significantly affect demand, allowing for slight price increases to maximize revenue.
- High Segment: Elastic demand with an average elasticity of 0.509307, indicating sensitivity to price changes, requiring careful optimization to maximize revenue without losing sales.
## Simulation Results:

The dynamic pricing strategy, involving a 5% price increase for the Medium segment and a 10% decrease for the High segment, led to a significantly higher total sales amount compared to the existing pricing strategy.
#### Insight:

The dynamic pricing model proved more effective in maximizing revenue by aligning prices with customer demand elasticity, highlighting the potential benefits of a more nuanced pricing approach.
## Conclusion
This project demonstrates how data-driven strategies, such as price optimization and dynamic pricing models, can enhance revenue and market competitiveness. By leveraging market data, customer segmentation, and price elasticity, businesses can achieve more effective pricing strategies that adapt to changing market conditions.
