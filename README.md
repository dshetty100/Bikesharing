# NYC Bikesharing Analysis

## Overview of Analysis

In this project we analyze NYC CitiBike bikesharing data from August, 2019, using Tableau. The purpose of the analysis is to make presentation to a potential investor who is interested in developing a bikeshare program in Des Moines, Iowa. The analysis is aimed at answering few key questions:

- Who uses bikeshare programs?
- What area of a city sees the most bikeshare usage?
- What time of day are bikes used the most and the least?
- How much are the bikes used and by whom?

The entire Tableau story can be seen by clicking at [this link](https://public.tableau.com/app/profile/dinesh.shetty/viz/NYC_Bike_Analysis_16372636521530/NYCityBikeAnalysis?publish=yes)

## Results

### 1. Customer Information
The image below shows that more than 3/4 of the users are Subscribers, who make regular use of the bikes and are a predictable source of income for the program. Bikeshare program users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.

![Figure1](/Images/customer_info.png)

### 2. Ride Starting Location
The map below displays the bike stations from which recorded bike trips started. The size of the circles and darkness of the green indicate the relative number of trips started at those locations. It is apparent that the bulk of the bike trips are originating in the bustling commercial heart of Lower Manhattan, known for towering office buildings, densely packed residential skyscrapers, and entertainment venues. Bike usage is lower in the less densely packed surrounding neighborhoods.

![Figure1](/Images/ride_starting.png)

### 3. Peak Hour Usage in August
The chart below displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August. We can see peak usage during morning rush hour and end-of-workday commute times. What is also of note is the low-usage hours between 2 AM and 5 AM. These hours would be the best times to conduct bike repairs and redistribution of bikes from full stations to less-full stations.

![Figure1](/Images/peak_hour.png)


### 4. Checkout Times for Users
This graphing of number of trips by duration show that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.

![Figure1](/Images/tripduration_usage.png)

### 5. Checkout Time by Gender
This breakdown of number of rides by duration, separated by gender, makes it even more apparent how many more rides are taken by male-identifying customers.

![Figure1](/Images/tripduration_gender.png)

### 6. Trips by Weekday Per Hour
A heatmap also helps show weekly usage patterns. Once again we can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours, every day of the week.

![Figure1](/Images/heatmap_1.png)

### 7. Trips by Gender (Weekday Per Hour)
![Figure1](/Images/heatmap_2.png)

### 8. User Trips by Gender by Weekday
Lastly, this heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.

There are one or two additional charts available in the Tableau analysis, but they tell pretty much the same story that has already been displayed above.

![Figure1](/Images/usertrip_gender_weekdays.png)


## Summary
In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.
