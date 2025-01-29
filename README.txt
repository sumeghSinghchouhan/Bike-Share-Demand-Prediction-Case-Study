# Project Name : Bike Sharing Case Study

BoomBikes is a bike-sharing company in the US that allows users to rent bikes for short-term use.
Due to the COVID-19 pandemic, the company has seen a drop in revenue and is struggling to sustain itself.
As the pandemic situation improves, the company wants to predict how the demand for shared bikes will change. This will help them adjust their business strategy to meet future demand. The company wants to know the following factors:-

1) Which variables are significant in predicting the demand for shared bikes.
2) How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The aim of the Project is to help a US based bike sharing provider BoomBikes that has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
Our goal is to help the company understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1) Which variables are significant in predicting the demand for shared bikes.
2) How well those variables describe the bike demands

- To forecast shared bike demand and understand the contributing factors, we employed a multiple linear regression model. Our analysis was based on daily time series data from 2018 and 2019, encompassing weather conditions, temperature, environmental variables, and contextual factors like workdays, holidays, weeks, and seasons.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Key Factors significantly influencing bike share demand were:-
  1) Year: As the year progresses, bike share demand tends to increase.
  2) Temperature: Warmer weather leads to higher demand.
  3) Season: Summer and winter see increased demand compared to spring and fall.
  4) Weekday: Sundays generally have higher demand than weekdays.
  5) Weather: Clear weather is associated with higher demand, while rain or mist decreases it.
  6) Month: Certain months (like August and September) have higher demand compared to others (like January).
- Specific Interpretations:
- For each unit increase in temperature, bike share demand increases by 0.4940 units, holding other factors constant.
- On a working day compared to a non-working day, demand increases by 0.0552 units.
- In the summer season, demand increases by 0.0936 units compared to spring.
- Factors that decrease the Demand for Bike- Share are : Weather Situations like Light Snow or light Rain and Mist+Cloudy  
  Sky, Month of January, High windspeed .
- Top 5 Factors that affect the Demand for Bike- Share are : Temperature, Light Snow or light Rain, year, Windspeed and    
  Winter Season

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- seaborn - version 0.13.2
- sklearn - version 1.2.2
- statsmodel - version 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad IIIT Bangalore PG program on ML and AI.
- This project was based on Multiple linear regression


## Contact
Created by [@sumeghSinghchouhan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
