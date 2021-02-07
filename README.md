# Amazon_Vine_Analysis
An analysis of product reviews by Amazon Vine service for our client SellBy

## Objective:
The purpose of this project is to analyze a dataset of product reviews provided by Amazon Vine for the intent of discovering bias in the Vine vs non_Vine reviews. 

### Technologies:
This project will use the cloud ETL process with the following technologies: PySpark, and pgAdmin using AWS RDS and Google Collab.

## Results: 
1. Total number of reviews with total votes over 20 are 40,815. The number of 5-star reviews are 20,068.

2. How many Vine reviews were 5 stars? There were 55 5-star reviews by paid Vine reviewers. 

3. 19,736 5-star reviews are from unpaid reviewers.

4. Only .27% of all 5-star reviews came from paid Vine reviewers. While 98% of all 5-star reviews came from unpaid reviewers.

## Summary: 
There is a bias by paid Vine reviewers against providing 5-star reviews. And a bias by unpaid reviewers for 5-star reviews at 98%. 

To further understand these dramatically different trends we can further examine if paid Vine reviewers are more likely to provide 4-star, 3-star, 2-star or 1-star reviews. We could then postulate that being paid makes the reviewer more discerning. This hypothisis may be proven with NLP to look for negative words in the reviews themselves compared to unpaid reviewers.

