# Amazon_Vine_Analysis

## Objective

  Goal of the project is to anlayze amazon reviews program (Vine) to anlayze if there is any bias towards favorable reviews. 
  To execute the project, used pySpark to run the ETL process to extract, transform and load into AWS RDS and pgadmin instance. Further, anlaysed the data to answer key questions and provide insights.
  
## Results

### Total Reviews split by vine and non-vine

* Vine Reviews

![](https://github.com/SuniAnalytics/Amazon_Vine_Analysis/blob/main/Resources/1.%20Paid.png)

* Non-Vine Reviews

![](https://github.com/SuniAnalytics/Amazon_Vine_Analysis/blob/main/Resources/3.%20Unpaid%20Reviews.png)

### 5 Star Reviews

* Number of 5 star vine reviews

![](https://github.com/SuniAnalytics/Amazon_Vine_Analysis/blob/main/Resources/2.%205%20Star%20Review.png)

* Number of 5 star non-vine reviews

![](https://github.com/SuniAnalytics/Amazon_Vine_Analysis/blob/main/Resources/6.%20Unpaid%205Star.png)

### Percentages

* % of 5 star vine reviews

![](https://github.com/SuniAnalytics/Amazon_Vine_Analysis/blob/main/Resources/4.%205Star%20%25.png)

* % of 5 star non-vine reviews

![](https://github.com/SuniAnalytics/Amazon_Vine_Analysis/blob/main/Resources/5.%20Unpaid%20%25.png)

## Summary

Based on the analysis, 51% of reviews from vine program were 5 stars. This is 12% higher than 5 star non-vine reviews (39%). This clearly infers a strong positive bias by reviews in vine program.

To determine the bias, we could anlalyse the shopping categories using a linear regression model to statistically analyse and determine the bias of 5 star reviews by paid vs non-paid reviews.


