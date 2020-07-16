# Classification_Logistic_regression_churnData_python
## problem definition
A telecommunications company is concerned about the number of customers leaving their business for competitors. They need to understand who is leaving. we want to find out who is leaving and why. we will create a model for a telecommunication company, to predict when its customers will leave for a competitor, so that they can take some action to retain the customers.
## Dataset
This data set provides information to help you predict what behavior will help to retain customers.
The dataset includes information about:
Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they had been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents
## libraries
- pandas
- numpy
- scikit learn
- matplotlib
## language programming
python
##  evaluation methods
- Jaccard index
- confusion matrix
- log loss
## plot
non-normalized confusion matrix

![1](https://user-images.githubusercontent.com/56628918/87706698-3a98ab00-c7a0-11ea-9170-d421c915d8b2.png)

## conclusion
After preprocessing and exploratory data , we used logistic regressin with optimizer 'liblinear' and regularization inverse C equal to 0.01 to creat model , then evaluated model with jaccard index confusion matrix and log loss.Jaccard index told us predicted values are 72 percent similar to real values in data set , average f1-score in confusion matrix tells us this model 68 percent can predict correctly.

