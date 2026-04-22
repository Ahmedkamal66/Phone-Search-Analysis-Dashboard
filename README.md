
# Phone Search Analysis Dashboard

## 📌 Project Overview
This project presents a comprehensive analysis of a dataset containing pricing and model information for various smartphones. 
The primary objective is to determine average prices, customer ratings, and sales trends for each product based on historical sales data. 

## 🛠️ Tools & Technologies
* **Power BI**: The core tool used for loading the business dataset and creating the visual dashboard.
* **Power Query**: Utilized for the ETL process, including data cleaning, manipulation, and error checking.
* **DAX (Data Analysis Expressions)**: Used to create calculated columns and measures to answer specific business questions.

## 🧹 Data Processing & Cleaning
To ensure data integrity, the following steps were performed using Power Query:
* **Data Type Validation**: Checking data types to identify and correct errors.
* **Null Management**: Identifying and handling null values within the dataset.
* **Data Manipulation**: General cleaning to prepare the dataset for analysis.

## 📊 Business Metrics (DAX)
Several key performance indicators (KPIs) and metrics were calculated to drive the analysis:
* **Pricing Analysis**: Average product price, price variance, and comparison between original and minimum offer prices.
* **Sales & Performance**: Total sales volume and sales volume per product.
* **Ratings**: Average star ratings across different phone models.
* **Market Status**: Counting "Amazon Choice" products and comparing them with "Best Sellers".
* **Sustainability**: Calculating the percentage of products marked as "Climate Pledge Friendly".

## 📈 Dashboard & Visualizations
The dashboard is designed to illustrate specific data purposes through various visual styles:
* **Bar Charts**: Used for visualizing average prices, sales volumes, and customer ratings.
* **Pie Charts**: Used to show the distribution of Prime eligibility, best-selling status, and climate-friendly products.
* **Histograms**: Planned to represent the distribution of prices and ratings.

## 🗂️ Dataset Dictionary
The dataset includes the following key columns:
* `asin`: Unique identification for each phone.
* `product_title`: The name of the phone.
* `product_price`: The current price of the phone.
* `product_original_price`: The original price of the phone.
* `Currency`: The currency code for the region where the phone is sold.
* `product_star_rating`: Customer rating for the phone.
* `is_best_seller`: Indicates if the phone is a best-selling model.
* `is_prime`: Indicates if the product is eligible for Prime.
* `climate_pledge_friendly`: Indicates whether the product is environmentally friendly.
* `sales_volume`: Total sales recorded per product.
"""
## Dashboard
![image](https://github.com/Ahmedkamal66/Phone-Search-Analysis-Dashboard/blob/main/Dashboard.png)
