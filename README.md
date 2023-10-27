# Car Price Prediction

## Project Description
A used car sales service is developing an application to attract new customers.  
The goal is to build a model that can determine the market value of a car based on its characteristics.  
Data on technical specifications, configurations, and prices of other cars are available.  

## Key Findings
Data preprocessing and exploratory data analysis were performed.  
Feature correlations were determined.  
The target RMSE metric of 1654 was achieved, which is better than the target value of 2500, using an LGBM model with the following hyperparameters:  
- Learning Rate: 0.3  
- Number of Estimators: 100  
- Verbose: -1  

## Additional Information
Toolkit: Pandas, Python, LightGBM, Scikit-learn
