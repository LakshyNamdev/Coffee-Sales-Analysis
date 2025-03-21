# Coffee-Sales-Analysis (Using Python).

## Overview.
This dataset contains detailed records of coffee sales from a vending machine.
The vending machine is the work of a dataset author who is committed to providing an open dataset to the community.
It is intended for analysis of purchasing patterns, sales trends, and customer preferences related to coffee products.

## Data Collection Period.
The dataset spans from March 2024 to Present time, capturing daily transaction data. And new information continues to be added.

## Dataset Used.
- <a href="https://github.com/LakshyNamdev/Coffee-Sales-Analysis/blob/main/Coffee_Sales.csv">Coffee-Sales-Analysis</a>

## Questions (KPIs).
- Total Sales Per Day and Monthly Sales.
- To Calculate Monthly Sales data.
- Payment Method Preferences (Cash vs Card).
- Customer Loyalty by Repeat Purchases.
- Peak Sales Analysis (Sales by Hour).
- Coffee Category Analysis.
    - Total Revenue by Coffee Type.
    - Top Selling Coffee by Coffee Type.
- Sales By Day of the Week.    

## Tasks.
- Time Series Exploratory Data Analysis
- Next day/week/month sales
- Specific customer purchases

## Process.
* Importing Necessary Libraries
  - Pandas, Numpy for data manipulation and Matplotlib, Seaborn for data visulization.
* Loading the Dataset
  - Use the pd.read_csv() function to read the file.
  - Use df.head() to check first few rows.
* Data Exploration
  - Use df.info() to check data types and missing values.
  - The date column is converted to datetime format.
* Exploratory Data Analysis (EDA)
  - Total Sales Per Day and Monthly Sales: Aggregation of sales data over time.
  - Monthly Sales Calculation: Summing sales per month.
  - Payment Method Analysis: Checking customer preferences between cash and card.

## Project Insight. 
- Comparted to other Months, the highest sales were in October which was 13891.16 dollars.
- Out of the Total Sales, only 2.7% people paid in Cash while 97.3% people paid by Card.
- Sales peak between 8 AM - 11 AM, suggesting a morning rush for coffee.
- A significant portion of customers are repeat buyers, indicating strong brand loyalty.
- The highest sales occur on Tuesday of the week.
- Out of all coffee types, Espresso has least sales which was 2561.56 dollars.
- Premium blends and specialty coffee have higher sales compared to regular coffee.


## Conclusion:
Your coffee shop experiences high demand in the morning, with a loyal customer base favoring specialty coffee. To maximize revenue, you may consider promotional offers during off-peak hours or expanding the menu of top-selling coffee types.
