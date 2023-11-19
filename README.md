# credit-card-model-pyspark

# Dataset 
 Dataset contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Id - A unique Id for each row.
Time - Number of seconds elapsed between this transaction and the first transaction in the dataset
V1-V28 - Features after dimensionality reduction to protect user identities and sensitive features
Amount - Transaction amount
Class - Target Class (1 for fraudulent transactions, 0 genuine)

Dataset is having total 284807 data points

# Purpose
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase

# Objective
Identify the features which influence fraud credit card transaction
Predicting fraud credit card transaction using different ML algorithm
Compare the different ML model using different factors and choose the choose the best algorithm
