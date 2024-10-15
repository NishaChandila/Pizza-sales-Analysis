# Pizza Sales Analysis

## Project Background

Pizza: a universal language of happiness. As one of the most beloved foods across the globe, pizza has become more than just a meal; it’s a cultural phenomenon. 

As a data analyst, this project is dedicated to uncovering vital insights in the pizza sales market by delving into consumer preferences and sales trends. My objective is to identify the types of pizzas that significantly impact revenue, pinpoint peak ordering times, and shed light on the least popular menu items. By analyzing these elements, I aim to craft targeted marketing strategies that leverage high-demand products while simultaneously addressing underperforming options. This comprehensive analysis will equip pizza businesses with actionable insights, empowering them to enhance sales performance and refine their menu offerings in an increasingly competitive landscape.

- The SQL queries utilized to inspect and perform quality checks can be found [here](https://github.com/NishaChandila/Pizza-sales/blob/main/pizza_sqlquery.sql).
- **Dataset** [order_details](https://github.com/NishaChandila/Pizza-sales/blob/main/order_details.csv), [orders](https://github.com/NishaChandila/Pizza-sales/blob/main/orders.csv), [pizza_type](https://github.com/NishaChandila/Pizza-sales/blob/main/pizza_types.csv) , [pizzas](https://github.com/NishaChandila/Pizza-sales/blob/main/pizzas.csv)
- The Power BI dashboard can be accessed [here](https://github.com/NishaChandila/Pizza-sales/blob/main/Pizza-sales-dashboard.pdf).

## About Dataset

### Dataset Overview
This project uses a dataset containing information about pizza orders, types of pizzas, and the details of each order. The data is divided into four tables:

![Dataset](https://github.com/NishaChandila/project-assets/blob/main/pizza-dataset.jpg?raw=true)

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

- **Dataset** [order_details](https://github.com/NishaChandila/Pizza-sales/blob/main/order_details.csv), [orders](https://github.com/NishaChandila/Pizza-sales/blob/main/orders.csv), [pizza_type](https://github.com/NishaChandila/Pizza-sales/blob/main/pizza_types.csv) , [pizzas](https://github.com/NishaChandila/Pizza-sales/blob/main/pizzas.csv)


## Executive Summary

As a data analyst, my goal is to tackle the challenges within the pizza sales market by conducting a thorough analysis of sales data. This project focuses on identifying key insights that can enhance operational efficiency, improve customer satisfaction, and drive revenue growth. I will analyze customer ordering patterns, assess the revenue contributions of different pizza types, and identify peak sales periods. Additionally, I will evaluate underperforming products to uncover opportunities for improvement. By leveraging these insights, I aim to provide strategic recommendations for optimizing product offerings, refining marketing initiatives, and maximizing profitability. Ultimately, my analysis will support informed decision-making that drives sustained business success.

![Pizza](https://github.com/NishaChandila/project-assets/blob/main/pizza.jpg?raw=true)

### Key Findings:

- **1. Order Analysis:**

The majority of orders are placed in the afternoon and on weekends, highlighting peak demand times that require optimal staffing and inventory levels. Small pizzas contribute 34% of total orders but represent only 22% of total revenue, signaling a potential area for growth through targeted promotions.

![Orders](https://github.com/NishaChandila/project-assets/blob/main/pizza1.jpg?raw=true)

- **2. Revenue Analysis:**

Large pizzas dominate revenue, accounting for nearly 47%, while classic pizzas have generated $220k in sales. Premium offerings like the Greek pizza show strong demand, presenting an opportunity to promote high-margin items. Chicken and veggie pizzas are underperforming, indicating a need for better marketing or menu enhancements.

![Revenue](https://github.com/NishaChandila/project-assets/blob/main/pizza2.jpg?raw=true)

3. **Forecasting:**

Sales forecasts predict consistent demand from January 3rd to January 10th, with opportunities to maximize revenue through targeted promotions and upselling during this expected period of steady sales. This allows for better planning of resources and marketing initiatives during peak demand.

![Forecasting](https://github.com/NishaChandila/project-assets/blob/main/pizza3.jpg?raw=true)

- The Power BI dashboard can be accessed [here](https://github.com/NishaChandila/Pizza-sales/blob/main/Pizza-sales-dashboard.pdf).

## Recommendations
Based on the analysis of pizza sales data, here are key recommendations to enhance revenue and align offerings with customer preferences:

1. **Boost Morning Orders**: Introduce breakfast-themed pizzas or limited-time morning promotions to attract customers who don’t typically order pizza in the morning.
2. **Promote Chicken Pizzas**: Increase sales of chicken pizzas by bundling them with popular sides, offering discounts, and featuring them in marketing campaigns.
3. **Leverage Medium and Large Preferences**: Run promotions to incentivize upsizing from medium to large pizzas, and offer combo deals for large pizzas to attract families and groups.
4. **Increase Small Pizza Revenue**: Introduce bundle deals like “Buy 2 small pizzas for a discount” and create lunchtime specials to make small pizzas more appealing to individuals.
5. **Revitalize Veggie Pizza Sales**: Develop premium veggie options and promote them as healthy choices to attract health-conscious consumers and boost revenue.
6. **Highlight High-Margin Pizzas**: Focus marketing efforts on high-margin premium pizzas, such as the Greek pizza, through limited-time specials or seasonal promotions.

- The SQL queries utilized to inspect and perform quality checks can be found [here](https://github.com/NishaChandila/Pizza-sales/blob/main/pizza_sqlquery.sql).
- **Dataset** [order_details](https://github.com/NishaChandila/Pizza-sales/blob/main/order_details.csv), [orders](https://github.com/NishaChandila/Pizza-sales/blob/main/orders.csv), [pizza_type](https://github.com/NishaChandila/Pizza-sales/blob/main/pizza_types.csv) , [pizzas](https://github.com/NishaChandila/Pizza-sales/blob/main/pizzas.csv)
- The Power BI dashboard can be accessed [here](https://github.com/NishaChandila/Pizza-sales/blob/main/Pizza-sales-dashboard.pdf).
