# Project Name: Bike-Sharing_Linear-Regressinon-Assignment
> This is the case study for a basic understanding to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    1. Which variables are significant in predicting the demand for shared bikes.
    2. How well those variables describe the bike demands

### Business Goal:

We need to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


### Steps Followed:
1. Data understanding, preparation 
2. EDA
3. Data preparation
4. Model building and evaluation
5. Residual Analysis
6. Prediction & evaluation on the test

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
1. numpy
2. pandas
3. matplotlib.pyplot
4. seaborn
5. sklearn
6. statsmodels

## Conclusions
The summary of the model after linear regression model building and training, residual analysis and evaluation of test model are as follows:
1. Model with 8 variables is having R-squared value for Training and Test data as `0.804` and `0.772` respectively.
2. Adjusted R-Square for training data is `0.801` and for test data is `0.763`.
3. Final list of features are: ['yr','holiday','temp','windspeed','season_summer','season_winter','mnth_sep','weathersit_Light_snowrain']
4. More bookings were observed on Clear/FewClouds and Mist Cloud. Lowest booking on Light Snow/Thunderstorm days
5. Fall season has more booking for rental bikes.
6. With in an year , July month has atracted more rentals. But in general most bookings are done from May- Oct.
7. Top 5 variables which is recomendeded to give utmost importance while planning to achieve maximum demand.

 temp|weathersit_Light_snowrain|yr|windspeed|season_winter|
 -|-|-|-|-|
 0.568|-0.253|0.233|-0.145|0.126|

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->





<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
1. Wikipedia- https://en.wikipedia.org/wiki/Anscombe%27s_quartet
2. Statsandr - https://statsandr.com/blog/multiple-linear-regression-made-simple/



## Contact
Created by [@pramod-prasad01] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
