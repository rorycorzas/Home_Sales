# Challenge 22: Home Sales

# Background

In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

# Description of process

Using both PySpark and Spark SQL on Google Colab to determine key metrics about home sales data. Spark is utilized to create temporary views, partition the data, cache and uncache a temporary table.

As an example, I generated a table with two columns, one of which contained the average price, rounded to 2 decimal places, of only the 4-bedrooms in the database and the other one which contained the grouped years when each property was sold. I also compared the runtimes between running queries on an uncached temporary table, a cached temporary table, and a cached and partitioned with Parquet temporary table.

# Answer the following questions using SparkSQL:

Some of the data key metric questions that were answered:

* What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

* What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

* What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

* What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.



