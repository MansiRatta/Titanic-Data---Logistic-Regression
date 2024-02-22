Titanic Data- Logistic Regression 

This repository contains the code for a logistic regression analysis on the Titanic dataset. The dataset provides information about passengers aboard the Titanic, including their demographics and whether they survived or not. The goal of this project is to predict survival based on various features using logistic regression.


Dependencies

Python 3.x
Jupyter Notebook
pandas
NumPy
scikit-learn
matplotlib
seaborn
Dataset

The dataset (titanic_train.csv) contains the following columns:

PassengerId: Unique identifier for each passenger
Survived: Whether the passenger survived (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name: Passenger's name
Sex: Passenger's sex
Age: Passenger's age
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Fare paid for the ticket
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Description

In this project, we have started by performing some EDA using Data visualization libraries like Matplotlib and Seaborn. Through this, we have tried to understand the dependence between variables and the importance of some variables. 
Moving forward, we have converted categorical features to dummy variables using pandas. Otherwise our machine learning algorithm won't be able to directly take in those features as inputs. 
After having all the features ready, we have built the logistic regression model by splitting our data into training and testing data.
In the end, we evaluated our model using the Classification Report to note the precision, recall, f1-score of our model.  

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

This analysis is based on the Titanic dataset available on Kaggle.
Credits to the contributors of scikit-learn, pandas, NumPy, matplotlib, and seaborn for their invaluable tools for data analysis and machine learning.
Feel free to contribute or provide feedback!
