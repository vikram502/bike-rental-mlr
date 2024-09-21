# Bike Rental Multiple Linear Regression

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Information

> The project is an Assignment to create a Multiple Linear Regression model using the BoomBikes dataset to predict the demand for shared bikes.

### Project Background
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

Company want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

### Project Statement
Create a model to predict the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### Dataset

> The dataset is a csv file with BoomBikes bike rental data.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- __Equation for best fitted line is:__
$ cnt = 0.1343 + 0.2333  \times  yr - 0.1072 \times  holiday - 0.1529 \times windspeed + 0.0991 \times mnth Sep + 0.0878 \times season summer + 0.1323 \times season winter - 0.0503 \times weekday Sunday  - 0.2890 \times weathersit light - 0.0810 \times weathersit mist + 0.5473 \times temp $
- R^2 values
    - Train dataset R^2: 0.8364
    - Test dataset R^2: 0.7959
    - Train dataset Adjusted R^2: 0.8262     
    - Test dataset Adjusted R^2: 0.7633
- Significant variables list based on VIF
    1. `temp`
    2. `windspeed`
    3. `yr`
    4. `season_summer`
    5. `weathersit_mist`
- Fall season has the highest number of bike rentals followed by summer, and, in
each season the booking count has increased from 2018 to 2019.
- Year 2019 has higher rentals than 2018.
- When it comes to months, the sales have a positive trajectory from Jan to Jun, then
a downward trend from July to December.
- A user is more likely to rent a bike when the weather is "clear" and less likely to
rent it when it snows.
- Thursday, Friday, Saturday have more bookings when compared to the start of the
week.
- When it's a holiday, bookings seem to be less in number.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.2.2
- matplotlib - version 3.8.4
- seaborn - version 0.13.2
- statsmodels - version 0.14.2
- sklearn - version 1.5.1.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
The Case Study is developed as part of the Linear Regression Module required for Post Graduate Programme in Machine Learning & AI - upGrad and IIIT, Bengaluru

## Contributors
[Aditya Vikram Tata](https://github.com/vikram502)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->