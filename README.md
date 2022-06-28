# Amazon_Vine_Analysis
### Overview

The purpose of the analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. In order to complete this analysis, a subset of data that pertained to the video game (M16-Amazon) subcategory of Amazon was used; an i preformed an ETL on this data with the use of AWS, Google Colaboratory, PostgreSQL, and PySpark. after amalysing this data it was inspected for  positivity bias for reviews in the Vine Program.

### Results
How many Vine reviews and non-Vine reviews were there?
There were a total of of 4,291 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset.

<img width="1406" alt="98488023-cbceda00-21f4-11eb-8f84-271b002ea5af" src="https://user-images.githubusercontent.com/100738128/176084098-086f38bf-51a8-44ae-9c45-e767632da0e6.png">

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
In the data set their was a total of 15,711 5-star reviews
15,663 of the 5-star reviews were non-vine


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
38.2% of the five_star reviews were vine
38.9% of the five_star reviews were non-vine

<img width="1361" alt="98488026-cec9ca80-21f4-11eb-96ee-4aad73f98509" src="https://user-images.githubusercontent.com/100738128/176084230-076b535d-f687-4479-9231-cfe88be50916.png">


### Summary 

After analyzing the results, I would conclude that there is a positive bias for reviews in the Vine program. It is essential to note that while the non-vine sample size was very large, the vine sample size was less than 100 entries. In addition to the current analysis, I the percentage of those who purchased the product  through the verified_purchase column either confirm or fail to confirm if there is a positivity bias for reviews in the Vine program.
