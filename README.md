# Ecommerce Performance Analysis

## Overview
This project analyzes an e-commerce dataset to identify key factors affecting sales performance, customer satisfaction, and logistics efficiency.

## Obective
To uncover insights that support data-driven decision-making and improve overall business performance.

## Dataset
The dataset includes information about orders, customers, products, categories and reviews. Multiple tables were merged to create unified dataset for analysis.

## Tools & Skills
- Python (pandas, numpy, Matplotlib, Seaborn)
- Jupyter notebook
- Power BI (in progress)

## Data preparation
- Merged multiple datasets
- Handled missing values
- Converted date columns into datetime format
- Created new features such as delivery time and delay indicators

## Analysis performed
### 1 Delivery performance & customer satisfaction
Delivery delays negatively impact customer satisfaction, with lower review scores observed in delayed orders.
### 3 Price & customer satisfaction
No strong relationship was found between product price and customer satisfaction, suggesting that operational factors play a more important role.
### 4 Delivery Delays by State
Some states show higher average delivery delays, indicating potential regional inefficiencies in logistics.
### 5 Sales over time
Sales increased significantly during 2017 and stabilized in 2018, with a noticeable peak in november, likely due to seasonal events.
### 6 Sales by State
SP generates the highes revenue, driven by a high number of orders, while other states show different purchasing behaviors.
### 7 Orders vs Average Ticket by State
Some states generate high revenue through volume (many orders with low ticket), while others generate revenue through higher-value transactions but lower frecuency.
### 8 Category performance
Different categories contribute to revenue in distinct ways: some through high purchase frecuency and others through higher transaction value. 

## Key insights
- Delivery delays significantly reduce customer satisfaction.
- SP generates the highest revenue driven by high order volume, while PB shows higher ticket value but lower frequency.
- Sales grew rapidly in 2017 and stabilized in 2018, with a peak in November (likely due to seasonal events).
- Health & Beauty leads in revenue, while Watches & Gifts has the highest ticket value and Bed Bath Table the highest order volume.

## Interactive Dashboard

[![Ver Video Demo de Power BI](https://cdn.loom.com/sessions/thumbnails/a9aea8de7c644af580b18109e3c541a8-6f57e3b365571501-full-play.gif)](https://www.loom.com/share/a9aea8de7c644af580b18109e3c541a8)

## Key Insights
- Impact of Delivery Time on Satisfaction: It was found that longer delivery times cause a significant drop in the average rating.
- Fulfillment Status: 7.85% of orders were delayed.
- Metrics by Category: Analysis of average order value and sales volume.

## Conclusion
Delivery performance is a key driver of customer satisfaction, highlighting the importance of optimizing logistics operations.

Additionally, sales patterns vay across regions and product categories, revealing differents customer behaviors. These findings provide opportunities to optimize business strategies, such as increasing averageticket size in high-volume regions and boosting demand in high-value categories.

### Future work
Develop an interactive dashboard in Power BI.
