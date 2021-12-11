# Multiple Linear Regression Model For The Prediction Of Demand For Shared Bikes
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## General Information

* Problem Statement

  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

  In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

* The company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands.

* Business Goal:
To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.



## Conclusions
* Analysing the model the company should take the following steps into consideration

* Temperature (temp) is having the highest co-efficent . It plays a major role in bookings. A a unit increase in temp variable increases the bike hire    numbers by 0.5393 units when the temperature in normal range
* Company should focus on expanding business during August and September months
* Saturday , the rentals shows high bookings.
* When there is high windspeed and misty-cloudy and rainy weathers bike rentals might go low.
* Holiday season is also one such fator wherein rentals might be low.

* Variables significant in predicting the demand for shared bikes are :
  Seasons: Summer and Winter
  Months : August and September
  Weekday: Saturday
  Year : 2019
  Working Day
  temp
  
  All the above variables ( season_Summer, season_Winter, mnth_Aug, mnth_Sep, weekday_Saturday, yr, workingday,temp) have positive coefficients indicate that an increase in these values will lead to an increase in the bike rentals

* Variables which are responsible for decrease the no of bookings are :
  Weather : Mist & Cloudy , Light Snow & Rain
  hum: humidity
  windspeed: wind speed
  holiday
  
  All the above variables ( weathersit_Mist & Cloudy , weathersit_Light Snow & Rain, hum, windspeed, holiday) have negative coefficients indicate that an decrease in these values will lead to an decrease in the bike rentals



## Technologies Used

- library - version 3.0



## Contact
Created by [@shwethapp] - feel free to contact me!


