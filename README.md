



## Motivation

This project is part of Udacity Data Science Nanodegree program. Here, I analyzed the Airbnb Boston Listings dataset from 2019, which includes descriptions of amenities, location, and price for each listing. As part of the program, I also wrote a blog post on the findings. You can find it on Medium.com

## Objectives

Following the CRISP-DM methodology, I tried to find insights and build two models aim to explain and predict property prices as follows:

1. Most common `property_type` and `room_type` and their impact on bookings, measured by `booking_percentage_30`;

2. Most common `amenities` available and how they attract bookings;  

3. Build an ML model that predicts property `price` based on the most popular and common features of the listings

4. Correlation heatmap for some of the most prominent `features_of_interest`;

5. `price` spreads based on location: evenly or unevenly?; 

6. Build a linear regression model that explains to what extent distance from Boston downtown predicts variations in property `price`.


## Libraries Used

```python
1. Numpy
2. Pandas
3. Matplotlib pyplot
4. Sklearn
5. Seaborn
6. Math
7. Folium
```
## Results 

1. The most common `room_type` are Entire home/apt and Private Room.  The most common `propety_type` are Apartment, House, Condominium,
and Bed & Breakfast. However, results show that Private Room type is preferred over Entire home/apt and Apartments are as much popular as Bed & Breakfast;

2. The most common `amenities` are Internet, Heating, Kitchen, Essentials, Dryer, Smoke Detector. However, only Smoke Detector turns out to be increasing the booking percentage by almost 15%;

3. The R squared value of our model is 0.22. It means that a full 22% of the variation of property price is explained by our model;

4. The Heatmap shows the highest correlations  for `price` are with `bedrooms`, `beds`, `accommodates`, `cleaning_fee`, and `latitude` and `longitude`; 

5. `price` does not necessarily evenly spread, as in decreasing, from Boston downtown outwards;

6. The model has an R squared value of 0.23, meaning that 23% of the variation in the prices is explained alone by the distance from Boston downtown. More specifically, for each kilometer distance from downtown, the property price drops around 15 USD. 






## Deployment
Code can be run on Jupypter notebook command.

## Acknowledgements
Thanks to Kaggle and AirBnb for the dataset and Udacity for the course.
