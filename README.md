# EV_Charging_Time_Prediction_Using_XGBoost

Exploratory Data Analysis (EDA) is conducted at the initial stage to understand the dataset structure, examine variable distributions, identify missing data, and analyze descriptive statistics. In the given code example, the EDA step involves displaying dataset information and descriptive statistics using the `df.info()` and `df.describe()` methods. This analysis helps to gain initial insights into the data being used.

Prediction is performed after going through the EDA and data preprocessing stages. In this stage, an XGBoost model is trained using the training data, which is a subset of the dataset with selected features. After training the model, the prediction step is carried out using the trained model to predict the charging time on the test data. Predictions are made using the `predict()` method from the trained model.

Thus, the analysis aims to understand the dataset and its characteristics, while the prediction aims to utilize the trained model to predict the charging time based on the available features.
