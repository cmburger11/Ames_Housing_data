
# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Ames, IA Housing Data:

### Problem Statement

<<<<<<< HEAD
What features affect Sales Price of the Ames Housing Data Set the most? What should homebuyers consider when looking for a home?
>>>>>>> 4c1d7003b1f287306d13b05dcab02acd89ecc433

---
### Background Research & Sources

Using the famous Ames, IA Housing DataSet, I have created testing and training datasets, as well as visualizations. The point of this is to create a model to most closely predict the Housing Prices in Ames. Data is from 1872-2010.

---
### Datasets Used

original testing dataframe = pd.read_csv ("test.csv")
-Ames Housing Kaggle Competition Testing Dataframe

original training dataframe = pd.read_csv ("train.csv")
-Ames Housing Kaggle Competition Training Dataframe

sample Kaggle submission = pd.read_csv ("sample_sub_reg.csv")
-Example for how submission to Kaggle should look.

test_clean = pd.read_csv ("test_clean.csv")
-Ames Testing data after EDA, Data Cleaning and some Dummification

train_clean = pd.read_csv ("train_clean.csv")
-Ames Training data after EDA, Data Cleaning and some Dummification

kaggle_submission = pd.read_csv ("kaggle_attempt_923")
-My Kaggle Submission (7th place!)


---

### Analysis Summary

I began by importing both the Ames Testing and Training Datasets. I cleaned them separately, depending on the dataset and its needs and then in a separate notebook, created several models (Linear Regression, Train-Test-Split, Cross Validation, etc.) as well as several visualizations to show the different features included in the dataset and how they affect the Sale Price of the listed homes.

My final model got 7th place in the Kaggle Competition with a score of just under 21k RMSE.
---

### Conclusions & Considerations

I found that there are 8 Major features that can greatly increase or decrease the Sale Price of a home. I performed several visualizations regarding these and had some interesting findings, as well as some expected ones. Overall, the sale price of a home in Ames greatly depends on many different features; from total square footage to housing type, size of the garage and overall condiiton of the home. Great things to consider when lookin to buy a home.

---

### Sources Cited:/
Ames Housing Data Set https://www.kaggle.com/c/dsir-1019-project-2-regression-challenge/data
