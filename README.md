# Customer-Churn-Prediction
Text analytics has been done for this semi supervised learning project to predict whether a mobile phone customer is going to churn or not.

Dataset:
Customers.csv - This file has structured data about customer's information related to his/her age, gender, marital status, car ownership, mobile plans, payment type etc
Comments.csv- The other file has text data of the complaint raised by the customer.


Tasks done in this project:
Find out the total number of stemmed words produced by each 
Construct the term-document matrix

Construct the TF-IDF matrix from the term-document matrix

Combine the TF-IDF matrix with Customer data. Then do one-hot encoding on the categorical variables.

Use filter type and wrapper type to determine the best set of features

Use the best set of features from each method (filter and wrapper), build new classification models and evaluate them on the test data.
