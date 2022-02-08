# NY Citibike Challenge

## Overview
Using data collected from the Citi Bike ridership in New York City, the goal is to create visualizations in Tableau to identify trends that will inform a proposal to launch a bike sharing service in Des Moines, Iowa.

## Results
In order to visualize rider data by time of day, the original data file was cleaned using Pandas to convert the integer data type for Trip Duration into an hour of the day.

[NYC_CitiBike_Challenge.ipynb](https://github.com/rptseng/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)

The cleaned file was then fed into Tableau and the below story was created using various visualizations:

[Link to Story](https://public.tableau.com/app/profile/ryan.tseng/viz/NY_citibike/NYCitibike)

### Number of Riders by Gender
By count of total riders by gender, we observe that a majority of riders are male. This gives an indication of the demographic of the riders.
![gender_breakdown.png](https://github.com/rptseng/bikesharing/blob/main/resources/images/gender_breakdown.png)

### Top Starting Locations
Using coordinate data for the stations, we observe that large portion of rides are likely to occur in the middle of the city while the stations on the perimeter are used less frequently.
![top_starting_locations.png](https://github.com/rptseng/bikesharing/blob/main/resources/images/top_starting_locations.png)

### Checkout Times
This graphic shows how long riders are using the bike per trip. The most frequent travel duration on Citi bikes are around 10 minutes, and very few trips last longer than one hour.
![checkout_times.png](https://github.com/rptseng/bikesharing/blob/main/resources/images/checkout_times.png)

### Checkout Times by Gender
Similar to the previous chart, we can see the frequencies of trip duration separated by gender.
![checkout_times_by_gender.png](https://github.com/rptseng/bikesharing/blob/main/resources/images/checkout_times_by_gender.png)

### Trips by Weekday per Hour
This heat map demonstrates that the highest usage period for rides within a day are between 7am-9am and 5pm-7pm on Mon-Fri. It would be important to know this information to decide when to service and repair the bikes when they are not as likely to be in use.
![trips_by_weekday_per_hour.png](https://github.com/rptseng/bikesharing/blob/main/resources/images/trips_by_weekday_per_hour.png)

### Trips by Gender
Like the previous chart but separated by gender, this heat map seems to indicate there is no major difference in ride stop time patterns between genders.
![trips_by_gender.png](https://github.com/rptseng/bikesharing/blob/main/resources/images/trips_by_gender.png)

### Trips by Gender by User Type
Plotting the number of rides by user type and gender, it appears that subscribers are much more likely to take trips than regular customers.
![user_trips_by_gender.png](https://github.com/rptseng/bikesharing/blob/main/resources/images/user_trips_by_gender.png)

## Summary
From visualizing this data set, we may be directed to draw the following assumptions:
- The majority of riders are males that are subscribers.
- A majority of rides will be for a relatively short time; around 10 minutes.
- Peak hours of usage are between 7am-9am and 5pm-7pm.

Below is the picture of the presentation of this data in a Tableau story.

![citibike_story_1.png](https://github.com/rptseng/bikesharing/blob/main/resources/images/citibike_story_1.png)

### Future Recommendations
There are a few other parameters in this data set that we can gain additional insights from. We could further investigate the most common distance travelled by riders based on the starting and ending position of each ride. We may also consider looking at the age demographic (Birth Year) across user types (Subscribers vs Customers)


