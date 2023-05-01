# Product-Analytics-Recommendation

Problem Statement: The aim of this project is to improve the product conversion rate and performance.Many Startups are struggling with low sales and revenue despite having a high number of Website and App visitors.

Regression methods were applied to determine the number of purchases, but the linear regression model produced poor results.

Because the dataset contains more zeros, the Poisson regression model results in an infinite mape value.

To solve this problem, we employed zero-inflated Poisson (ZIP) and zero-inflated negative binomial (ZINB), giving a mape value of 0.010%.

For Multi-class classification to classify the customer based on their purchase frequency with bagging classifier giving better results with weighted f1 score is 0.92

To calculate the estimated number of banner shows to customers, ZIP and ZINB models with MAPE is 2.06% were used.

Performed Mini batch k-mean clustering for retargeting the products to customers.
