# Amazon_Vine_Analysis

## Overview of the Analysis
The purpose of this project is to analyze Amazon reviews written by members of the Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.

In this projects, I used the dataset from [amazon_reviews_us_Mobile_Apps](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Mobile_Apps_v1_00.tsv.gz). I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results
How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


## Summary
state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

