# Credit-Card-Fraud-Detection
Credit Card Fraud Detection
Credit card fraud is a serious issue that affects both credit card companies and cardholders. With the increasing number of transactions made online and through mobile apps, the risk of credit card fraud is higher than ever before. In this project, we will use machine learning techniques to detect credit card fraud.

# Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. The dataset has 31 columns, including the amount of the transaction, the time of the transaction, and the class of the transaction (fraudulent or not). The dataset has 284,807 transactions, of which only 492 (0.17%) are fraudulent.

# Requirements
This project requires the following Python libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn


# Project Steps

The following steps are performed in this project:
Load the dataset and perform exploratory data analysis
Check the class balance
Preprocess the data
Train-test split
Build and train a logistic regression model
Evaluate the model
Perform cross-validation
Perform grid search to find the best hyperparameters for the model
Determine feature importance
Visualize the data
Build and train a random forest model
Evaluate the model using a confusion matrix and classification report
Create an ROC curve and calculate the AUC-ROC score
# Conclusion
In this project, we used machine learning techniques to detect credit card fraud. We started by exploring the dataset and checking the class balance. We then preprocessed the data and split it into a training set and a test set. We built and trained a logistic regression model and evaluated its performance. We performed cross-validation and grid search to find the best hyperparameters for the model. We determined feature importance and visualized the data. We then built and trained a random forest model and evaluated its performance using a confusion matrix, classification report, and ROC curve. We calculated the AUC-ROC score to determine the model's performance. Overall, we found that the random forest model had better performance than the logistic regression model. This project demonstrates the importance of using machine learning techniques to detect credit card fraud and the steps involved in building a fraud detection system.
