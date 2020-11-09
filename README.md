# bank-Machine-Learning-Project
This is Exploratory data Analyst and machine Learning to classify whether customers will exit account or not

### Background
Bank can end the relationship with a customer at any time, just as a customers can move to another bank at any time. A customers could move because of some reason likes a competitor offers a better deal or because of unsatisfactory with the bank.

### Problem
When the customers a bank decided to end the relationship with the bank (or exit account), its could arise some problems for the bank. Bank would lose their customers and having hard time to gain their trust. That was when the bank would has experience loss.

### Goals
In order to know the pattern of customers who will exit their account, this research aims to:
1. Perform **Exploratory Data Analyst** to know the characteristic of customers that exit account
2. Building **Machine Learning** to predict whether a customer will exit account or no

### Results
#### `Exploratory Data Analyst`
- Range age that has highest percentage of exit account from bank is **Lansia Awal (50.57) followed by Lansia Akhir (48.32)**
- Customers who has high balance tend to exit account with percentage around 24.98%
- Germany has the highest percentage of exit account with percentage around 32.44%
- female has higher percentage of Exit Acount around 25.07%
- Customers that is not active member tend to exit account with percentage aroung 26.85%

#### `Machine Learning`
In Building Machine Learning, I used 3 algoritms (Logistic regression, Random forest, Decision Tree). 
- Best Base Model after handling imbalance data using Random Over Sampling is Logistic regression with Recall 0.70
- While after did a Tuning on Decision tree and Random Forest, Tuning random forest has higher recall rather than Decision Tree

### Suggestion
Since I didn't do scaling for Balance and EstimatedSalary features because I used algorithms that base on tree, its would be better to try another algorithms that use distance base likes KNN, SVC etc and did scaling in both of that features.
