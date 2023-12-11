# About the Dataset
The dataset comprises Superstore order information spanning 15 European countries, consisting of 10,000 rows and 28 columns of data. 

The dataset includes a variety of information such as customer details, order details (order date, manufacturer name, product name, segment, category, sub-category, units sold), location details (country, state, region, city), shipping information (days to ship, ship date, ship mode, ship status) and financial data (sales amount, sales forecast, profit, discount).

[Data Source](https://github.com/haiilingg/Business-Analytics-KYDP/blob/main/Data%20Visualisation/Expert%2B-%2BSuperstore%2B-%2BMaster.xlsx)

# Data Cleaning
The columns, namely "Profit Per Order" "Profit Per Customer" and "Profit" contain the same data. However, "Profit Per Order" is represented with 2 decimal places, while the other two columns have no decimal places. I have opted to proceed using the "Profit Per Order" column due to its higher precision and consequently, I have deleted the remaining two columns.

Additionally, I have removed the "Number of Records" column as its data for all rows is consistently "1."

Upon inspection, no null values were found and there is no need to change any item data types as all data types are correct.

# Superstore Analysis
Analysing the Superstore's performance from a financial perspective provides insights into its sales and profit outcomes. 

Additionally, analysing key performance indicators (KPIs) such as quantity sold and days to ship (actual) contributes to a comprehensive evaluation of the Superstore's overall performance

# 💡 Highlights
- Actual sales amounting to $2.94 million is lower than the forecasted sales of $3.85 million, resulting in an overestimation of units sold (50.43k) compared to the actual units sold (37.77k).
- Among the 15 countries, France stands out with the highest sales amount of $859k, while Denmark has the lowest at $9k.
- The Consumer segment leads in both sales ($1.5 billion) and profit ($189k).
- The highest sales ($797k) and profit ($97k) for actual days to ship occur within a 4-day timeframe.
- Shipping metrics reveal that nearly half of the orders are shipped early (49.2%), followed by shipped late (26.39%), and shipped on time (24.41%).
- Becky Castell emerges as the top customer, purchasing the most quantity of products at 37 items.
- Analyzing profit by discount indicates that a 0% discount generates the highest profit at $384k, while discounts above 20% result in losses. The highest loss percentage is incurred at a 50% discount, leading to a loss of $97k.

# Suggestions for improvement for problems identified
Problem 1
-
All orders with discounts exceeding 20% result in losses. 

Hypothesis: Insufficient profit margin to cover costs. Given that Profit = Selling Price - Cost, a loss indicates either an excessively high cost or an insufficient selling price after applying the discount.

Solution: Consider implementing measures such as capping the maximum discount percentage at 20% or adjusting the selling price upward."

Problem 2
-
The actual sales amount is lower than the forecasted sales amount;the actual units sold are less than the forecasted sales units.

Hypothesis: Insufficient sales volume or potentially undervalued selling prices.

Solution: Consider expanding the customer base to increase sales opportunities.


# 📊 Visualization
Produced a 1-pager dashboard using Power BI.

![Superstore Dashboard - TalentLabs (1)-1](https://github.com/haiilingg/Business-Analytics-KYDP/assets/130296433/c29df4dc-ba49-410f-953d-5695deb2de2d)


