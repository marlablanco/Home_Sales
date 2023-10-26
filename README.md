# Home_Sales

## Summary
SparkSQL is used to determine key metrics about home sales data. Spark is then used to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached. The runtimes of the uncached, cached, and parquet data is compared. 

### Questions Answered with SparkSQL:
- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

  <img width="179" alt="Screenshot 2023-10-25 at 5 19 45 PM" src="https://github.com/marlablanco/Home_Sales/assets/131930449/f611e03c-40cb-43fd-96e3-96f39e07e48d">

- What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
  
<img width="230" alt="Screenshot 2023-10-25 at 5 20 17 PM" src="https://github.com/marlablanco/Home_Sales/assets/131930449/1c18acb3-5932-4864-80d1-9c20b601ab7b">

  
- What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
  
<img width="228" alt="Screenshot 2023-10-25 at 5 20 51 PM" src="https://github.com/marlablanco/Home_Sales/assets/131930449/c7703ac1-95c4-4f66-81f4-99dc071591e9">

  
- What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

<img width="250" alt="Screenshot 2023-10-25 at 5 21 17 PM" src="https://github.com/marlablanco/Home_Sales/assets/131930449/77701987-c8fd-472a-a2ab-283a530454d8">

### Cached Data Runtime 

<img width="263" alt="Screenshot 2023-10-25 at 5 23 01 PM" src="https://github.com/marlablanco/Home_Sales/assets/131930449/9a2fe57e-ebcc-4bb5-8239-6ce99e313f10">

### Parquet Data Runtime 

<img width="251" alt="Screenshot 2023-10-25 at 5 23 58 PM" src="https://github.com/marlablanco/Home_Sales/assets/131930449/0221f81f-f065-42a0-835c-f4559106e1cb">




