# Home Sales

In this challenge, SparkSQL was used to determine key metrics about home sales data. Then Spark was used to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Analysis & Results

* The average price for a four-bedroom house sold for each year? Round off your answer to two decimal places:

<img width="1390" alt="Screen Shot 2023-05-28 at 3 52 27 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/52bfd400-12b5-4b6d-a785-d6d7c5e1ad79">

* The average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places:

<img width="1393" alt="Screen Shot 2023-05-28 at 3 54 49 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/ca234aa9-0a3d-420e-97f2-ef2ce614740d">

* The average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places:

<img width="1394" alt="Screen Shot 2023-05-28 at 3 56 21 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/485b7568-2888-40e8-9887-279335e7787a">

* The "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places:

<img width="1398" alt="Screen Shot 2023-05-28 at 3 57 45 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/7ed5d317-7ee9-4cd8-a125-e18efdd18dc5">

* Cache the temporary table home_sales and check if your temporary table is cached:

<img width="1397" alt="Screen Shot 2023-05-28 at 4 05 34 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/89cb94c2-b3a5-4a5a-a070-c77a89520a7a">

* The "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places--CACHED DATA:

<img width="1394" alt="Screen Shot 2023-05-28 at 4 10 29 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/7a54e83a-b8e3-4ac7-8702-d4ba9edd8507">

* Partition by the "date_built" field on the formatted parquet home sales data:

<img width="1393" alt="Screen Shot 2023-05-28 at 4 13 33 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/25e1b65f-8a81-4d5c-a532-150826e1297c">

* Create a temporary table for the parquet data:

<img width="1398" alt="Screen Shot 2023-05-28 at 4 16 28 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/91d11d45-9e33-4f04-b20e-7da3d3885dc3">

* The "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places--PARTITIONED PARQUET DATA:

<img width="1398" alt="Screen Shot 2023-05-28 at 4 20 53 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/cc81810c-b516-454d-ae10-81d5f8c59dfe">

Uncache the home_sales temporary table and verify that the home_sales temporary table is uncached using PySpark:

<img width="1396" alt="Screen Shot 2023-05-28 at 4 23 34 PM" src="https://github.com/therahgithub/Home_Sales/assets/119986667/f29d0f55-ba09-44c6-bda6-1135a06dfa5d">
