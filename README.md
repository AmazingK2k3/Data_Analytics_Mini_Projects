# Mini Data Analytics Projects

This repository contains a collection of mini data analytics projects, each focusing on a specific problem and dataset. The projects follow a standard pipeline implementation, including data loading, cleaning, preprocessing, feature engineering and selection, model building, testing, and evaluation.

Each file in this repository corresponds to a specific project. Below is a description of the projects included:

---

## Retail Analytics Case Study
**Description**: This project primarily involves analysis of weekly sales of different store types. Primarily an EDA project, it seeks to understand the data and come up with preliminary insights.
**Dataset**: Within the Folder
**Algorithms/Models Used**: Classical EDA approaches, including data preprocessing, correlation analysis etc.
**Insights**: Insights from the EDA are documented at the end of ipynb. The lesson learnt is to have a more nuanced and thought-oriented eda rather than just applying and testing correlation.

---

## Cybersecurity Threat Classification
**Description**: A machine learning-based approach to classify network traffic as normal or a potential cyber threat for network flow-based dataset.
**Dataset**: UNSWB-NB15
**Algorithms/Models Used**: Random Forest, Light GBM, XG Boost, Decision Trees, Logistic Regression
**Insights**: Random Forest turned out to be the top-performing model with F1-score of 0.76 on test data.

---

## Intrusion Detection using Isolation Forest
**Description**: An anomaly detection system to identify malicious activities in network data using the Isolation Forest algorithm.  
**Dataset**: Mentioned within all-data
**Algorithms/Models Used**: Isolation Forest, Random Forest
**Insights**: yielded an F1-score of 0.55 on Isolation forest and 0.73 on Random forest algorithm while more finetuning is required.


---

## Link Utilization and Forecasting
**Description**: Time series analysis to predict network link utilization and bandwidth requirements.  
**Dataset**: Linkstats.csv file 
**Algorithms/Models Used**: ARIMA, Exponential Smoothing, and other forecasting models  
**Insights**: Just a good exercise to explore classical time series algorithms and the possible use of LSTMS.

---

## MNIST Classical Classification
**Description**: A traditional machine learning approach to classify handwritten digits from the MNIST dataset.  
**Dataset**: MNIST  
**Algorithms/Models Used**: Logistic Regression, SVM, K-Nearest Neighbours
**Insights**: Good approach and understanding of using classical ML algorithms on image-related problems and datasets.

---

## MovieLens Recommendation System
**Description**: A recommendation system built using collaborative filtering techniques to suggest movies to users based on past interactions.  
**Dataset**: MovieLens Belief 2024
**Algorithms/Models Used**: Collaborative Filtering - SVD ,KNN
**Insights**: I just applied a few classical algorithms, the idea is to expand into a large-scale recommendation system.

---

## Network Traffic Classification
**Description**: Classification of network traffic into categories based on protocol and activity
**Dataset**: *[Specify Dataset Name]*  
**Algorithms/Models Used**: Just a classical EDA approach towards classifying based on protocol etc

---

## Predicting House Prices
**Description**: A regression problem to predict house prices based on various features such as location, size, and amenities. As a practice file for implementing a full-scale datascience related pipeline. 
**Dataset**: Kaggle California Housing dataset 
**Algorithms/Models Used**: Linear Regression, Random Forest, XGBoost, LightGBM etc.

---

## Stock Prices Forecasting
**Description**: Time series forecasting to predict stock prices based on historical data.  
**Dataset**: Yfinance - Stocks
**Algorithms/Models Used**: ARIMA, LSTM, etc.  


## Additional Files
- **linkstats.csv**: A sample dataset used in the `Link Utilization and Forecasting` project.
- **all_data**: Folder contains the data required for running all the other mini projects.


