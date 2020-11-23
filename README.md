# Project Scope
This project aims to use Machine Learning Technique to uncover the survival rate of passangers in the Titanic using specific features in the Titinic Data Frame.

# Data
Our data set comes from the "Titanic: Machine Learning from Disaster" https://www.kaggle.com/c/titanic where the entire data can be downloaded.

# Libraries
1.Pandas
2.Numpy
3.Matplotlib
4.Seaborn
5.Scikit-learn

# Exploratory Data Analysis (EDA)
There are several features present in this data frame:

1- We have a passangerID colmun (Survived) with the values of 0, if they did not survive or 1, if they did survive.

2- Another inportant variable is the Passanger Class (PClass) which is classified as either 1,2 or 3 depending on which class the passangers belonged.

4- Name and Sex for the name and gender of the passangers.

5- The Age for each passanger. In some cases we do have missing calues which we'll address in subsequent steps of our analysis.

6- SibSp, which correponds to the number of Siblings or Spouces aboard.

7- The Parch indicate the number of parents and children aboard.

8- Ticket number for each passenger

9- Fare, corresponding to the monetary value a given passenger paid for the ticket.

10- Cabin which reflects the assigned cabin for each passenger for the durantion of the trip.

11- Embark: this is the port the passangers boarded the Titanic Ship. The values are "S" for Southampton, C for Cherbourg and Q for Queenstown


## Data Visualization

![](https://github.com/vimpicode/Machine-Learning-with-Python/blob/main/1.png)

![](https://github.com/vimpicode/Machine-Learning-with-Python/blob/main/2.png)




## Data Cleaning

Performed data cleaning for the "Age" variable using Imputation.
Dropped the "Cabin" column since it had too many missing values.
Dropped the "ticket" and "name" columns since they are not particularly relevant to our analysis.

## Summary Statistics of the new data set


# Model Building

1-Split the data into train and test
2-Created a Logistic Regression using Logistic Regression using sklearn.linear_model.
3-Fit the Model
3-Model Evaluation


# Conclusion

Conclusion

The model can be improved by using the entire data set instead of a portion of the data set only. We can also increase our Precision and Recall Accuracy. This can be done by using the entire training set and compare it to test set, instead of splitting our train set into both train and test. Another alternative to improve our model is to use feature engineering by taking the title of the passangers names and use that as a feature, such as Dr. Mrs. Mr etct. Perhaps the cabing letter can also be a feature. The Ticket can also be explored for any possible feature engineering

 
# References

Kaggle Database : https://www.kaggle.com/c/titanic

"Understanding Logistic Regression" by Sarang Narklede https://towardsdatascience.com/understanding-logistic-regression-9b02c2aec102

"Logistic Regression Explained" by Jaime  Zornoza https://towardsdatascience.com/logistic-regression-explained-9ee73cede081

"7 Ways to Handle Missing Values in Machine Learning" by Satyam Kumar https://towardsdatascience.com/7-ways-to-handle-missing-values-in-machine-learning-1a6326adf79e


