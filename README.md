# Midterm-Election-Project

## Summary 
This is a project that aims to predict the outcome of this year's midterm elections. It takes a number of predictor variables and the results of previous election cycles to predict this one. The models will use logistic regression and are coded in Python.

## Basic Model Methodology 
This model was made using a large database of the average polling data of tossup senate elections from 2014 to 2026. Used factors such as polling averages, incumbency advantages, partisan lean, midterm status, and the party of the president to create a logistic regression model. This model predicts a 53-47 senate majority for the Democrats. 

## Final Model Methodology 
This model aims to create a more comprehensive model that takes into account each and every individual poll from 2006 to 2024. It uses the same factors as the basic model, but we are analyzing the data at an individual poll level, rather than the poll averages. The model uses logistic regression on the dataset with all the polls from 2006 to 2024, and then predicts that on all the polls that have come out in the month leading up to the election. Then the probability of winning is averaged out to get a percent chance of the Democrats winning. I've created 6 models in this notebook. One takes the predicted case when it comes to national environment and then a best and worst case for Democrats and Republicans. And then 3 of the models have incumbency factored in and 3 don't since the incumbency advantage is not a great variable to use to predict this year's election since most incumbents are quite unpopular. 

### Final Model Results
Here are my final predictions:

Alaska - Dem flip (altough this race is virtually a 50/50 tossup)

Florida - Rep hold

Georgia - Dem hold

Iowa - Rep hold (altough this race is virtually a 50/50 tossup)

Kansas - Rep hold (altough this race is virtually a 50/50 tossup)

Maine - Dem flip

Michigan - Dem hold

Minnesota - Dem hold

New Hampshire - Dem hold

North Carolina - Dem flip

Ohio - Dem flip

South Carolina - Rep hold

Texas - Dem flip (altough this race is virtually a 50/50 tossup)

Final Prediction: D - 52 seats, R - 48 seats

Democrats' Ceiling: 54 seats, Republicans' Ceiling: 51 seats
