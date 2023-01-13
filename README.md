# **Amazon Vine Analysis** 

## **Overview:** 
### Amazon is the world'd number 1 e-commerce marketplace, with over 6.3 million sellers. In order to give visibility to smaller vendors, Amazon created the Vine program, which allows sellers to offer free products to customers in exchange for thoughtful reviews. 
### Unfortunately, some people have questioned whether individuals who receive free products are less likely to write honest reviews. This project was performed to assess Amazon Vine reviews of digital video games and determine if incentivized reviews are more likely to be favorably biased. 
### We used PGAdmin, Google Colab and PySpark to analyze data from Amazon Vine reviews.

## **Results:** 

### There were a total of 145,431 reviews of products in the entire database of digital video games. 
![Full database](https://github.com/elissewright/Amazon_Vine_Analysis/blob/main/images/total_reviews.png)

### The set was restricted to rows where the total vote count was equal to or exceeded 20, and then further restricted to rows where the number of helpful_votes divided by total_votes was equal to or greater than 50%.

### Of a total of 1,685 restricted reviews, there were zero paid reviews with ratings of 5-stars (0%), and 631 unpaid 5-star ratings(100%). 
![Vine reviews](https://github.com/elissewright/Amazon_Vine_Analysis/blob/main/images/vine_reviews.png)

## **Summary:** 
### The results of this analysis for digital video games suggests that there is not only no evidence for biased incentivized reviews, but that the opposite is true for this category, and unpaid reviewers were far more likely to give 5-star reviews. 
### These unexpected findings may be unique to this specific category of products, which may be an outlier compared to other product categories. 
### In order to further evaluate whether paid reviews may be biased, we should evaluate several other sets of data from various Amazon product categories, obtaining summary statistics for each category, as well as from averaging them together. 
