# Retail-Sales-Prediction-Regression-Model

# Introduction:
### Retail sales is the sale of consumer goods, or final goods, by businesses to end consumers and includes in-store sales as well as online sales. Products may be durable (with a significant expected shelf life) or perishable (such as groceries). There are different retail stores in the market. They are specialty stores, department stores, supermarkets, convenience stores, and discount stores. This study is related to the sales of drug stores in European countries. These sales depend on state holiday, school holiday, day of the week and competition distance, etc.

![Retail-Sales](https://user-images.githubusercontent.com/99146783/183277303-4034577c-e72a-4903-8327-8c6bfeaa520d.jpg)


# Problem Staement:
### Look at the given datasets and study the relationship between different features or trends in different features. Find the correlation between sales and other features and build an efficient machine learning model to predict future sales for given input variables. Rossmann operates over 3,000 drug stores in seven European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Many factors influence store sales, including promotions, competition, school and state holidays, seasonality, and location. With thousands of individual managers forecasting sales based on their specific circumstances, the accuracy of the results can vary greatly. We are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the sales column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

# Approach:
### We concatenated the two data sets Rossmann and Stores data to get more information about sales. We did replace null values with appropriate values like median and mode of that particular feature values. We had done univariate analysis and bivariate analysis for good understanding of the data. We converted categorical features into numerical features by using one hot encoding technique. Then we removed the features showing multicollinearity nature (removed features having VIF value more than ten). We did split the data set into train and test. We trained different algorithms using train data set. We tested algorithms like Linear Regression, Lasso, Ridge, Elastic-Net and Decision Tree Regression. We find that among these five algorithms, Decision Tree Regression giving good results.
# Conclusions:
1. From correlation matrix, we can say that 'Customers' feature is highly correlated to Sales (dependent Variable).
2. The 'Month' feature was removed instead of week of year because these both features were correlated and 'Month' is less correlated with 'Sales' compared to later one.
3. In linear regression, Customers is the most influencing feature and State Holiday is at the second place.
4. In Decision Tree Regressor, Customers is the most influencing feature and Competition Distance is at the second place.
5. We find that among these five algorithms, Decision Tree Regression giving good results
