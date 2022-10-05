# Advanced Regression 

> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
 
The company wants to know:
 - Which variables are significant in predicting the price of a house, and
 - How well those variables describe the price of a house.

## Table of Contents
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## Business Goal 
 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions

Results comparison

Comparing the results of both Ridge and Lasso:

**Ridge Regression:**

R2 score Train: 84.8 percent
R2 score Test: 79.7 Percent
RSS for Train data: 1.798
RSS for Test data: 0.962
MSE for Train data: 0.0018
MSE for Test data: 0.0023

**Lasso Regression:**

R2 score Train: 84.7 percent
R2 score Test: 80.3 Percent
RSS for Train data: 1.811
RSS for Test data: 0.933
MSE for Train data: 0.0018
MSE for Test data: 0.0022

**Optimal Alpha Values**

Alpha = 1.0 in Ridge
Alpha = 0.0001 in Lasso
Conclusion Comments

Except R2 score value, the rest of the values are almost the same. The R2 scores are better in the Lasso Regression.

Since the Lasso Regression fares better than the Ridge Regression, let's consider the features from the Lasso. The top ten features that best explain the target variabl are:

1. The basement quality (BsmtQual)
2. The overall quality of house (OverallQual)
3. The exterior quality (ExterQual)
4. The lot shape (LotShape)
5. The level of the house (Lvl). That is the land contour will play the role.
6. CulDSac. Lot configuration plays a role in the sale price.
7. FR3. That is lot configuration with frontage on 3 side of the property plays a role.
8. GarageAge
9. Overall condition
10. RRAn. That is the conditions like North-South rail road play a role.




## Technologies Used

- Python 3.9.6
- Jupiter Notenook 6.4.12
- SciKit Learn 1.1.1
- Statsmodels 0.13.2



## Contact
Created by [sunkannah346@gmail.com] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
