# Midterm-Election-Project

## Summary 
This is a project that aims to predict the outcome of this year's midterm elections. It takes a number of predictor variables and the results of previous election cycles to predict this one. The models will use logistic regression and are coded in Python. All of the data is from RealClearPolitics and their polling archive. 

## Model 1
This model was made using a large database of the average polling data of tossup senate elections from 2014 to 2026. Used factors such as polling averages, incumbency advantages, partisan lean, midterm status, and the party of the president to create a logistic regression model. As of 09/04/2026, this model predicts that Democrats will win in 7 of the 9 tossup senate races. According to this model, Republicans are set to win in Iowa and Alaska, but Democrats will win the other 7 tossup races including Texas and Ohio. 

## Model 2
This model aims to create a more comprehensive model with more variables and more importantly time till election. The database for this model will contain every single poll from tossup Senate races from 2018 to determine the winner of this year's election. Importantly, this model will take days till the election into account to see if a party can gain an advantage towards the end of an election cycle. This project will be done by training the 2018 data and then testing the 2020 data. And then train the 2018 and 2020 data and test it on 2022, and so on and so forth. This model is currently a work in progress. 
