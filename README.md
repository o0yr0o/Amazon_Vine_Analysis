# Amazon_Vine_Analysis

## Overview of the Analysis
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

The purpose of this project is to analyze Amazon reviews written by members of the Amazon Vine program and determine if there is any bias towards favorable reviews from Vine members.

In this projects, I used the dataset from [amazon_reviews_us_Video_Games](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz). I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results
![image](https://user-images.githubusercontent.com/82549782/129827445-8479ddb0-0ab3-41d5-a485-7a958dd21668.png)
- This dataset contains 40,565 helpful reviews. Among them, 94 are Vine reviews and 40,471 are non-Vine reviews.

![image](https://user-images.githubusercontent.com/82549782/129828550-d2834dd5-0952-4e4e-b2c4-1242546b4582.png)
- There are 15,711 5-star reviews in total, among which there are 48 5-star Vine reviews and 15,663 5-star non-Vine reviews. 

![image](https://user-images.githubusercontent.com/82549782/129829415-2534da41-24f2-493d-aeea-21a6caa73674.png)
- There are 39% Vine reviews were 5 stars, and 51% non-Vine reviews were 5 stars.

## Summary
state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

