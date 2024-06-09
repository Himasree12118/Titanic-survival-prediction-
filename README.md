# Titanic-survival-prediction-
To predict the survival chances of the Titanic passengers using the given information about their sex, age, etc. As this is a classification task we will be using random forest.

There will be three main steps in this experiment:

Feature Engineering
Imputation
Training and Prediction

Download the dataset from this link https://www.kaggle.com/competitions/titanic/data?select=train.csv. Once the dataset is downloaded it is divided into three CSV files gender submission.csv train.csv and test.csv

visualize the data using some pie charts and histograms to get a proper understanding of the data.

Feature Engineering

Now see which columns should drop and/or modify for the model to predict the testing data. The main tasks in this step is to drop unnecessary features and to convert string data into the numerical category for easier training.

Model Training

Using Random forest as the algorithm of choice to perform model training. Before that, split the data in an  ratio as a train-test split. For that, we will use the train_test_split() from the sklearn library.

Prediction

Provided with the testing dataset on which we have to perform the prediction. To predict, pass the test dataset into trained model and save it into a CSV file containing the information, passengerid and survival. PassengerId will be the passengerid of the passengers in the test data and the survival will column will be either 0 or 1.
