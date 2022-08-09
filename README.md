# Housing Price Prediction Case Study

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
 a. Which variables are significant in predicting the price of a house, and
 b. How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

## Table of Contents
* [General Info](#general-information)
* [Data Info](#data-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Surprise Housing wants to know 
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also the optimal value of lambda for ridge and lasso regression.


## Data Information
- They need these info to enter in Australian Market.
- Dataset is available at: https://ml-course3-upgrad.s3.amazonaws.com/Assignment_+Advanced+Regression/train.csv
- Also data disctionary is available at: https://cdn.upgrad.com/UpGrad/temp/87f67e28-c47e-4725-ae3c-111142c7eaba/data_description.txt 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Lasso regression results
  - R2 Score
  - Train: close to 0.9131
  - Test: close to 0.8871
  - alpha value: 0.0001
  - Top 10 predictors for SalePrice are
  - OverallCond, BsmtFullBath, 1stFlrSF, LowQualFinSF, 2ndFlrSF, MasVnrArea, BsmtFinSF1, Neighborhood_Timber, Neighborhood_NridgHt, BsmtFinSF2

- Ridge regression results
  - R2 Score
  - Train: close to 0.9141
  - Test: close to 0.8759
  - alpha value: 5.0
  - Top 10 predictors for SalePrice are
  - OverallCond, BsmtFullBath, LowQualFinSF, 2ndFlrSF, BsmtFinSF2, BsmtFinSF1, Neighborhood_NridgHt, 1stFlrSF, Neighborhood_Timber and MasVnrArea

- Recommendation is to go with Lasso Regression model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - 3.9.7
- numpy - 1.20.3
- pandas - 1.3.4
- matplotlib - 3.4.3
- seaborn - 0.11.2
- sklearn - 0.24.2

## Acknowledgements
- This project was inspired by Advanced Linear Regression Model using Lasso and Ridge regression models learning at Upgrade as part of AI/ML course.
- This project was based on [this tutorial](https://learn.upgrad.com/course/1991/segment/25160/150983/463809/2405074).


## Contact
Created by [@kc11381] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
