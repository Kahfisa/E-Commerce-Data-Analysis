# E-Commerce-Data-Analysis

## Introduction
This project analyzes e-commerce data to identify key insights into customer behavior, revenue patterns, and product performance. It explores customer demographics, sales trends, regional revenue contributions, payment preferences, and purchasing patterns to provide actionable insights for strategic decision making.

## Tools
- Python (Pandas, Matplotlib, Seaborn)

## Dataset
|Dataset             |Column                                                                                                                                                                               |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Customers           |customer_id, customer_unique_id, customer_zip_code_prefix, customer_city, customer_state                                                                                             |
|Geolocation         |geolocation_zip_code_prefix, geolocation_lat, geolocation_lng, geolocation_city, geolocation_state                                                                                   |
|Order Items         |order_id, order_item_id, product_id, seller_id, shipping_limit_date, price, freight_value                                                                                            |
|Order Payments      |order_id, peymant_sequential, payment_type, payment_installments, payment_value                                                                                                      |
|Order Reviews       |review_id, order_id, review_score, review_comment_title, review_comment_message, review_creation_date, review_answer_timestamp                                                       |
|Orders              |order_id, customer_id, order_status, order_purchase_timestamp, order_approved_at, order_delivered_carrier_date, order_delivered_customer_date, order_estimated_delivery_date         |
|Products            |product_id, product_category_name, product_name_length, product_description_length, product_photos_qty, product_weight_g, product_length_cm, product_height_cm, product_width_cm     |
|Sellers             |seller_id, seller_zip_code_prefix, seller_city, seller_state                                                                                                                         |

## Business Question
- What are the demographics of e-commerce customers?
- Which product categories are the most and least frequently purchased by customers?
- What are the e-commerce revenue trends throughout 2018?
- Which cities and states contribute the most to total revenue?
- Which payment methods are most commonly used by customers?
- When was the last time customers made a transaction on the platform?
- How frequently do customers make purchases on the e-commerce platform?
- What is the total spending of customers during their transactions on the platform?

## Process
- Gathering Data
- Assessing Data
- Cleaning Data
- Exploratory Data Analysis
- Visualization
