# Customer Lifetime Value Prediction using K-Means Clustering on Online Retail Dataset

This project aims to predict the Customer Lifetime Value (CLTV) using K-Means Clustering on the Online Retail Dataset available on Kaggle.


## Project Overview

CLTV is a metric that helps companies determine the total amount of money a customer is expected to spend on their products or services throughout their lifetime. This project will use K-Means clustering algorithm to segment customers based on their buying behaviour and predict the CLTV of each segment.


## Dataset

The Online Retail Dataset contains 541,909 transactions made by customers of an online retail store based in the UK from 2009 to 2011. The dataset has the following attributes:



* InvoiceNo: Unique identifier of each transaction
* StockCode: Unique identifier of each product
* Description: Description of each product
* Quantity: Number of products purchased in each transaction
* InvoiceDate: Date and time of each transaction
* UnitPrice: Price of each product
* CustomerID: Unique identifier of each customer
* Country: Country of each customer

The dataset can be downloaded from[ Kaggle](https://www.kaggle.com/carrie1/ecommerce-data).


## Requirements

The project is implemented in Python 3.x using the following libraries:



* pandas
* numpy
* scikit-learn
* seaborn
* matplotlib

To install the required libraries, run the following command:

bash

Copy code

pip install pandas numpy scikit-learn seaborn matplotlib


## Project Structure

The project has the following structure:

* data: Contains the Online Retail dataset in CSV and ZIP format.
* notebooks: Contains the Jupyter notebooks used in the project.
    * data_exploration.ipynb explores the dataset and visualises the data distribution.
    * data_preprocessing.ipynb preprocesses the dataset for modeling.
    * cltv_prediction.ipynb implements K-Means clustering and predicts the CLTV of each customer segment.
* src: Contains the Python script for CLTV prediction.
* README.md: This file.
* requirements.txt: Contains the list of required libraries.


## Usage

To run the project, follow these steps:



1. Install the required libraries
2. Download the Online Retail dataset from[ Kaggle](https://www.kaggle.com/carrie1/ecommerce-data) and place it in the data directory.
3. Run the cltv_prediction.ipynb notebook to predict the CLTV of each customer segment.


## License

This project is licensed under the MIT License - see the LICENCE file for details.
