# Olist E-Commerce -Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMjU5MTI4NDgtNThhYi00MjlhLWE2OWEtOGZkNzExMzk5OTI5IiwidCI6IjZjZDQxMTc3LThmMzgtNGE5ZS04NWY5LWI5OGRjMjA3NTYyMyJ9

## Problem Statement

Welcome! This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

This is real commercial data, it has been anonymised, and references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses.


## Task List
Weekday Vs Weekend (order_purchase_timestamp) Payment Statistics

Number of Orders with review score 5 and payment type as credit card.

Average number of days taken for order_delivered_customer_date for pet_shop

Average price and payment values from customers of sao paulo city

Relationship between shipping days (order_delivered_customer_date - order_purchase_timestamp) Vs review scores.


# Data Model

![Screenshot 2024-02-04 174241](https://github.com/Ad1tyaBhardwaj19/Olist_Ecommerce_Analysis/assets/158819480/be0eb29d-f53d-4e84-b722-331dff95656c)


 
 # Overall Analysis View

 
![Screenshot 2024-02-04 181649](https://github.com/Ad1tyaBhardwaj19/Olist_Ecommerce_Analysis/assets/158819480/dd00a584-c084-451b-9d6e-db45ec5e68b0)


# Task Analysis View

![Screenshot 2024-02-04 181707](https://github.com/Ad1tyaBhardwaj19/Olist_Ecommerce_Analysis/assets/158819480/652d3507-8442-4bbc-96c7-1dbd5b53e95d)



# Insights From the Dashboard 

Report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

###  Ratings
 - Overall Ratings were 4.09 and in each quarter, every year there were not more than 3 products whose rating where less than 2.5
 - There was a inverse realtion between the shipping days and Review Score. The Reiews were less where the shipping time taken was higher 

### Sales, Revenue, Sellers
- In year 2016,2017 there was continous growth in the totals sales by every quarter but from second quarter of 2018 the sales went down drastically
- We saw a decrese in Total Revenue and sellers in third quarter of 2018 
- Most of the payments were done by the credit Cards and most of the payments were done on the weekends 
- Most of the sales were happened in Sao Paulo City only 


