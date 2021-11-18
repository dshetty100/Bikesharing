# NYC Bikesharing Analysis

## Overview of Analysis

In this project we analyze NYC CitiBike bikesharing data from August, 2019, using Tableau. The purpose of the analysis is to make presentation to a potential investor who is interested in developing a bikeshare program in Des Moines, Iowa. The analysis is aimed at answering few key questions:

- Who are the potebtail users of bike?
- What time of the day bikes and most used?
- What time of the day they are least used?
- For how long the bikes are used and by whom?
- What days of the week the bike are mostly used?
- What area of a city sees the most bikeshare usage?

The entire Tableau story can be seen by clicking at [this link](https://public.tableau.com/app/profile/dinesh.shetty/viz/NYC_Bike_Analysis_16372636521530/NYCityBikeAnalysis?publish=yes)

## Results

### 1. Customer Information
The image below shows that about 3/4 of the bike users are Subscribers, who use bike regularly. The bike users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.

![Figure1](/Images/customer_info.png)

### 2. Ride Starting Location
The map below shows the bike stations from where bike trips started. The size of the circles and darkness of the blue indicate the relative number of trips started at those locations. It is observed that the bulk of the bike trips originated from Lower Manhattan, which has a large population density. Bike usage is lower in the surrounding area which is less densely packed.

![Figure1](/Images/ride_starting.png)

### 3. Peak Hour Usage in August
The chart below displays the number of bike rides initiated during each hour of the day for the month of August. 
One observes that the buke usage peaks during morning rush hour and evening end-of-workday commute times. The usage is low between 2 AM and 5 AM.  This would be the best times to conduct bike repairs and redistribution of bikes from full stations to less-full stations.

![Figure1](/Images/peak_hour.png)


### 4. Checkout Times for Users
The checkout times for users graph shows that the majority of trips taken are under an hour in length. More specifically, the trips are under a half-hour in length, with a significant drop in number of rides over an hour in length.

![Figure1](/Images/tripduration_usage.png)

### 5. Checkout Time by Gender
The checkout time by gender graph shows that the bike rides are mostly taken by male customers.

![Figure1](/Images/tripduration_gender.png)

### 6. Trips by Weekday Per Hour
The heatmap for trips by weekday per hour shows that the bikes are heavily used during weeday commute times and also during weekend throughout the middle of the day.
One also observes that the usage is low in the early morning hours, every day of the week.

![Figure1](/Images/heatmap_1.png)

### 7. Trips by Gender (Weekday Per Hour)
The heatmap for trips by gender once again reinforce that the bikes ar heavily used during weeday commute times and also during weekend throughout the middle of the day.
While the trend is the same for both male and female riders, the male rider seems to dominate the female rider in the bike sharing program.

![Figure1](/Images/heatmap_2.png)

### 8. User Trips by Gender by Weekday
Lastly, the heatmap below reinforces how much of the userbase is dominated by male-identifying, subscribing users. 

![Figure1](/Images/usertrip_gender_weekdays.png)


## Summary
In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.
