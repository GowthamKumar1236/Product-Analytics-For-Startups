# Product-Analytics-Recommendation

Problem Statement: The objective of this project is to improve the product conversion rate and performance, we plan to use predictive modeling to analyze visitor behavior on website and mobile application.

●	For finding count as a response variable,Bagging regressor is performing well in tree based model with MAPE value is 1.2%

●	Linear regression overfitting if used all variables in a dataset.If used significant variables also,its giving very low r_square value 0.155

●	Poisson Regression might give better results.But due to more zeros in data,It's also not giving better results. So we are experimenting with Negative Binomial Distribution.

●	We are working on Mini Batch K-Means clustering on the products column and the number of customers in order to recommend products to the user.
