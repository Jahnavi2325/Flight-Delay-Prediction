# Flight-Delay-Prediction
Flight delays can disrupt travel plans and impact the aviation industry's efficiency. This project focuses on developing a machine learning model to predict flight delays based on historical flight data and relevant features. By accurately anticipating delays, travelers and stakeholders can make informed decisions and take appropriate actions. This repository contains the code and resources for the Flight Delay Prediction project.

I have collected the dataset from kaggle. 

source link: https://drive.google.com/drive/folders/1-U17SOSSX2crwlWUP1z98Ng42nYuJJOD?usp=sharing

## Explorations

### Exploratory Data Analysis
I have collected the data, cleaned it and performed univariate and Bivariate analysis i.e. analysis of features with target variable to answer some interesting questions on the dataset through visualization.

Data Cleaning : Removal of missing values, Label Encoding, Normalization, Splitting data to train and test datasets.
 

##### Models used:
Logistic Regression is incredibly easy to implement and very efficient to train. 

(Logistic Regression implementation is best instead of Linear Regression because the target variable in the dataset is of type categorical, not continuous. So, my dataset is not suitable for linear regression.)
-> After using logistic regression, I have implemented through decision tree classifier, which did not meet the accuracy of logistic regression.But definitely, both models have shown that they can be very successful in solving classification problems.

Decision Tree Classifier
Support vector Classifier(There is no much difference between support vector classifier without kernel and SVC with kernel).
Random Forest Classifier
Neural Networks

### Links to Notebooks
-[Initial Exploration](initial_exploration.ipynb)

-[linear_regression](linear_regression.ipynb)

-[Classification](classification.ipynb)

-[Clustering & NN](clustering.ipynb)

Visualizations can be found in Initial Exploration.
