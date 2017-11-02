# Credit-Card-Fraud-Detection-Project
## What is credit card fraud
Credit card fraud is a wide-ranging term for theft and fraud committed using or involving a payment card,<br>
such as a credit card or debit card, as a fraudulent source of funds in a transaction. It is of importance<br>
to detect such fraud via some novel methods. Here we will apply several `machine learning algorithms` to make prediction.<br>

## Dataset
The datasets(creditcard.csv) contains transactions made by credit cards in September 2013 by european cardholders.<br> 
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.<br> 
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.<br>

## Key Results
I want test Logistic Regression on skewed data. I also apply cross validation for hyperparameter tuning<br>
different classification models. My model is offering an 94% recall accuracy on the test data.<br>
* Recall = True Positive/(True Positive+False Negative)
<div align=center><img width="400" height="350" src="https://github.com/songloveai/Credit-Card-Fraud-Detection-Project/blob/master/figures/Recall.png"/></div><br>
<div align=center>The Confusion Matrix of the Logistic Regression model</div><br>
You can see all the codes in the jupyter notebook.<br>

## Certification
