# Superstore Analysis


# About the Data
The dataset consists of order information across 15 European countries with 10,000 rows and 28 columns of data. 

The data includes information such as customer name, order information (order date, manufacturer name, product name, segment, category , sub-category, units sold), location information (country, state, region, city), shipping info (days to ship, ship date, ship mode, ship status) as well as financial information (sales amount, sales forecast, profit, discount).

[Data Source](https://github.com/haiilingg/Business-Analytics-KYDP/blob/main/Data%20Visualisation/Expert%2B-%2BSuperstore%2B-%2BMaster.xlsx)


# Data Cleaning
1. Share your findings for data cleaning.
These columns (“Profit Per Order”, “Profit Per Customer” and “Profit”) actually consist of the same data, with “Profit Per Order” having 2 decimal places while the other 2 columns having no decimal places. I have processed using the “Profit Per Order” column and deleted the remaining 2 columns as it is more accurate to use data with decimal places instead of rounded up data.

I’ve also removed the “Number of Records” column as the data for all rows is “1”. 
2. How are you dealing with null values?
No null values were discovered.

3. Do you think some item data types need to be changed? Why do you think so?
No item data types need to be changed as all the data types are correct.
![image](https://github.com/haiilingg/Business-Analytics-KYDP/assets/130296433/8e4822e3-26d9-4c1a-8914-a984cf1b9d50)


# 💡 Highlights
•	Actual sales is lower than forecasted sales, hence more estimated units sold as compared to actual units sold.
•	Among the 15 countries, France has the highest sales amount while Denmark has the lowest.
•	Consumer is the segment with the highest sales and profit amount.
•	The highest sales and profit for actual days to ship is 4 days.
•	Nearly half of the orders are shipped early, followed by shipped late and shipped on time
•	Becky Castell is the customer that purchased the most quantity of products at 37 items
•	For profit by discount, 0% discount generated the highest profit at $384k, while discounts above 20% is loss making. The % that incurred the highest loss is a 50% discount given as it incurred a loss of $97k.

# 📊 Visualization
Produced a 1-pager dashboard using Power BI.

![Superstore Dashboard - TalentLabs (1)-1](https://github.com/haiilingg/Business-Analytics-KYDP/assets/130296433/c29df4dc-ba49-410f-953d-5695deb2de2d)


