# Supervised-ML-Classification
This rpository contains a machine learning classification model developed to classify price of mobile based on historical data.

**PROBLEM STATEMENT**

In the competitive mobile phone market, companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is ?

**Project Summary:**

This project aims to develop a machine learning model that can predict the price range of a mobile phone based on its specifications and features. The project utilizes a dataset containing information about various mobile phones, including their prices, brands, RAM, internal memory, screen size, and other features.

**Data Preprocessing:**

1. **Data Cleaning:** The dataset is cleaned by removing any missing or irrelevant data points.
2. **Feature Engineering:** Additional features are extracted from the existing features, such as the screen size category (small, medium, large) based on the screen size in inches.
3. **Data Transformation:** Categorical features like brand and screen size category are encoded using one-hot encoding to convert them into numerical features suitable for machine learning algorithms.

**Model Training and Evaluation:**

1. **Model Selection:** Various machine learning classification algorithms like Decision Tree, Random Forest, and XGBoost are trained and evaluated on the preprocessed dataset.
2. **Hyperparameter Tuning:** The hyperparameters of each model are tuned to optimize their performance.
3. **Model Evaluation:** The performance of each model is evaluated using metrics like accuracy, precision, recall, and F1-score.

**Results:**

The XGBoost model achieved the best performance with an accuracy of 81%. The model was able to accurately predict the price range of a mobile phone based on its specifications and features.

**Conclusion:**

This project demonstrates the successful development of a machine learning model for predicting the price range of mobile phones. The model can be used by consumers to compare different mobile phones and make informed purchasing decisions.
