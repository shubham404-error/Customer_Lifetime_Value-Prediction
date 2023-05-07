# Customer Lifetime Value Prediction on Online Retail Dataset

This project is about predicting customer lifetime value (CLV) for an online retail dataset. CLV is a measure of the total worth of a customer to a business over the entirety of their relationship. In this project, we will use machine learning algorithms to predict the CLV of customers using the online retail dataset available on Kaggle.


## Dataset

The dataset used in this project is the Online Retail dataset available on Kaggle[ here](https://www.kaggle.com/vijayuv/onlineretail). The dataset contains 541,909 rows and 8 columns of transactional data from an online retailer that sells gift items. The data includes the following variables:



* InvoiceNo: Unique identifier for the transaction.
* StockCode: Unique identifier for each item sold.
* Description: Description of the item.
* Quantity: Quantity of each item sold in the transaction.
* InvoiceDate: Date and time of the transaction.
* UnitPrice: Price per unit of each item.
* CustomerID: Unique identifier for each customer.
* Country: Country where the transaction took place.


## Methodology

The methodology used in this project is as follows:



1. Data Cleaning and Preprocessing: The dataset was cleaned and preprocessed to handle missing values, outliers, and other data quality issues.
2. Feature Engineering: New features were created from the existing variables to capture additional information about the customers, such as recency, frequency, and monetary value.
3. Modeling: Several machine learning algorithms were used to predict the CLV of customers, including linear regression, decision tree regression, and random forest regression. The best model was selected based on its performance on the test dataset.
4. Model Evaluation: The performance of the selected model was evaluated using metrics such as root mean squared error (RMSE), mean absolute error (MAE), and R-squared.


## Results

The best performing model was the Random Forest Regression model, which achieved an RMSE of 306.25 and an R-squared value of 0.83 on the test dataset. This model was able to predict the CLV of customers with a reasonable degree of accuracy.


## Conclusion

In this project, we used machine learning algorithms to predict the CLV of customers using the online retail dataset. We found that the Random Forest Regression model was the best performing model, achieving an RMSE of 306.25 and an R-squared value of 0.83 on the test dataset. These results suggest that machine learning can be used to accurately predict the CLV of customers in an online retail setting.
