# Boombikes Linear regression assignment
> Linear Regression performed on the Boombikes bike rental dataset identifying the features that have influence on demand of bike hire.


## Table of Contents

## General Information

Multiple linear regression is performed on the dataset.

We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc.

The Boombikes bike rental dataset is being used

## Conclusions

The R-squared value of the train set is 82.77% whereas the test set has a value of 79.98% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

We can conclude that the bike demands for the BoomBikes is company is dependent on the temperature and whether it is a workingday or not, demand is lower on non-working days. Additionally more rentals seem to be demanded on the winters as compared to the summer. We had observed that the months of August and September had higher use of rentals. In terms of weather, the demand is lower during snowy, misty and cloudy weather.

These interpretations help us derive meaningful insights in the bike rental market and the behaviour of the people. One of the recommendations based on this model are that there should be aggressive marketing in the summer and spring season to drive up rentals. Since the summer months also show low rental levels, a strong marketing strategy for the first 6 months of the year can assist in driving up the rental numbers. There has to be an approach required to introduce more users on days where the weather is less clear, perhaps with incentives or strategic deals. Rentals were more in 2019 than 2018 which suggests that over time more people would be exposed to this idea and there has to a strong analysis done to retain the repeat customers.


## Technologies Used

pandas
seaborn
matplotlib
statsmodels
sci-kit learn
numpy


## Contact
Created by [@sang2012] - feel free to contact me!