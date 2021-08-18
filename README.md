# Electricity-Consumption-Prediction

Prediction Using Machine Learning Models



Data Preprocessing
Electricity and Weather Data is loaded by using Pandas. Convert the time format in both the datas to EST, Rename Date & Time in weather data
to time and merge the two data sets on the column time.

Data Analysis
Daily Consumption, Average Daily Consumption and Monthly Consumption were calculated for Analyzing the Data. From Average Daily Consumption and Monthly 
Consumption we can find on which days and which month the Power consumption is high respectively and prevent the high consumption on those days and months
in the future.

Features Generation
I Generated the following features using the existiing features. These features values are added to the data to help us get more accurate predictions: We use this 
feature set for Linear Regression, Random Forest and XGBoost Regressor models.

1. Weekend
During the weekdays the Power consumption is uniform whereas during the weekends the consumption fluctuates because on weekends people don’t go to their jobs
and they may spend their entire weekend in the home increasing the Power Consumption or may go on a trip decreasing the Consumption.

2. Season
Power consumption will vary Season to Season. For example, If we take Winter Power Consumption is high due to heating requirements, If we take Summer Power
Consumption is high due to the high usage of Air Conditioners and If we compare the above with the Spring then the Power Consumption is less as it does not 
require the above requirements.

3. Sleep
As the Human Activity is less to none during the sleeping hours the Power Consumption is low and lesser than that of the day. During the day we use light bulbs and other
appliances so Power Consumption is High.

