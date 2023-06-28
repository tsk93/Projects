#  ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2 - Predicting Singapore's Housing Resale Price

**Primary Learning Objectives:**
1. Creating and iteratively refining a regression model
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process
3. Providing business insights through reporting and presentation.


## Problem Statement

In this project, a linear regression model based on Singapore Housing Dataset was established to predict the resale price of a HDB unit to aid potential buyers and sellers estimate the amount they can expect to pay or sell for. This model will provide insights into the key features that exert a significant influence on a unit's resale value. The predicted resale price on an independent test dataset will also be submitted to a Kaggle competition, with the lowest Root-Mean-Squared-Error (RMSE) score as the evaluation metric.

## Dataset

The HDB resale price dataset consists of more than 70 different housing features relating to houses. The original dataset is in the datasets folder as shown below:

- train.csv: training dataset with all features and HDB resale prices
- test.csv: test dataset with all features only, for submission to competition on Kaggle
- sample_sub_reg.csv: sample of the submission template
    
## Technical Report

The technical report is split into 5 parts in the code folder:

- Part 1 - Data Cleaning.ipynb: A Jupyter notebook that performs data cleaning and the result is exported to the cleaned_housing_data.csv dataset in the datasets folder.
- Part 2 - EDA and Feature Engineering.ipynb: A Jupyter notebook that focuses on Exploratory Data Analysis (EDA) and feature engineering and the result is exported to the cleaned_housing_data.csv dataset in the datasets folder.
- Part 3 - Model Tuning & Evaluation.ipynb: A Jupyter notebook that focuses on model fitting and assessing the performance of each model using RMSE and R2 score. The model coefficients are exported to model_coefficients.csv dataset in the datasets folder for further analysis.
- Part 4 - Production Model Insights.ipynb: A Jupyter notebook that uses the trained model to provide business insights.
- Part 5 - Kaggle Submission.ipynb: A Jupyter notebook that utilises the trained model to generate resale price predictions on the test dataset, the result is exported to kaggle_submission.csv in the datasets folder and uploaded to Kaggle.


## Performance of Model for Kaggle Submission

Based on the evaluation metric of root-mean-squared-error (RMSE), the production model has a public and private score of 52323 and 52640 respectively. ![Image](https://github.com/tsk93/DSIF-9-v2/blob/main/Project%202_Predicting%20Singapore's%20Housing%20Resale%20Price/images/Kaggle%20submission%20of%20predicted%20housing%20price_Song%20Kai.png)


## Conclusions and Recommendations

Planning area and flat type are the most influential factors that determine a housing unit's resale price. A HDB in Marine Parade or Tanglin can expect to sell at a higher resale price than other areas, while those in Woodlands and Sembawang are expected to sell for the lowest prices. With the exception of terrace units, resale price will likely be dependent on the number of rooms in the units. The more rooms there are, the higher the resale price. Amenities have a much lower impact on resale price.

## Future Research

Besides the HDB resale market, it would be worth taking a look into the private property market in Singapore as well. Looking at both HDB and private markets might help to create interesting insights and allow us to compare features that drive housing prices in both markets. In addition, studying overseas housing trends might also allow us to understand features that are specific to different countries/continents.

This resale price model is specific to Singapore and may not be representative of other cities. For instance, our neighbouring countries have significantly more land and floor area might not be an immediate concern anymore. In addition, some other features could be added to the dataset. One example would be increase the amount of facilities/amenities, such as the distance to provision shops, fast food chains or coffeeshops instead of relying on just distance to hawker centres.