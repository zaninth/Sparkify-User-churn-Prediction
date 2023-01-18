# Sparkify User churn Prediction

## 🚀**Introduction**
In this project , I will explain my Udacity Data Scientist track graduation project: churn modelling for music app Sparkify. 
Sparkify is a fictional digital music service application for mobile phones and computers created by [Udacity](https://eu.udacity.com/) for some projects. It is same as with Spotify or other music streaming apps. It has same type of data as we are used to in web site event type data. When a user plays a song or open the app, all these actions are logged to database with their event types. With these data a lot of experiments can be done.
This project is created as a part of [Udacity](https://eu.udacity.com/) Data Scientist Nanodegree Program.

*Read the article on [Medium](https://medium.com/@thaleszanin/can-we-predict-if-a-customer-will-leave-or-downgrade-a-service-churn-1dc752c8ff55)

The aim of the project was divided into 3 sections:

* **Data Understanding:
  -Loading the dataset
  -Inferring the meaning of different variables, their type, the values they can take, their distribution
  -Understanding the relationships between different columns
  -Identifying missing values, potential duplicates
  
* **Feature Engineering and Exploratory Data Analysis:
  -Transforming the original dataset (one row per user log) to a dataset with user-level (one row per user) information or statistics, obtained through mapping (e.g. user's gender, start/end of the observation period, etc.) or aggregation (e.g. song count, advertisement count, etc.)
  -Engineering the features that will be used to identify churned users, e.g. aggregated statistic per unit of time, number of plan changes, songs played vs. total activity ratio, thumbs up vs. thumbs down ratio, activity trend, etc.
  -Defining and calculating the binary response variable: 1 - users who cancelled their subscription within the observation period, and 0 - users who kept the service throughout
  -Analyzing the correlation between engineered features
  -Performing exploratory data analysis comparing the engineered statistics for users who stayed vs users who churned

* **Modelling and Evaluation:
  -Defining pipelines that combine: standardization of the numerical features, feature assembly, and a selected binary classifier (logistic regression, random forest classifier or gradient boosting classifier)
  -Splitting the dataset into train and test set
  -Pipeline training and tuning using grid-search with cross validation for all different classifiers on the training data
  -Analyzing model performance in cross validation (using AUC as metric) and extracting feature importances
  -Retraining the models that performed best on the full training set and evaluating model performance on the test set (using standard AUC and F1 metrics)

## 📁 **File Description**
* Notebook: 
    - Starbucks - Jupyter notebook with all data analyses e preparations and modeling tests.
* Data:
    - training.csv - Contains the data that should be used to train ou model.
    - test.csv - Contains the data that should be used to test our model.
* Models:
    - test_results.py - Script used to test the model.

## ⚠️**Software and Libraries**
* This project uses Python 3.7.2 and the following libraries:
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Scikit-learn](http://scikit-learn.org/stable/)

## 🥇 Acknowledgments
I would like to thank the team from [Udacity's](https://www.udacity.com/) for the great support and the brilliant online 
course [Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) and [Starbucks](https://www.starbucks.com/) for the incredible challenge.

## 📫 Have questions?
Any doubt?? Feel free to ask.[Linkedin](https://www.linkedin.com/in/thales-zanin/)

If you find this repo useful,don't forget to give a ⭐
