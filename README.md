# Amazon_Vine_Analysis

The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and 
publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. PySpark was used to perform the 
ETL process to extract the dataset, massage it and connect it to an AWS RDS instance. The newly transformed data was then loaded to pgAdmin for further review.

## Results of our analysis:

How many Vine reviews and non-Vine reviews were there?
   
 Total number of Paid
 ![image](https://github.com/DmanDJs1/Amazon_Vine_Analysis/blob/main/resources/Paid_total_number_of_reviews.png?raw=true)


Total number of unpaid

 ![image](https://github.com/DmanDJs1/Amazon_Vine_Analysis/blob/main/resources/unpaid_total_number_of_reviews.png?raw=true)	 


How many Vine reviews were 5 stars? 
 ![image](https://github.com/DmanDJs1/Amazon_Vine_Analysis/blob/main/resources/Paid_5_star_reviews.png?raw=true)


How many non-Vine reviews were 5 stars?
 ![image](https://github.com/DmanDJs1/Amazon_Vine_Analysis/blob/main/resources/unpaid_5_star_reviews.png?raw=true)



What percentage of Vine reviews were 5 stars? 
 ![image](https://github.com/DmanDJs1/Amazon_Vine_Analysis/blob/main/resources/Paid_5_star_reviews%20%25.png?raw=true)


What percentage of non-Vine reviews were 5 stars?
 ![image](https://github.com/DmanDJs1/Amazon_Vine_Analysis/blob/main/resources/unpaid_5_star_reviews%20%25.png?raw=true)


##Summary
----------------------------------------------------------

According to the analysis of the dataset, more than half of the reviews in the program were 5 star at 51%. 
The percentage of the unpaid non vine reviews were lower at 39%. 
This demonstrates a positive bias towards the reviews in the vine review program.

An additional analysis can be conducted to determine the mean, median and mode (statistical distribution) 
of rating for both the paid and non-paid reviews
