# Vehicle-Insurance-Claim-Amount-Prediction-MLR
Python Data Science Project, Vehicle-Insurance-Claim-Amount-Prediction using MLR algo with 79.62% accuracy, RMSE: 10087, MAE: 8238, Mallow's_CP: 0.001, D_Watson: 1.76, No Multicollinearity

## Problem Statement
An Indian vehicle insurance company wants to create such a system through which the company can estimate proper insurance amount for Client's vehicle. If the company gets proper estimates for the insurance amount it can build better insurance plans & policies benefiting both sides.

They have contracted an consultency firm to understand the factors on which the insurance amount of cars depends. Specifically, they want to understand the factors affecting the insurance of cars in the Indian market. The company exactly wants to know:

- Which variables are significant in predicting the insurance amount

- How well those variables describe the price of a car

Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars Features & Insurance details.

## About the Car Insurance Prediction
Insurance Claim Amount is Target variable & 5 features are Vehicle Length, CC, Weight, Age

## Business Goal
You are required to model the Insurance amount of cars with the available independent variables. It will be used by the management to understand how exactly the amount varies with the independent variables. They can accordingly manipulate the insurance schemes, conditions, terms & policies to meet the company goals. Further, the model will be a good way for management to understand the vehicle insurance dynamics of Indian market.

## Project Overview
In this Project I have unleashed the useful Data Science insights using this Vehicle Insurance dataset and performed the feature selection precisely to build multiple linear regression model by combining the power of best statistical rules & principles to maximise accuracy at its best. The best thing is my model is not having any Multicollinearity & Heteroscedasticity problem.

## This Project is divided into 28 major steps which are as follows:
1. [Check out the Data](#data-check)
2. [Importing Libraries & setting up environment](#imp-lib)
3. [Loading dataset](#data-load)
4. [Data Cleaning & Preprocessing](#prep-clean)
5. [Shapiro for Normality test of All Numeric Columns](#shapiro-norm)
6. [Spearman Correlation Test for Measures of Association between non-normal Datas](#spear-corr)
7. [Outlier Treatment/Check](#out-check)
8. [Skewness Check](#skew-check)
9. [Exploratory Data Analysis ( EDA )](#data-expo)
10. [Measures of Association between Continuous and Categorical Variables](#cat-measure)
11. [New Feature Creation](#new-feature)
12. [Removal/Selection of Categorical Features](#feature-select)
13. [Saving The Cleaned CAR DataFrame](#save-clean)
14. [Assigning Label & Features](#Labe-Feature)
15. [Features Encoding Technique](#Features-Encoding)
16. [Scaling of Numeric Features](#scale-feature)
17. [Train & Test Split](#data-split)
17. [Features P-Value & VIF Check](#p-vif)
18. [Final Implimentation of the MLR Model](#final-model)
19. [Model Evaluation](#mod-eval)
20. [Actual vs Predicted Price of Used CAR](#actual-predicted)
21. [Residual Distribution of Predicted Used CAR Price](#re-dit)
22. [Amount of Error in Used CAR Price Prediction](#amt-er)
23. [Durbin Watson Auto-Correlation Test](#dur-wat)
24. [Regression Evaluation Metrics](#mod-eval)
25. [Plotting the Regression Line](#reg-plot)
26. [Heteroscedasticity Tests](#het-test)
27. [Auto-Correlation plot](#auto-plot)
