# Marketing-Insights-for-E-Commerce-Company---Data-Analysis-SQL-Mini-Project

## Introduction
Datasets Sources: [Kaggle](https://www.kaggle.com/datasets/rishikumarrajvansh/marketing-insights-for-e-commercecompany/data).

The goal of this mini project is to obtain conclusions in the form of information/insight from data through specified business problems. From the Kaggle dataset source, there are two tables that will be used in this project: online_sales and customers. These two tables will be entered into a database (on Google BigQuery) named ecommerce. So, the tools for this data analysis mini project is using Google BigQuery.

## Business Problems to solve

1. Show a list of unique products sold in September 2019.
2. Display a list of product categories whose product sales total more than 10000.
3. Calculate the average GMV (Gross Merchandise Value) for all product sales in the "Bags" category. (Note: GMV = Quantity * Avg_Price)
4. Display a list of customers whose ‘tenure_months’ is greater than the average ‘tenure_months’ of all customers.
5. Display on which (unique) dates customers from cities starting with “New” made transactions.

## Conclusions

Based on the query results obtained, several conclusions can be drawn as follows:
1. There were a total of 199 products sold in September 2019. (file link for complete query results: [Answer No.1](https://drive.google.com/file/d/194_9r3sjFXoFhwgDFuQfv8bR6E71p2jG/view?usp=sharing)).
2. There are six product categories with sales of more than 10,000 products, namely: Lifestyle, Drinkware, Office, Apparel, Bags, and Nest-USA. 
3. The average GMV (Gross Merchandise Value) for all sales of products in the “Bags” category is around 80,4.
4. There are a total of 741 customers whose ‘tenure_months’ are greater than the average ‘tenure_months’ of all customers, where all of these customers come from five different cities, namely: California, Chicago, New Jersey, New York, and Washington D.C. (file link for complete query results: [Answer No.4](https://drive.google.com/file/d/1s1H43-IgPPn4YlNQec_0D8Ye4g4Hclp-/view?usp=sharing))
5. There were 330 different (unique) days, where customers from cities starting with “New” made transactions. (file link for complete query results: [Answer No.5](https://drive.google.com/file/d/1po0fbcWHg1lFyx86R8NG8GVgv2VjEn5w/view?usp=sharing))
