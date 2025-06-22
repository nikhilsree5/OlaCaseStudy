# Neural Network-Based Delivery Time Prediction for Food Logistics at Porter

## 🎯 Objective
To develop an intelligent delivery time prediction system using neural networks that enhances customer satisfaction and operational efficiency by providing accurate, real-time ETAs for food deliveries across Porter’s intra-city logistics network.

## 📝 Project Report
-You can access the complete project python file here - [Python](https://github.com/nikhilsree5/PortBusinessCase/blob/main/Ola_Case_study.ipynb)
-You can access the complete project in pdf format here - [Report](https://github.com/nikhilsree5/PortBusinessCase/blob/main/Ola_Case_study.pdf)

## 📚 About Data
ach row in this file corresponds to one unique delivery. Each column corresponds to a feature as
explained below.
1. : integer id for the market where the restaurant lies
2.  : 
3.  : 
4.  : 
5.  : (how the order was placed ie: through
porter, call to restaurant, pre booked, third part etc)
6.  : 
7.  : 
8.  : 
9.  : 
10.  : 
11.  : 
12.  : 
13.  : 

| Feature | Description |
|:--------|:------------|
| market_id  | integer id for the market where the restaurant lies|
| created_at | the timestamp at which the order was placed |
| actual_delivery_time | the timestamp when the order was delivered |
| store_primary_category | category for the restaurant |
| order_protocol | integer code value for order protocol |
| total_items subtotal |  final price of the order |
| num_distinct_items |  the number of distinct items in the order | 
| min_item_price | price of the cheapest item in the order | 
| max_item_price | price of the costliest item in order |
| total_onshift_partners | number of delivery partners on duty at the time order was placed |
| total_busy_partners | number of delivery partners attending to other tasks |
| total_outstanding_orders | total number of orders to be fulfilled at the moment |
| estimated_store_to_consumer_driving_duration | approximate travel time from restaurant to customer |

## Outcome Insights and Reccomendations

-Neural Network model have performed well with a good performance metrics.
-These models could be used to predict delivery time of orders in a future percpective.
-From the feature correlation, total outstanding orders and total busy dashers are found to be most important is deciding the delivery time of orders from Porter.
