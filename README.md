# House Prices Prediction System

This project focuses on predicting the house prices using structured data such as Lot Area, Year built, Area, Number of rooms and more. It covers the full machine learning lifecycle including Exploratory Data Analysis (EDA), model development, and deployment. The project also integrates MLOps practices using ZenML and MLflow , and implements CI/CD pipelines to automate testing and deployment processes.



# 📁 Data

We have a data file (csv format) of above said features. The data file is uploaded [here](https://github.com/venkatchandu848/House-Prices-prediction-system/tree/main/data)

# Data Exploring

Step-1: Data Exploring

Initially, data exploring is done to understand the structure of data, where some custom functions are defined to know summary statistics for both numerical and categorical features.

Step-2: Missing value analysis

Missing values ​​are handled based on their severity:

- High missingness : Columns are dropped if missing data is excessive.

- Moderate/single missingness : Missing values ​​are imputed using mean, mode or placeholders.

Step-3: Handling outliers

Outliers are identified using statistical techniques to prevent skewed model training and ensure robust predictions.

Step-4: Feature engineering

Correlation analysis is conducted to identify relationships between features and the target variable, redundant ones found and removed based on insights.

# 🤖 Model Building

After proper data analysis, important features have been found and a Linear Regression model is chosen to train on selected features, its performance metrics are tracked and logged using MLFlow

# Deployement

Deployment is handled using ZenML , which manages the ML pipeline, including data preprocessing, model training, evaluation, and deployment stages.




