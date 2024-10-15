# Pizza Sales Analysis

## Project Background

Pizza: a universal language of happiness. As one of the most beloved foods across the globe, pizza has become more than just a meal; it’s a cultural phenomenon. 

As a data analyst, this project is dedicated to uncovering vital insights in the pizza sales market by delving into consumer preferences and sales trends. My objective is to identify the types of pizzas that significantly impact revenue, pinpoint peak ordering times, and shed light on the least popular menu items. By analyzing these elements, I aim to craft targeted marketing strategies that leverage high-demand products while simultaneously addressing underperforming options. This comprehensive analysis will equip pizza businesses with actionable insights, empowering them to enhance sales performance and refine their menu offerings in an increasingly competitive landscape.

- [The SQL queries utilized to inspect and perform quality checks can be found here](https://github.com/NishaChandila/Pizza-sales/blob/main/pizza_sqlquery.sql).
- **Dataset** [order_details](https://github.com/NishaChandila/Pizza-sales/blob/main/order_details.csv), [orders](https://github.com/NishaChandila/Pizza-sales/blob/main/orders.csv), [pizza_type](https://github.com/NishaChandila/Pizza-sales/blob/main/pizza_types.csv) , [pizzas](https://github.com/NishaChandila/Pizza-sales/blob/main/pizzas.csv)
- [The Power BI dashboard can be accessed here](https://github.com/NishaChandila/Pizza-sales/blob/main/Pizza-sales-dashboard.pdf).

## About Dataset

### Dataset Overview
This project uses a dataset containing information about pizza orders, types of pizzas, and the details of each order. The data is divided into four tables:

1. **order_details**
   - **Description**: This table contains detailed information about each individual pizza order.
   - **Rows**: 48,621
   - **Columns**: 4 (order_details_id, order_id, pizza_id, quantity)

2. **orders**
   - **Description**: This table stores information about the orders made by customers.
   - **Rows**: 21,351
   - **Columns**: 3 (order_id, date, time)

3. **pizza_types**
   - **Description**: This table lists all the available types of pizzas in the system.
   - **Rows**: 33
   - **Columns**: 4 (category, ingredients, name, pizza_type_id)

4. **pizzas**
   - **Description**: This table contains information about individual pizzas available for order.
   - **Rows**: 97
   - **Columns**: 4 (pizza_id, pizza_type_id, price, size)

### Dataset Visualization
![Dataset Overview](link_to_dataset_image)

## Executive Summary

As a data analyst, my goal is to tackle the challenges within the pizza sales market by conducting a thorough analysis of sales data. This project focuses on identifying key insights that can enhance operational efficiency, improve customer satisfaction, and drive revenue growth. I will analyze customer ordering patterns, assess the revenue contributions of different pizza types, and identify peak sales periods. Additionally, I will evaluate underperforming products to uncover opportunities for improvement. By leveraging these insights, I aim to provide strategic recommendations for optimizing product offerings, refining marketing initiatives, and maximizing profitability. Ultimately, my analysis will support informed decision-making that drives sustained business success.

### Key Findings:
- **Revenue Drivers**: Large pizzas contribute nearly 47% of total revenue, with classic pizzas generating approximately $220k. Premium options, like the Greek pizza, show strong demand.
- **Underperforming Items**: Chicken and veggie pizzas are underperforming, contributing less to overall sales compared to other offerings.
- **Order Timing**: The majority of orders are placed in the afternoon and during weekends, indicating peak periods for staffing and inventory management.
- **Small Pizza Sales**: Small pizzas account for only 22% of total revenue, presenting an opportunity for targeted promotions to boost sales.

## Recommendations
Based on the analysis of pizza sales data, here are key recommendations to enhance revenue and align offerings with customer preferences:

1. **Boost Morning Orders**: Introduce breakfast-themed pizzas or limited-time morning promotions to attract customers who don’t typically order pizza in the morning.
2. **Promote Chicken Pizzas**: Increase sales of chicken pizzas by bundling them with popular sides, offering discounts, and featuring them in marketing campaigns.
3. **Leverage Medium and Large Preferences**: Run promotions to incentivize upsizing from medium to large pizzas, and offer combo deals for large pizzas to attract families and groups.
4. **Increase Small Pizza Revenue**: Introduce bundle deals like “Buy 2 small pizzas for a discount” and create lunchtime specials to make small pizzas more appealing to individuals.
5. **Revitalize Veggie Pizza Sales**: Develop premium veggie options and promote them as healthy choices to attract health-conscious consumers and boost revenue.
6. **Highlight High-Margin Pizzas**: Focus marketing efforts on high-margin premium pizzas, such as the Greek pizza, through limited-time specials or seasonal promotions.

- The SQL queries utilized to inspect and perform quality checks can be found [here](link_to_sql_queries).
- The dataset used can be found [here](link_to_dataset).
- The Power BI dashboard can be accessed [here](link_to_dashboard).
