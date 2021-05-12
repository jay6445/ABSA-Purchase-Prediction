# ABSA-Purchase-Prediction

ABSA bank sales team is looking for insights for making informed decisions for marketing their array of investment products which include bonds, stocks, and derivatives. There are time and budget constraints on marketing the products that will allow only potential customers to be contacted for a successful purchase. As a marketing analyst, a dataset of past customer records ‘Market.csv’ has been provided for analysis of various trends and insights supporting successful purchases. Another file ‘Market_pred.csv’ has been provided that consists of the customers for which the purchase predictions need to be made. These predictions will help the sales team contact only those who have higher chances of purchasing the investment products.

The initial part of the project consists of exploratory analysis which is eyeballing of the available data to understand the types of variables present. The dataset is also checked for missing and null values such that a clean dataset is available for further analysis. The descriptive analysis involves detecting and studying various patterns and trends by observing the distribution of features of the dataset using descriptive statistics and visualizations using graphs. The dataset is then prepared for predictive analytics for which it is randomly divided into training a testing dataset. Based on the exploratory and descriptive analysis, it is assumed to be a classification problem for which the following machine learning models are considered

1. Classification and Regression Tree (CART)
2. C5.0
3. Random Forest
4. Naïve Bayes 
5. Support Vector Machine (SVM)

The above models are trained, tested, and evaluated using the parameters like accuracy, precision, false positives, and false negatives. k-fold cross-validation is used to eliminate biases or overfitting if present in the dataset used to test the models. The suitable classification model is then used to predict the purchase decisions of customers present in 'Market_pred.csv'.
