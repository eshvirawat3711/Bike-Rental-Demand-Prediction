# Bike-Rental-Demand-Prediction
Predicting the rental of bikes at any given hour in the day so the company can arrange for sufficient number of bikes for the customers.

This case study is about a bike rental shop.They have shared the hourly rental data for last two years.

The flow of the case study is as below:

* Reading the data in python
* Defining the problem statement
* Identifying the Target variable
* Looking at the distribution of Target variable
* Basic Data exploration
* Rejecting useless columns
* Visual Exploratory Data Analysis for data distribution (Histogram and Barcharts)
* Feature Selection based on data distribution
* Outlier treatment
* Missing Values treatment
* Visual correlation analysis
* Statistical correlation analysis (Feature Selection)
* Converting data to numeric for ML
* Sampling and K-fold cross validation
* Trying multiple Regression algorithms
* Selecting the best Model
* Deploying the best model in production

# Data description
The business meaning of each column in the data is as below:

* season: The current season (1:winter, 2:spring, 3:summer, 4:fall)
* yr: year (0: 2011, 1:2012)
* mnth: month ( 1 to 12)
* hr: hour of the day (0 to 23)
* holiday: weather day is holiday or not
* weekday: day of the week
* workingday: if day is neither weekend nor holiday is 1, otherwise is 0
* weathersit: The Weather forecast for the day
    1: Clear, Few clouds, Partly cloudy, Partly cloudy
    2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
* temp: Normalized temperature in Celsius.
* atemp: Normalized feeling temperature in Celsius.
* hum: Normalized humidity. The values are divided to 100 (max)
* windspeed: Normalized wind speed. The values are divided to 67 (max)
* casual: count of casual users
* registered: count of registered users
* cnt: count of total rental bikes including both casual and registered
