# Credit_Card_Fraud_Detection

## Utilized Tools & Modules

*   Python3
*   Data Analysis - Pandas | Numpy | Matplotlib | Seaborn
*   Anomaly Detection Techniques - 
    * Isolation Forest
    * Local Outlier Factor
*   Deep Learning Techniques - 
    * AutoEncoder
    * CNN
# Dataset
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features are converted into PCA features - V1, V2, … V28. The only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
The data set can be found at https://www.kaggle.com/mlg-ulb/creditcardfraud

# Result
On this extremely unbalanced dataset, anomaly detection methods such as Isolation Forest and Local Outlier Factor performed poorly. This dataset demonstrated the effectiveness of Deep Learning approaches such as AutoEncoders with the Logistic Regression Model and a Convolution Neural Network model.

# Credit-card-fraud-detection
