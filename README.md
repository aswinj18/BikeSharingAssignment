# Bike Sharing Assignment
> To create a Linear Regression Model that explains the demand of the bike sharing, for a bike sharing business BoomBikes. The business wants to know 2 things:
    > - 
    > - How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To create a Linear Regression model that explains the demand in the bike sharing market.
- A bike sharing business, BoomBikes, wants to know the demand to help with increasing its revenue.
- The model should explain two things:
    - Which variables are significant in predicting the demand for shared bikes?
    - How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model created: y = 526.45 +2001.47*yr -1045.42*holiday +4180.74*temp -508.86*season_spring +603.29*season_summer +833.91*season_winter +387.93*day_11 +452.76*day_16 +388.27*day_17 +433.68*mnth_10 +340.26*mnth_8 +912.70*mnth_9 -460.89*weekday_Tues -2076.14*weathersit_bad_weather +707.02*weathersit_best_weather
- Significant Variables explaining demand: 
    - year
    - holiday
    - temperature
    - season
    - if its 11th, 16th, or 17th of a month
    - if its August, September, or November month
    - if its Tuesday
    - weather
- Factors positively impacting demand: 
    - year (more demand in 2019 than 2018)
    - Temperature increase
    - winter and summer seasons
    - if its 11th, 16th, or 17th of a month
    - if its August, September, or November month. November has the highest positive effect on demand
    - best weather
- Factors negatively impacting demand:
    - bad weather (highest negative factor)
    - holidays
    - spring season
    - Tuesdays

## How good the model is | R2-Score
- Training R2-Score: 0.841
- Testing R2-score: 0.771

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Acknowledging the following people, without whom I could not have done the project:
- Associate Professor Dinesh J Babu, who took the online recorded classes
- Instructor Shivam Garg, who took the Linear Regression online session
- Professor Raghuram, who took the theoretical session on Gradient Descent
- Instructor Akashdeep Makkar, who took the online session on how to do this assignment

## Contact
Created by [@aswinj18] - feel free to contact me!ss


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->