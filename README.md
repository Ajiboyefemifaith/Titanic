# Titanic
This is an analysis to predict the passengers that survived the Titanic shipwreck.

# The Challenge
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

This analysis answers the question “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

# Overview
The data has been split into two groups:

training set (train.csv)
test set (test.csv)
The training set was used to build predictions. For the training set, the outcome was provided which is also known as the “ground truth”) for each passenger. The predictions will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set was used to see how well the predictions performs on unseen data. For the test set, the ground truth for each passenger was not provided. The outcomes have to be predicted. For each passenger in the test set, we will use the insights gotten to predict whether or not they survived the sinking of the Titanic.

A prediction_submission.csv is also included which contains the set of predictions of the survival chances of passengers aboard the Titanic.

# Data Dictionary
Variable	Definition	Key

survival;	Survival	0 = No, 1 = Yes

pclass;	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd

sex;	Sex	

Age;Age in years

sibsp; number of siblings / spouses aboard the Titanic	

parch; number of parents / children aboard the Titanic	

ticket;	Ticket number	

fare;	Passenger fare

cabin;	Cabin number	

embarked;	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

# Variable Notes
pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

# Links

https://www.kaggle.com/c/titanic/data

# Analysis and result

Titanic.ipnyb - Jupyter notebook for analysis.

Test.csv - Excel file containing the names of passengers to predict survival.

Prediction_submission.csv - Result of prediction
