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
Using RFM analysis combined with K-means clustering, we've identified distinct customer segments to facilitate targeted recommendations:

* Big Spenders: This group represents customers with significant spending habits. We propose upselling high-end products to them, as they're likely to appreciate premium offerings.

* Loyal and Best Customers (VVIP): These are our most loyal customers who frequently engage with our brand. For them, we suggest cross-selling complementary products to enhance their overall experience.

* Potential Loyalists: This segment shows promise in transitioning to loyal customers. To encourage their loyalty, we recommend offering discounts on future purchases as an incentive.

* Lagging Customers: These customers have shown interest but haven't made recent purchases. To re-engage them, we propose targeting them with their wishlist items and providing limited-time offers or free delivery.

* Hibernating Almost Lost: This group consists of customers who made initial purchases but haven't returned. Our strategy involves investing resources in building brand awareness to reignite their interest.

* Churned Customers: This segment represents customers who have stopped engaging with our brand. To win them back, we need a different approach focused on understanding their reasons for leaving and implementing targeted strategies to reacquire their business.
![image](https://github.com/ThucNguyen22/Olist-E-commerce-Data-Analysis./assets/151516549/e7236274-bd25-4fc7-92a6-67a53cd0cbb9)
![image](https://github.com/ThucNguyen22/Olist-E-commerce-Data-Analysis./assets/151516549/7fe0147a-21e6-48e3-8334-eff703d3749a)

### 3: Recommendation Systems  

Recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy or anything else depending on industries).

Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. As a proof of the importance of recommender systems, we can mention that, a few years ago, Netflix organised a challenge (the "Netflix prize") where the goal was to produce a recommender system that performs better than its own algorithm with a prize of 1 million dollars to win.
We will be using below approach to Recommend products - 
 
Recommendation for Potential Loyalists and Other - 
ALS (Alternating Least Squares) is an implicit recommendation algorithm to make a recommendation of products and product categories to the users. ALS is an iterative optimization process where for every iteration it tries to arrive closer and closer to a factorized representation of the original data.

This dashboard summarizes the charts drawn in data analysis. Dashboard was shared at here <https://lookerstudio.google.com/u/0/reporting/dad93adf-5ad4-448f-9fdd-f75768732542/page/8LItD>
