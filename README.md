# Prices-prediction-system

This project is about predicting the house prices based on some data we have like Lot Area, Year built, Area, Number of rooms and so on. This project does the Exploratory data analysis (EDA), integrate MLOps Practices using ZenML, MLFlow. Also, implements CI/CD pipelines to automate testing, deployement of model. 


# Data

We have a data file (csv format) of above said features. The data file is uploaded here ()

# Data Exploring

- Step-1: Data Exploring

Initially, data exploring is done, where some functions are defined to know summary statistics for both numerical and categorical features.

- Step-2: Missing value analysis

This handles the missing values: data has significant, moderate and single missing values. These are dealt accordingly either filling with mean or mode, impute missing values with placeholder or drop the columns

- Step-3: Handling outliers

Potential outliers are found in some features. These needs to be detected to avoid skewing model predictions.

- Step-4: Feature engineering

Correlation analysis need to be found among the features. 

# Model Building

After proper data analysis, important features has been found and a Linear Regression model is chosen to train and predict the house prices. MLFlow is used to track the metrics of training

# Deployement

ZenML is used for deployement. 





