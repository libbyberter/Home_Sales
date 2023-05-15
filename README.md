# Home_Sales
HW22

This challenge uses SparkSQL to determine key metrics about home sales data. Spark was used to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

The following questions were answered:

1	What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
2	What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
3	What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
4	What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
5	Using cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
6	Run the query that filters out the view ratings with an average price of greater than or equal to $350,000 with partitioned data. Determine the runtime and compare it to uncached runtime.


