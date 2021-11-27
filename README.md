# INSAID2021-ML-Foundation-Predicting_Beijings_Air_Pollution
INSAID 2021 ML Foundation Term Project
# Project Description
## Introduction
Client for this project is an air purifier company.

One of the leading Global pollution controller organizations.
The company is working its way for the betterment of the society by using advanced technologies to purify the air by removing harmful particles from the atmosphere.

## Current Scenario
As we know in recent years the pollution emitted per day has increased drastically, countries all around the world are taking up actions in order to tackle the rapid increase in pollution to avoid global warming.

Beijing’s pollution authority has collected data for the past 5 years and the data has been passed on to your client by the government of China.
The company calculates pollution using traditional or manual methods, so it needs a model to do the long process.

## Problem Statement
Beijing is suffering from the following problems:

 * China is notorious for being a major polluter. Its economic growth in the past three decades has been the fastest among major nations, which is the main factor in why China has extensive air pollution.
* China’s Environmental Sustainability Index is ranked near the bottom among countries worldwide.
* Air Pollution in Beijing is mainly dominated by coal combustion and vehicles running on the roads.
* With this amplified wealth, individuals are more capable of affording motor vehicles. The number of motor vehicles on Beijing’s roads has doubled to 3.3 million with nearly 1200 added each day.
* They want to come up with actionable insights and a model that could help predict pollution.
They expect a model that could predict the daily pollution emission for Beijing.
The idea is to use the model in order to take further action to reduce the pollution rate.

## Project Task
* Dataset of the past few years of the air quality (2013-2017) is provided.
* The data is from the 12 stations of Beijing that have been thoroughly observed.
* Project task is to build a regression model using the dataset.

## Project Deliverables
* Deliverable: Predict the particulate matter from the given set of data.
* Machine Learning Task: Regression
* Target Variable: PM2.5
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the RMSE score.
# Data Description
* The dataset containing all the necessary information about the air quality of Beijing.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 403776 rows and 17 columns.
* The train set contains data from 2013-16.
* The column PM2.5 is the target variable.

## Test Set:
* The test set contains 16728 rows and 16 columns.
* The test set contains data for 2017.
* The test set doesn’t contain the PM2.5 column.
* PM2.5 needs to be predicted for the test set.
# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **REF_NO**   | Index of rows                          |
|02| **year** | Contains the year in which the data was Recorded                 |
|03| **month**        | Contains the month of the year in which the data was Recorded            |
|04| **day**          | Contains the day of the month in which the data was Recorded                     |
|05| **hour**      | Contains at what hour of the day the data was Recorded                  |
|06| **PM2.5**           | Atmospheric particulate matter (PM) that have a diameter less than 2.5 micrometers
|07| **PM10**     | Atmospheric particulate matter (PM) that have a diameter less than 10 micrometers |
|08| **SO2**     | SO2 concentration (ug/m^3)|
|09| **NO2**        | NO2 concentration (ug/m^3)|
|10| **CO**          | CO concentration (ug/m^3)  |
|11| **O3**         | Ozone concentration (ug/m^3) |
|12| **Temp**     | temperature (degree Celsius)  |
|13| **PRES**     | 	pressure (hPa)  |
|14| **DEWP**     | dew point temperature (degree Celsius) |
|15| **RAIN**     | RAIN in (mm) |
|16| **wd**     | wind direction  |
|17| **WSPM**     | wind speed (m/s)  |
|18| **station**     | name of the air-quality monitoring site   |
