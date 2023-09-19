# Surprise House Sales
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.


## Table of Contents
* [Objective](#Objective)
* [Conclusions](#conclusions)


## Objective
- Create a Regression model which can predict the price of house based on number of independant variables.
- Understand how exactly the prices vary with the variables
- Find out the optimal value of alpha for Ridge and Lasso regression model
- Find the significant variables which are determining the price of house. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Optimal value of alpha is Ridge - 4 and Lasso - .0001
### TOP Predictor variable accoring to Ridge model
- Neighborhood_Crawfor  
- OverallCond_9         
- OverallQual_9          
- Exterior1st_BrkFace   
- OverallCond_8
### TOP Predictor variable accoring to Lasso model
- Neighborhood_Crawfor    0.156330
- OverallQual_9           0.144760
- Exterior1st_Stucco      0.141526
- OverallCond_9           0.138120
- OverallQual_10          0.116798
       



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
