# Home_Sales

INTRODUCTION 

In this challenge , we were asked to use our knowledge of sparkSQL to determine key metrics about home sales data.Then we used spark to create temporary views ,partition the data, cache and uncache a temporary table, and verify that the table had been uncached.

Analysis 

Dataframe (df) was read into the notebook, and I evaluated the schema.
I decided to change the view and price to integers since i would be working and sorting those numbers and not as strings 
SQL queries were very starightforward , there was a diffrence in speed by using the partioned data 
For the final query , first time it ran at 1.63 seconds , when the temporary table was cached, it ran in 0.76 seconds.The same query using partioned data ran in 0.58 seconds . An improvement , even for a small data set.

The table was successfully uncached at the end of the notebook.

Although we ran the query for each year , i am particulary comparing the home_sales during the year 2017

The Average price for a four-bedroom house sold was 2,965,76.69
The Average price for three bed and three bathroom sold was 2,926,76.79
The Average price for three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet was 2,803,17.58
The "View" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

Finally , The "home_sales" temporary table is uncached and verified

Conclusion 

Overall , This project was a great excersize to learn the usage of Spark along with SQL . Running the SQL Queries helped us to ariive us at the average home price for each of the year . For completing thsi project we used the following resources :

Home_Sales.ipynb as a starter code 
"Xpert Learning Assistant Chat+"
 Stack Overflow
 
