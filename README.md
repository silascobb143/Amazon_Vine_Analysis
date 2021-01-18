# Amazon_Vine_Analysis

# Overview of the analysis:
We were tasked to pick one of the datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

# Results: 
For this assignment I endend up using "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz" from AWS.

How many Vine reviews and non-Vine reviews were there?
* In our review there were a total of 334 paid reviews and 61,614 that were not paid.

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* Of those reviews we had 139 paid with 5 stars.  For the not paid 5 stars there were 32,665 reviews.

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
* The percentages breakdown of paid 5 star was 41.6% and the 5 start not paid was 53%.

# Summary: 

* You can clearly see after running this review that there is a much high percentage of unpaid 5 star reviews compared to that of the 5 star paid reviews.  Along with there being a high percentage of 5 star reviews being unpaid there is a much high number of total reviews being unpaid.

* One additional analysis that you could do with the dataset is finding out what our average review rating is.  In this case we only focused on the 5 star reviews but we have a lot more data to pull from is we were to use all of the star ratings.
