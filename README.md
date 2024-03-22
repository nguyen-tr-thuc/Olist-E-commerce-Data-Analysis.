# Olist E-commerce Data Analysis

## Exploration, Insight generation and Visualization of E-commerce sales data
This repository contains a data analysis project that explores the sales data of the Olist platform and provides insights into revenue trends, order patterns, product categories, seller performance, customer behavior, and payment methods. The project is implemented in Python using Jupyter notebooks and various data science libraries.

# Olist Data Analysis
### 1. Exploratory Data Analysis
* Order
* Sale
* Product category
* Payment
* Rating
### 2. Customer Analysis
* RFM modelling
* K-Means clustering
## Customer Segmentation and RFM Modeling 
- Using RFM anaylsis and K-means Clustering, we created the below Clusters or segments of customers to further give targetted recommendation to them.

- We can Upsell high end products to Big Spenders and Cross Sell complimentary products to **Loyal** and **Best Customer (VVIP)**.

- Potential Loyalists: They are highly potential to enter our loyal customer segments, discounts for future purchases are very suitable for this audience.

- Lagging Customers: Let’s target them with their wishlist items, a limited time offer discount and/or a free delivery.

- Hibernating Almost Lost: They made some initial purchase but have not seen them since. Let’s spend some resource to build our brand awareness with them.

- Churned Customers: Poorest performers of our RFM model. They might have went with our competitors for now and will require a different activation strategy to win them back. We can see many things to improve our business through surveying this customer group.

## Recommendation Systems  

Recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy or anything else depending on industries).

Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. As a proof of the importance of recommender systems, we can mention that, a few years ago, Netflix organised a challenge (the "Netflix prize") where the goal was to produce a recommender system that performs better than its own algorithm with a prize of 1 million dollars to win.
We will be using below approach to Recommend products - 
 
Recommendation for Potential Loyalists and Other - 
ALS (Alternating Least Squares) is an implicit recommendation algorithm to make a recommendation of products and product categories to the users. ALS is an iterative optimization process where for every iteration it tries to arrive closer and closer to a factorized representation of the original data.

This dashboard summarizes the charts drawn in data analysis. Dashboard was shared at here <https://lookerstudio.google.com/u/0/reporting/dad93adf-5ad4-448f-9fdd-f75768732542/page/8LItD>
