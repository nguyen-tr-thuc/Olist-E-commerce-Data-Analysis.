## Data source
Brazilian E-Commerce Public Dataset by Olist

https://www.kaggle.com/olistbr/brazilian-ecommerce

## Introduction
Olist is a Brazilian startup that operates in the e-commerce segment , mainly through the marketplace. It is well spread within the country. This project is a detailed analysis on the comprehensive Olist data. The original Olist dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. The schema of the dataset is as below:-


* olist_order_customers_dataset - This dataset has information about the customer and its location. Use it to identify unique customers in the orders dataset and to find the orders delivery location.
* olist_geolocation_dataset - This dataset has information Brazilian zip codes and its lat/lng coordinates.
* olist_order_items_dataset - This dataset includes data about the items purchased within each order.
* olist_order_payments_dataset - This dataset includes data about the orders payment options.
* olist_order_reviews_dataset - This dataset includes data about the reviews made by the customers.
* olist_orders_dataset - This is the core dataset. Every necessary information is mapped to each order in this.
* olist_products_dataset - This dataset includes data about the products sold by Olist.
* olist_sellers_dataset - This dataset includes data about the sellers that fulfilled orders made at Olist.



## Basic Analysis
 - Focus on  `orders`, `customers`, `payments`, `products` and `reviews` datasets.  
    * Analysis by Purchase Period
    * Analysis by Customer State
    * Analysis by Payment Type
    * Analysis by Product Categories
    * Analysis by Review Score
## Answer a series of business questions
1. What is revenue over year by Olist, how it changed over time?
2. Total orders on E-commerce by status
3. Is there any growing trend on brazilian e-commerce?
4. What are the most popular product categories on Olist, and how do their sales volumes?
5. Level of satisfation
6. Payment type analysis
7. Count order and revenue over year
8. Number order per state
9. Average delivery time
   

## Why RFM Works
According to Arthur Hughes from the Database Marketing Institute, Customers who have purchased from you recently are more likely to respond to your next promotion than those whose last purchase was further in the past. This is a universal principle which has been found to be true in almost all industries: insurance, banks, cataloging, retail, travel, etc. It is also true that frequent buyers are more likely to respond than less frequent buyers. Big spenders often respond better than low spenders. <br>
By identifying these big spenders, we can focus our marketing efforts to these big spenders to make good returns.
## RFM Analysis
The “RFM” in RFM analysis stands for recency, frequency and monetary value. RFM analysis is a way to use data based on existing customer behavior to predict how a new customer is likely to act in the future. An RFM model is built using three key factors:

how recently a customer has transacted with a brand how frequently they’ve engaged with a brand how much money they’ve spent on a brand’s products and services a basic CRM system can perform rudimentary tracking of the three easily quantifiable characteristics that contribute to RFM analysis:

Recency value: This refers to the amount of time since a customer’s last interaction with a brand, which can include their last purchase, a visit to a website, use of a mobile app, a “like” on social media and more. Recency is a key metric because customers who have interacted with your brand more recently are more likely to respond to new marketing efforts.

Frequency value: This refers to the number of times a customer has made a purchase or otherwise interacted with your brand during a particular period of time. Frequency is a key metric because it shows how deeply a customer is engaged with your brand. Greater frequency indicates a higher degree of customer loyalty.

Monetary value: This refers to the total amount a customer has spent purchasing products and services from your brand over a particular period of time. Monetary value is a key metric because the customers who have spent the most in the past are more likely to spend more in the future.

## Conclusions



