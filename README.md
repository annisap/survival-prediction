# Supervised Prediction Model for Titanic Survivals
##### Binary Classification

Titanic survivals occured by chance? Or were they applied the well known "survival of the fittest"?
The goal of this project is to reveal what features affect the outcome of survival.
We learn these patterns on test data, predict survival on test data, and evaluate the prediction accuracy of our model.

## Dataset Used
[Titanic Prediction](http://www.kaggle.com/c/titanic-gettingStarted/data) :This data set corresponds to a set of anonymized records associated with passengers' travelling details and individual data. 

## Data description

Variable of interest:
0. Survival - Survival (0 = No; 1 = Yes). Not included in test.csv file.
Predictors:
1. Pclass - Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
2. Name - Name
3. Sex - Sex
4. Age - Age
5. Sibsp - Number of Siblings/Spouses Aboard
6. Parch - Number of Parents/Children Aboard
7. Ticket - Ticket Number
8. Fare - Passenger Fare
9. Cabin - Cabin
10. Embarked - Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## The better the question the better the answer:

"Use the Machine Learning Workflow to process and transform the titanic dataset to create a prediction model. This model must predict which passengers are likely to survive from the titanic sank with 90% or greater accuracy."

## Analysis Process

1. Exploring data distributions
2. Preparing data for machine learning
3. Feature Selection
4. Training a logistic regression model, a decision tree and a random forest model
5. Try different subsets of features
6. Measuring the accuracy of your model


## Requirements
To run the project, it is required that the following are installed in your system:

- [anaconda](https://docs.continuum.io/anaconda/navigator)
- [Pyhton](https://www.python.org/download/releases/2.7/) version: "^2.7"
- [NumPy](http://www.numpy.org/) version: "^1.11.3"
- [Matplotlib](https://matplotlib.org/) version: "^2.02"
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/install.html) version: "^0.20.1"
- [scikit-learn](http://scikit-learn.org/stable/install.html) version: "^0.18.1"
