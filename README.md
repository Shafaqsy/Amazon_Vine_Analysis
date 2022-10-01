# Amazon_Vine_Analysis
## Purpose
The purpose of this analysis is to analyzing Amazon reviews written by members of the paid Amazon Vine program. I chose the amazon video games reviews for thsi project. I use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Also, I use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.
## Summary
### Results from deliverable 1
#### Customer Table

![customer_table1](https://user-images.githubusercontent.com/107155888/193355987-3db68fc4-1535-47e8-bd2b-7a39545a5f76.png)

#### Products Table
![products_table](https://user-images.githubusercontent.com/107155888/193356002-bcb361a4-5321-4e30-93c5-30af7f5ac861.png)

#### Review ID Table
![review_id_table](https://user-images.githubusercontent.com/107155888/193356013-9358dfef-84b2-4104-9dc2-79da37f5744b.png)

#### Vine Table

![vine_table](https://user-images.githubusercontent.com/107155888/193356026-fdfae1f1-5566-44af-b4a8-ef8e949c4054.png)

### Results from deliverable 2
paid vine reviews = 94

unpaid vine reviews = 40471

paid five star vine reviews = 48

unpaid five star vine reviews = 15663

percentage of paid  five star vine reviews = 51.06382978723404 = 51.1 %

percentage of unpaid five star vine reviews = 38.701786464381904 = 38.7%



<img width="722" alt="vine_reviews" src="https://user-images.githubusercontent.com/107155888/193358051-448c2ae8-7c49-4c67-9fde-39de49098348.png">

##Summary

There's only 48 paid reviews and 51.1% of people has given five star reviews for paid vine program. I don't think there's a positive bias and people are not happy with the paid vine program because there is only few people who have given reviews and only half of it has given five star reviews. 
I would recomend an additional analysis for both paid and unpaid program. We can calculate the mean of star rating cloumn for better conclusion.
