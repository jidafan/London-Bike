# London Bike Share Dashboard

## Table of Contents
* [Introduction](#introduction)
* [Data Overview](#data-overview)
* [Data-Cleaning](#data-cleaning)
* [Conclusion](#conclusion)

## Introduction

Commuting through a city is a hassle, whether driving, walking or biking. The London Bike Share Program is one of the most cost-effective ways to traverse the city. However, its usage of it seems to be affected by weather conditions, wind speed, and temperature. This project will aim to create a visualization to showcase these findings.

## Data Overview

The data used in this project comes from the London Bike Sharing Dataset on Kaggle. The data can be viewed [here](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/data).
| Variable      | Description           | 
| ------------- |:---------------------| 
| `timestamp`     | The time and data for when the data was obtained    |
| `cnt`     | The count of new ride shares      |   
| `t1` | The real feel of the temperature in C                                       |
| `t2`     | The feels like of the temperature in C   |
| `hum`     | The percentage of humidity      |   
| `wind_speed` | Windspeed in km/h                                   |
| `weather_code`     | The category of weather on the given day   |
| `is_holiday`     | Boolean variable for if it is a holiday or not      |   
| `is_weekend` | Boolean variable for if it is a weekend or not                           |
| `season` | Category field for which season it is                         |

## Data Cleaning

To data cleaning code can be viewed [here](https://github.com/jidafan/London-Bike/blob/main/datacleaning.ipynb)

Here are the steps we will follow to clean the data:

* Import the data
* Explore the data
* Changing column names
*Writing to excel file

## Results

The tableau dashboard can be viewed [here](https://public.tableau.com/app/profile/scott.duong8287/viz/LondonBikeShare_16994113330510/Dashboard1)

