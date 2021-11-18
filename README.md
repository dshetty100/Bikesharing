# NYC Bikesharing Analysis

## Overview of Analysis

In this project we analyze NYC CitiBike bike-sharing data from August 2019, using Tableau. The purpose of the analysis is to make a presentation to a potential investor who is interested in developing a bike-share program in Des Moines, Iowa. The analysis is aimed at answering a few key questions:

- Who are the potential users of a bike?
- What time of the day are bikes most used?
- What time of the day they are least used?
- For how long the bikes are used and by whom?
- What days of the week the bike is mostly used?
- What area of a city sees the most bike-share usage?

The entire Tableau story can be seen by clicking at [this link](https://public.tableau.com/app/profile/dinesh.shetty/viz/NYC_Bike_Analysis_16372636521530/NYCityBikeAnalysis?publish=yes)

## Results

### 1. Customer Information
The image below shows that about 3/4 of the bike users are Subscribers, who use the bike regularly. The bike users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.

![Figure1](/Images/customer_info.png)

### 2. Ride Starting Location
The map below shows the bike stations from where bike trips started. The size of the circles and the darkness of the blue indicate the relative number of trips started at those locations. It is observed that the bulk of the bike trips originated from Lower Manhattan, which has a large population density. Bike usage is lower in the surrounding area which is less densely packed.

![Figure1](/Images/ride_starting.png)

### 3. Peak Hour Usage in August
The chart below displays the number of bike rides initiated during each hour of the day for August. 
One observes that the bike usage peaks during morning rush hour and evening end-of-workday commute times. The usage is low between 2 AM and 5 AM.  These would be the best times to conduct bike repairs and redistribution of bikes from full stations to less-full stations.

![Figure1](/Images/peak_hour.png)


### 4. Checkout Times for Users
The checkout times for users graph shows that the majority of trips taken are under an hour in length. More specifically, the trips are under a half-hour in length, with a significant drop in the number of rides over an hour.

![Figure1](/Images/tripduration_usage.png)

### 5. Checkout Time by Gender
The checkout time by gender graph shows that the bike rides are mostly taken by male customers.

![Figure1](/Images/tripduration_gender.png)

### 6. Trips by Weekday Per Hour
The heatmap for trips by weekday per hour shows that the bikes are heavily used during weekday commute times and also during weekends throughout the middle of the day.
One also observes that the usage is low in the early morning hours, every day of the week.

![Figure1](/Images/heatmap_1.png)

### 7. Trips by Gender (Weekday Per Hour)
The heatmap for trips by gender once again reinforce that the bikes are heavily used during weekday commute times and also during weekend throughout the middle of the day.
While the trend is the same for both male and female riders, the male rider seems to dominate the female rider in the bike-sharing program.

![Figure1](/Images/heatmap_2.png)

### 8. User Trips by Gender by Weekday
Lastly, the heatmap below reinforces how much of the user base is dominated by male-identifying, subscribing users. 

![Figure1](/Images/usertrip_gender_weekdays.png)


## Summary

In summary, bike-sharing programs can be a success in densely populated metropolitan areas. The analysis shows that male subscribers tend to be the dominant users of bike-sharing programs. The analysis also indicates that the bikes are heavily used during weekday commute times and also during weekends throughout the middle of the day. The low number of female riders is particularly striking and attracting more female riders could improve the income from the ride-sharing program.

Two additional visualizations that one could perform with the given dataset.
- Average trip duration by age to explore what age group in each gender category prefers bike-sharing.
- A heatmap to determine what proportion of the bikes get heavy usage and which will need to be repaired often.

