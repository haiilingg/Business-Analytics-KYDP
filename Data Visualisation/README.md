# About the Data
The dataset consists of order information across 15 European countries with 10,000 rows and 28 columns of data. 

The data includes information such as customer name, order information (order date, manufacturer name, product name, segment, category , sub-category, units sold), location information (country, state, region, city), shipping info (days to ship, ship date, ship mode, ship status) as well as financial information (sales amount, sales forecast, profit, discount).

[Data Source](https://github.com/haiilingg/Business-Analytics-KYDP/blob/main/Data%20Visualisation/Expert%2B-%2BSuperstore%2B-%2BMaster.xlsx)

# Data Cleaning
These columns (“Profit Per Order”, “Profit Per Customer” and “Profit”) consists of the same data, with “Profit Per Order” having 2 decimal places while the other 2 columns having no decimal places. I have proceeded using the “Profit Per Order” column and deleted the remaining 2 columns as it is more accurate to use data with decimal places instead of rounded up data.

I’ve also removed the “Number of Records” column as the data for all rows is “1”. 

No null values were discovered and no item data types need to be changed as all the data types are correct.

# Superstore Analysis
Analysing from the financial perspective as at the end of the day we are looking at how well the Superstore performed in terms of sales and profit. 

We can also analyse it from quantity sold and days to ship(actual) as it is also one of the KPIs that determine if the Superstore is performing well.

# 💡 Highlights
- Actual sales ($2.94 mil) is lower than forecasted sales ($3.85mil), hence more estimated units sold (50.43k) as compared to actual units sold (37.77k).
- Among the 15 countries, France has the highest sales ($ 859k ) amount while Denmark has the lowest($ 9k).
- Consumer is the segment with the highest sales ($1.5bil) and profit amount($189k).
- The highest sales ($ 797k) and profit ($ 97k) for actual days to ship is 4 days.
- Nearly half of the orders are shipped early (49.2%), followed by shipped late (26.39%) and shipped on time(24.41%).
- Becky Castell is the customer that purchased the most quantity of products at 37 items.
- For profit by discount, 0% discount generated the highest profit at $384k, while discounts above 20% is loss making. The % that incurred the highest loss is a 50% discount given as it incurred a loss of $97k.

# Suggestions for improvement for problems identified
Problem 1
-
All orders with discounts above 20% are loss making.

Cause: Not having enough profit to cover the cost. As Profit = Selling Price – Cost, since it’s loss making it means the cost is too high or selling price is too low after applying the discount.

Solution: To cap the maximum discount % at 20%, or to increase selling price.

Problem 2
-
The actual sales amount is lower than forecasted sales amount; the actual units sold is lesser than forecasted sales unit.

Cause: Not selling enough units / selling price marked too low.	

Solution: To increase the number of customer base to sell to.


# 📊 Visualization
Produced a 1-pager dashboard using Power BI.

![Superstore Dashboard - TalentLabs (1)-1](https://github.com/haiilingg/Business-Analytics-KYDP/assets/130296433/c29df4dc-ba49-410f-953d-5695deb2de2d)


