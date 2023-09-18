# Project Name
>   BIKE SHARING ASSIGNMENT 


## Table of Contents
* [General Info]
* [Conclusions]
* [Technologies Used]
* [Acknowledgements]



## General Information
Provide general information about your project here.

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
What is the background of your project?

The goal of project is to build to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

What is the business probem that your project is trying to solve?

BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands


What is the dataset that is being used?
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 



## Conclusions
1.demand for bikes is less for spring, then increases for summer with maximum for fall season and then again decreases for winter. 
2.The bike demand for year 2019 is greater than year 2018.
3.The bike demand for working day is greater than that of holiday.
4.The demand of bikes is highest for clear or parly cloudy weather while minimum for weather with light snow/light rain + thunderstorm. Worsening of weather condition decreases the demand for bikes.
5.The demand for bikes is minimum for month of January and maximum for month of June. The demand gradually increases from January to June, then it more or less remains constant from July to September while again shows a decreasing trend from October till December.
6.Demand for bike is less for holidays than that when it is not an holiday.

## Final Result Comparison
Train R^2 :0.787 Train Adjusted R^2 :0.784

Test R^2 :0.767 Test

This seems to be a really good model that can very well 'Generalize' various datasets.


As per our final Model, the top 5 predictor variables that influences the bike booking are:
The equation of best fitted surface based on model: cnt = -0.0483 + (yr × 0.2371) + (workingday x 0.0211) + (atemp * 6625 )  + (season_2 * 0.0829) + (season_4 * 0.1462) + (mnth_9 *0.0956) + (weathersit_3 * -0.2315)
**Variable	Coefficient	Description**
atemp :	0.6625	Indicates that a unit increase in temp variable increases the bike hire numbers by this many units
yr	:0.2371	Indicates that a unit increase in yr variable increases the bike hire numbers by this many units
weathersit_3	:-0.2315	Indicates that a unit increase in bad weather situation( Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) variable decreases the bike hire numbers by this many units
season_4: 0.1462 Indicates that a unit increase in season_4(winter) variable increases  the bike hire numbers by this many units
season_2 : 0.0829	Indicates that a unit increase in season_2(summer) variable increases  the bike hire numbers by this many units


Other fields to predict the demand for bikes.

working day (0.0211)
month_9(0.0956)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas 
- matplotlib
-Seaborn
-statsmodels.api
-scikit-learn 



## Acknowledgements

- This project was inspired by assignment given by upgrad.
-


## Contact
Created by [@Aratrika96] 


