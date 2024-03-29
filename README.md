# Case Study - Happy Deliveries (a food delivery company)
## Project Overview

The project uses the data from Happy Deliveries, a food delivery business based in Ireland. The competition in the food delivery industry is tough, hence the company aims to utilize their data to in order to gain advantage over its competitors. 

### Project Goal

The goal of the project is to provide answers to questions related to the business performance of the company.

### Datasets and Attributes

There are two datasets: ``orders`` and ``customers``. 

The ``orders`` dataset contains details of orders placed with Happy Deliveries from 2021 & 2022. It contains 998 records with the following attributes:

1. ``order_id``: Unique ID of order
2. ``order_timestamp``: Timestamp for when the customer placed the order.
3. ``delivered_timestamp``: Timestamp for when the order was delivered.
4. ``driver_id``: ID of the delivery driver.
5. ``restaurant_id``: ID of the restaurant ordered from.
6. ``cust_id``: ID of the customer who placed the order.
7. ``delivery_region``: County in Ireland the order was delivered.
8. ``discount_applied``: True or False whether or not the customer applied a discount to the order
9. ``discount_code``: Discount code applied, note that not all orders have discounts applied.
10. ``order_total``: Cost of the order before discount in Euros (€)
11. ``discount_pc``: Percentage discount
12. ``status``: The status of the delivery, whether it was successfully delivered or not.

The ``customers`` dataset contains loyalty card customers of Happy Deliveries which contains customer details. It has 406 records with the following attributes:

1. ``id``: Unique ID of customer
2. ``first_name``: Customer's first name.
3. ``last_name``: Customer's last name.
4. ``age``: Age of customer.
5. ``city``: City in Ireland where customer is based, note customer's city may be different from their ‘delivery_region’
6. ``email``: Email address of customer.

### Project Scope
1. Data Cleaning/Preprocessing<br> 
2. Exploratory Data Analysis<br> 
3. Conclusion
4. Resources

[NBViewer - Happy Deliveries Notebook](https://nbviewer.org/github/DSKunth/HappyDeliveries-CaseStudy/blob/main/notebooks/WAIACaseStudy_HappyDeliveries.ipynb)