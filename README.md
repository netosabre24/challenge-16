# Amazon Vine Analysis

# Project Purpose
The purpose of this analysis is to gain insights on Amazon reviewers of the vine program and see if there is any positive bias towards them. By using
Google Colab notebooks was used to create tables from this shoe review dataset, then pgAdmin and AWS. This data was stored in an SQL database. From pgAdmin, the vine table was exported, which includes data that shows review rating, helpful votes, total votes, whether the review was a Vine review with purchase verification.

# Results

ASfter creating samples he data was filtered to find reviews with 20 or more votes and more than 50% rating, which resulted in 27,009 reviews. Then broken into the following two datasets, one for only Vine reviews and the other for non-Vine reviews.

![final1](https://user-images.githubusercontent.com/82550431/136620927-392dd79b-ca94-4b64-b176-fe69c8128db9.PNG)

Based from this analysis above, the following was observed; there were 22 Vine reviews and 26,987 non-Vine review, 13 Vine review with 5 stars, compared to 14,475 of non-Vine reviews and 59.1% of Vine reviews were 5 stars, compared to 53.6% of non-Vine reviews

# Summary 
The vine reviews was a bit higher percentage of 5 star reviews than non-Vine reviews (59.1% vs 53.6%). The mean for Vine reviews is 4.36 compared to 3.86 for non-Vine reviews, which showed the vine reviews have a higher average in star ratings.
