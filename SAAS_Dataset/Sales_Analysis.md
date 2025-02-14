# Project: Sales Analysis in Amazon QuickSight

## Table of Contents  
1. [Introduction](#introduction)
2. [Project Aim](#project-aim)
3. [Project Description](#project-description)
4. [About the Dataset](#about-the-dataset)
5. [Data Analysis](#data-analysis)
6. [Data Visualization and Dashboard Development](#data-visualization-and-Dashboard-Development)
7. [Interpretation of Data](#interpretation-of-data)
8. [Recommendations](#recommendations)
9. [Conclusion](#conclusion)

## Introduction
In today’s data-driven business environment, leveraging analytics tools to gain insights into sales performance is essential. This project focuses on developing a Sales Analysis Dashboard using **Amazon QuickSight**, a cloud-powered business intelligence service.
The dashboard provides a comprehensive view of key sales metrics, customer demographics, and industry performance, enabling data-driven decision-making.

## Project Aim
This project aims to design and implement a Sales Analysis Dashboard that visualizes key performance indicators (KPIs) such as total sales, profit, customer distribution, and industry trends. The dashboard serves as a decision-support tool, helping
stakeholders identify patterns, optimize sales strategies, and enhance profitability.

## Project Description
The project involved analyzing SAAS sales data, identifying key business metrics, and developing interactive visualizations using Amazon QuickSight. The dataset includes transactional information such as order details, customer demographics, industry segmentation, and
financial performance (sales, quantity, discounts, and profits). The final dashboard provides an intuitive interface for monitoring business performance across different dimensions.

## About the Dataset
The dataset was downloaded from the AWS Skill Builder page while taking the course **Amazon QuickSight - Getting Started**. It contained the following columns:  
* _Row ID_: A unique identifier for each row in the dataset
* _Order ID_: A unique identifier for each order transaction
* _Order Date_: The date when the order was placed
* _Date Key_: A formatted date reference (e.g., YYYYMMDD) for time-based analysis
* _Contact Name_: The name of the primary contact person for the order
* _Country_: The country where the customer is located.
* _City_: The city in the country where the customer is based
* _Region_: The broader geographical area where the customer or order is located
* _Subregion_: A more granular classification within a region
* _Customer_: The name of the business placing the order
* _Customer ID_: A unique identifier assigned to each customer
* _Industry_: The industry in which the customer operates
* _Segment_: The market segment the customer belongs to 
* _Product_: The name of the product purchased
* _License_: The license associated with the product
* _Sales_: The total sales amount for the order
* _Quantity_: The number of units of the product ordered
* _Discount_: The discount applied to the order
* _Profit_: The net profit earned from the order after costs and discounts


## Data Analysis
The dataset was structured into key categories:  

1. **Sales Performance**  
Analysis of total sales, profit, and quantity sold.  

2. **Customer Distribution**  
Creating a breakdown of customers by region, subregion, and industry.  

3. **Product and Industry Trends**  
Determining sales and profit distribution across various industries and product categories.  

4. **Time-Based Analysis**  
Determining monthly sales trends across different customer segments (Enterprise, Strategic, SMB).  

5. **Geographical Analysis**  
Analyzing performance by regions (APJ, AMER, EMEA).  

6. **Visualization Techniques**
Creating charts and visuals to highlight trends and insights.


## Data Visualization and Dashboard Development
Amazon QuickSight was used to create an interactive and visually appealing dashboard with multiple widgets and filters. Key features included:  

1. **Cards**  
   * Total Customers
   * Total Quantity Ordered
   * Total Sales
   * Total Profit

2. **Bar Charts ** 
Bar charts were used to show Sales and Profit by Product, Industry, Segment, and Region to compare performance.  
   * **For Sales**
     - Sales by Product
     - Sales by Industry
     - Sales by Segment
     - Sales by Region

   * **For Profit**  
     - Profit by Product 
     - Profit by Industry using bar charts to compare performance.
     - Profit by Segment
     - Profit by Region

3. **Line Charts**  
Line charts were used to show monthly Performance trends for both sales and profit. In addition, a forecast was added to predict trends for upcoming months.
Filtering Options to refine analysis based on different business needs.

4. The dashboard was created, putting all the visuals in one place to easily communicate insights. The figure below shows the dashboard.

<figure>
  <img src="https://github.com/Songonge/AWS-Projects/blob/main/SAAS_Dataset/Sales_Dashboard.png" width=100% height=100% alt="alt text">
  <figcaption>Figure: SAAS Sales Analysis Dashboard</figcaption>
</figure>
<br/><br/> 

Link to the [online dashboard](https://us-east-1.quicksight.aws.amazon.com/sn/dashboards/5efc2951-bf9d-4d79-9006-76beaccab7ae/views/12da365b-5476-4ad6-a07b-c215a91693e5?directory_alias=Songonge)


## Interpretation of Data
The dashboard revealed the following key insights:  

1. The total sales amount was $2,297,201.86, with a total profit of $286,397.02.  
2. Top-performing industries included Finance, Energy, and Manufacturing.
3. Key revenue-driving products included ContactMatcher, FinanceHub, and Site Analytics.
4. The SMB segment contributed the highest sales and profit volume, followed by the Strategic and Enterprise segments.
5. Sales varied significantly across regions, with AMER leading in revenue generation.


## Uncovering Insights
1. Profitability varies by product: Some products showed high sales but lower profit margins.
2. Regional differences: Certain products performed better, indicating potential for expansion in underperforming regions.
3. Discounting impact: Analyzing discount rates helped assess whether promotions positively affected overall revenue.
4. Seasonality in sales – Monthly trends suggested peak sales periods such as November and December while months with fewer revenues were January and February.


## Recommendations
1. Optimize product pricing based on profit margins to improve overall revenue.
2. Expand into high-growth regions to increase market penetration.
3. Target industry-specific marketing strategies to boost sales in lower-performing sectors.
4. Monitor customer segments closely to develop retention strategies for high-value clients.


## Conclusion
Analyzing the SAAS sales dataset and creating a dashboard successfully provided actionable insights into business performance. By leveraging Amazon QuickSight, the dashboard would allow stakeholders to make informed decisions based on real-time data, optimizing 
sales strategies and profitability. Further enhancements, such as integrating machine learning models for sales forecasting, helped in predictive analytics and could drive long-term business success.


