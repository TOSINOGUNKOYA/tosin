# tosin
### tosin
````sql      SELECT category,
      (SELECT AVG(sales) FROM `sample-superstore-complete`) AS Overall_avg,
      SELECT ROUND(SUM(sales),2) FROM `sample-superstore-complete`) AS overall_total_sales,
      SELECT ROUND(SUM(sales),2) FROM `sample-superstore-complete
````
