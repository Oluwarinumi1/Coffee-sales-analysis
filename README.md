# COFFEE SALES ANALYSIS
# Table of Contents
- [Title](#OFFEE-SALES-ANALSIS)
- [Overview](#Project-Overview)
- [Business Description](#Business-Description)
- [Aim](#Aim-of-the-project)
- [Dataset](#Dataset)
- [Cleaning Tools and Processes](#Data-Cleaning-Processes)
- [Analysis and Visualization](#Analysis-and-Visualization)
- [Dashboard](#Dashboard)
- [Insight and Recommendation](#Insight-and-Recommendation)
- [Summary](#Summary)
## Project Overview
The Coffee Sales Analysis dataset contains transactional records of coffee purchases made through a coffee vending machine or coffee shop over a specific period. The dataset is used to analyze sales performance, customer purchasing behavior, product popularity, and revenue generation patterns.
## Business Description
Jerome Limited Company is a coffee retail business engaged in the sale of various coffee beverages and related products to customers. The company aims to provide high-quality coffee products while ensuring excellent customer service and satisfaction. Through its daily operations, Jerome Limited Company generates sales revenue from different coffee types, including espresso, americano, cappuccinos, lattes, and other specialty beverages.
## Aim of the Project
The aim of this project is to analyze the coffee sales data of Jerome Limited Company in order to evaluate sales performance, identify customer purchasing patterns, and generate actionable insights that support effective business decision-making and improve overall profitability.
## Dataset
The Coffee Sales Dataset used by Jerome Limited Company contains transaction records of coffee purchases made by customers over a specified period. The dataset was collected to monitor sales performance, analyze customer purchasing behavior, and support data-driven decision-making within the company.
The dataset captures important details about each coffee sale, including the type of coffee purchased, transaction value, payment method, transaction time, and customer information. These records provide valuable insights into sales trends, customer preferences, revenue generation, and peak business periods. The dataset is gotten from Kaggle.com
### Key Variables in the Dataset
- Transaction– Unique identifier for each sales transaction.
- Coffee Type – Type of coffee purchased by the customer.
- Amount – Quantity of coffee purchased or transaction amount.
- Price – Unit price of the coffee product.
- Payment Method – Method used to complete the purchase (e.g., card payment).
- Card No. – Card identifier used for payment transactions.
- Hour – Time of the transaction, used for peak-hour analysis.
- Month Name – Month in which the sale was recorded.
- Customers – Customer-related information used for customer behavior analysis.
## Data Cleaning Processes
The data cleaning process was carried out to ensure the accuracy, consistency, and reliability of the coffee sales dataset before analysis. The following steps were undertaken:
- Removal of Duplicate Records - The dataset was checked for duplicate transactions, and any repeated records were removed to prevent inaccurate sales calculations.
- Handling Missing Values - Missing or incomplete entries were identified and addressed by either replacing them with appropriate values or removing records where necessary.
- Correction of Data Entry Errors - Inconsistencies in coffee names, payment methods, and other categorical variables were corrected to maintain uniformity throughout the dataset.
- Standardization of Data Formats - Date, time, currency, and text formats were standardized to ensure consistency and facilitate accurate analysis.
- Data Type Validation - Numeric fields such as sales amount and quantity sold were verified and converted to appropriate data types where necessary.
- Creation of Derived Variables - Additional fields such as Month, Day of Week, and Hour of Transaction were created from the date and time columns to support trend and time-based analysis.
- Verification of Data Accuracy - The cleaned dataset was reviewed to ensure that all values were accurate, complete, and ready for analysis.
### Tools used for Cleaning
- Microsoft Excel: Remove Duplicates, Filter, Sort, Find & Replace, Text-to-Columns.
- Power Query: Data transformation, data type conversion, handling missing values, and creating
## Analysis and Visualization
### Analysis
- Jerome Ltd. generated a total revenue of ₦115.432K.
- The business served approximately 1,000 customers.
- A total of 3,636 transactions were recorded.
- Americano is the most purchased coffee type.
- Latte is the second most popular coffee product.
- Espresso has the lowest sales and purchase frequency.
- Most customers prefer paying with cards rather than cash.
- The highest number of transactions occurs during the night period.
- Monthly sales were highest at the beginning of the year and gradually declined over subsequent months.
- Americano contributes the largest share of coffee sales revenue.
### Visualization
- KPI Cards - display Revenue, Customers, Transactions, Average Price, Highest Price, and Lowest Price.
- Sales Distribution Bar Chart - compares total sales across coffee types.
- Coffee Type Performance Chart - shows the average sales generated by each coffee product.
- Payment Method Pie Chart - illustrates the proportion of card and cash payments.
- Hourly Transaction Bar Chart - displays transaction volumes during Morning, Afternoon, and Night periods.
- Coffee Type Purchase Frequency Chart - shows how often each coffee type was purchased.
- Monthly Sales Line Chart - visualizes sales trends across different months.
- Coffee Sales and Revenue Analysis Chart - compares coffee products based on sales performance.
- Hourly Coffee Sales by Coffee Type Chart - shows how different coffee products perform at different times of the day.
- Filters (Month, Payment Method, and Week Day) - allow users to interactively explore the dashboard data.
 ## Dashboard
<img width="835" height="377" alt="Dashboard " src="https://github.com/user-attachments/assets/0e6e5f5a-b07e-415e-afc8-2c81520ef605" />

## Insight and Recommendation 
### Insights
- April recorded the lowest sales despite having the highest number of cash transactions. This may indicate that customers relied more on cash payments during the month, possibly due to temporary issues with electronic payment systems. If card payment services were disrupted, customers without cash may have abandoned their purchases, contributing to the decline in overall sales.
- The analysis shows that customers preferred milk-based coffee beverages over regular coffee and cocoa-based drinks, as they recorded higher sales. This suggests that milk-based coffee products are more popular and contribute significantly to overall revenue.
- The analysis indicates that coffee sales were highest during the night, suggesting that customers preferred purchasing coffee during evening and nighttime hours. This trend may reflect increased demand from individuals working late hours, night shifts, or those seeking coffee for leisure or study activities.
- The monthly sales trend exhibited an irregular pattern, with noticeable fluctuations throughout the analysis period. Sales reached their lowest levels in October 2024 and January 2025, indicating periods of reduced customer demand or possible operational and seasonal influences.
### Recommendations
- Ensure electronic payment systems are regularly monitored and maintained to minimize downtime. Providing multiple reliable payment options and having contingency plans in place can help prevent lost sales and improve the customer experience during payment system disruptions.
- Prioritize the availability of milk-based coffee beverages by maintaining adequate inventory and promoting them through special offers or combo deals. At the same time, consider introducing new milk-based drink varieties while evaluating strategies, such as targeted promotions or recipe enhancements, to increase demand for regular coffee and cocoa-based drinks.
- Increase staffing and inventory during peak evening and nighttime hours to meet customer demand efficiently. Additionally, consider introducing night-time promotions or loyalty offers to maximize sales and enhance customer satisfaction during these peak periods.
- Conduct further analysis to identify the factors contributing to the sales decline during these months, such as seasonal demand, marketing activities, pricing strategies, or operational challenges. Implement targeted promotional campaigns and customer engagement initiatives during historically low-performing months to help stabilize sales and improve overall performance.
## Summary
The analysis of the coffee sales dataset revealed several important insights into customer purchasing behavior and sales performance. Monthly sales fluctuated throughout the analysis period, with the lowest sales recorded in October 2024, January 2025, and April, suggesting the influence of seasonal or operational factors. Despite April recording the highest number of cash transactions, overall sales remained low, which may indicate temporary challenges with electronic payment methods that could have discouraged some customers from completing their purchases.

Customer preferences were also evident in the analysis. Milk-based coffee beverages generated higher sales than regular coffee and cocoa-based drinks, making them the most popular product category. In addition, coffee purchases peaked during the night, indicating increased demand during evening hours, possibly driven by customers working late, studying, or engaging in leisure activities.

Overall, the findings highlight opportunities for the business to improve payment system reliability, maintain adequate stock of high-demand products, optimize staffing during peak hours, and implement targeted promotional strategies during historically low-performing months to enhance sales performance and customer satisfaction.








 
