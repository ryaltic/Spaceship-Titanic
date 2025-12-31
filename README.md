# Spaceship-Titanic-Kaggle
This repository relates to the Kaggle Spaceship Titanic competition

## Purpose
The purpose of this repository is to use machine learning in Python using the Sci-Kit Learn packages. This repository will help me refine my machine learning skills espically in Python and provided a end-to-end data science driven solution from reading in the data to uploading the results onto Kaggle as well as learn new techniques and skills about machine learning in Python. The goal of this competition is to get the highest accuracy score and my personal goal is to get an accuracy score above 0.80.

### Competition Link:
https://www.kaggle.com/competitions/spaceship-titanic

## Introduction to Problem and Background Information
The spaceship competition is set in the future (year 2912), and an issue occurred where a bunch of passengers were transported to an alternate dimension while travelling in space. The goal is to help retrieve the lost passengers by using the records on the spaceship to predict whether someone was transported or not. The competition was graded on accuracy score and has a rolling leaderboard that is constantly updated.

## Description of Repository
In this repository, there are four files: a README file, the train CSV file, the test CSV file, and the notebook in .ipynb format used to predict if someone is transported or not. The README file contains information about the competition and background information as well as what the repostitory contains. The train and test CSV files contains data about the passengers and were downloaded from the Kaggle competition data files. The notebook is in a .ipynb notebook file and contains all of the steps taken to predict if a passenger was transportated or not. The notebook contains reading in the file, splitting the data into training and test, EDA, Feature Engineering, Modelling (Logistic Regression, Random Forest, XGBoost), and Scoring on the unseen data. The notebook provides explanation and comments about the code.

## Results
The best accuracy score was 0.802 from the XGBoost model followed by the Random Forest model with an accuracy score of 0.795 while the Logistic model did the worst with 0.788 accuracy score. All three models underwent parameter tuning and variable importance. I am not suprised that the XGBoost model performed the best as it is the most advanced modelling method tried and had the most extensive tuning grid. Overall, I am satisifed with the results as my goal for this repository was to hit the 0.80 accuracy threshold. 

## Possible Improvements
Some improvements that can be made to this repository is transforming some variables as that can help the problems with the outliers or do a deeper dive into outliers to help reduce skewedness. Another thing that can be done is to introuduce more variables into the model such as adding a group size variable or adding interactions variable between certain variables. Also more in-depth variable testing can be done to see if certain variables help add predicted power into the model or if it adds noise to the model hurting the performance of the model. A more interesting thing is doing something with the name columns such as doing some text analysis to link passangers to families or relationship between passengers based on first and last name. A more advanced imputation strategy can increase the performance of the models as well. Another strategy is adding a more advanced or different type of model can increase performance.
