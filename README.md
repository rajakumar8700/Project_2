# Walmart Sales AnaLysis
## Project Objective:
- Analyze Walmart's sales trends on a quarterly and semester-wise basis to understand performance over time.
- Identify holiday events and evaluate their impact on sales, especially during high-demand periods.
- Detect stock-out scenarios by checking sales patterns and inventory availability around holidays.
- Provide insights to help optimize inventory management and ensure products remain in stock during peak seasons.
- Use data to support better planning and forecasting, reducing missed sales opportunities due to stock shortages.

  ## Dataset Used:
  - <a href= "https://github.com/rajakumar8700/Project_2/blob/main/Walmart_Store_sales.csv">Walmart_Store_sales</a>

## Questions (KPIs):

- **Basic Statistics tasks**
1. Which store has maximum sales
2. Which store has maximum standard deviation i.e., the sales vary a lot. Also, find out the coefficient of mean to standard deviation
3. Which store/s has good quarterly growth rate in Q3’2012
4. Some holidays have a negative impact on sales. Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together
5. Provide a monthly and semester view of sales in units and give insights

- **Statistical Model**
1. For Store 1 – Build  prediction models to forecast demand
2. Linear Regression – Utilize variables like date and restructure dates as 1 for 5 Feb 2010 (starting from the earliest date in order). Hypothesize if CPI, unemployment, and fuel price have any impact on sales.
3. Change dates into days by creating new variable.

## Project Insights:
- Store 7 had the highest growth rate at +13.33% followed by Store 16 (+8.49%), Store 35 (+4.47%), and so on.
- months like feb, sep and dec have high sales this means that it must be due to holiday events
- According to the bar-graph representing weekly sales by holidays **Thanksgiving** has the highest sales 

## Python Library Used:
- Jupyter Notebook
-  numpy
- pandas
- matplot
- seaborn
- Linear Regression
- Train_test_split
- r2_score
