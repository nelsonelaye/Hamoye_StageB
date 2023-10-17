# Hamoye_StageB

HDSC Fall'23 - Machine Learning: Regression - Predicting Energy Efficiency of
Buildings

This project is my tag-along project for the HDSC (Fall'23) Stage B quiz
(question 17-25) Predicting Energy Efficiency of Buildings

## Dataset

The dataset used in this tag-along project is the
[Application energy prediction](https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction)
dataset from the [UC Irvine ML repository](https://archive.ics.uci.edu/)

### Dataset Information

The data set is at 10 min for about 4.5 months. The house temperature and
humidity conditions were monitored with a ZigBee wireless sensor network. Each
wireless node transmitted the temperature and humidity conditions around 3.3
min. Then, the wireless data was averaged for 10 minutes periods. The energy
data was logged every 10 minutes with m-bus energy meters. Weather from the
nearest airport weather station (Chievres Airport, Belgium) was downloaded from
a public data set from Reliable Prognosis (rp5.ru), and merged together with the
experimental data sets using the date and time column. Two random variables have
been included in the data set for testing the regression models and to filter
out non predictive attributes (parameters).

This
[github repository](https://github.com/LuisM78/Appliances-energy-prediction-data)
provides more information about the house, data collection, R scripts and
figures

## Features

- T1, Temperature in kitchen area, in Celsius
- RH_1, Humidity in kitchen area, in %
- T2, Temperature in living room area, in Celsius
- RH_2, Humidity in living room area, in %
- T3, Temperature in laundry room area
- RH_3, Humidity in laundry room area, in %
- T4, Temperature in office room, in Celsius
- RH_4, Humidity in office room, in %
- T5, Temperature in bathroom, in Celsius
- RH_5, Humidity in bathroom, in %
- T6, Temperature outside the building (north side), in Celsius
- RH_6, Humidity outside the building (north side), in %
- T7, Temperature in ironing room , in Celsius
- RH_7, Humidity in ironing room, in %
- T8, Temperature in teenager room 2, in Celsius
- RH_8, Humidity in teenager room 2, in %
- T9, Temperature in parents room, in Celsius
- RH_9, Humidity in parents room, in %
- To, Temperature outside (from Chievres weather station), in Celsius
- Pressure (from Chievres weather station), in mm Hg
- RH_out, Humidity outside (from Chievres weather station), in %
- Wind speed (from Chievres weather station), in m/s
- Visibility (from Chievres weather station), in km
- Tdewpoint (from Chievres weather station), Â°C
- rv1, Random variable 1, nondimensional
- rv2, Random variable 2, nondimensional

## Additional resource

Article on
[Data driven prediction models of energy use of appliances in a low-energy house](https://www.sciencedirect.com/science/article/abs/pii/S0378778816308970?via%3Dihub)
