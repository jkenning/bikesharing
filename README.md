# Bikesharing

Analysis and visualization of data for over 2 million Citibike rides using Tableau

## Overview

The project involves using Tableau to analyze and visualize Citibike bike sharing data from New York from August 2019. Clear and helpful visualizations will be created so that data can be presented to a non-technical audience in the form of data stories.

### Purpose

In the scenario, the purpose for the study is to explore the possibility of starting a bike share in Des Moines. Citibike data from New York is analyzed to figure out how the bike share business operates and the results could be used to put together a proposal for potential investors for how it would work in Des Moines.

## Resources

Tools and Software: Tableau Public 2021.1, Visual Studio Code 1.54.3, Python 3.7.9, Jupyter Notebook 6.1.4, Anaconda 1.10.0

Datetime format conversion code: [NYC_CitiBike_Challenge.ipynb](https://github.com/jkenning/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)

Tableau Dashboard for initial analyses: [click here](https://public.tableau.com/profile/jack.kenning#!/vizhome/NYC_citibike_16182703800160/NYCCitiBike)

Final Tableau Story: [click here](https://public.tableau.com/profile/jack.kenning#!/vizhome/NYC_citibike_challenge_16182732633520/NYCCitibikeData)

Data source: [citibikenyc](https://www.citibikenyc.com/system-data) (201908-citibike-tripdata), Note: .csv dataset not uploaded due to size

## Results

The results of the analysis are summarized below:

![](https://github.com/jkenning/bikesharing/blob/main/Images/top_starting_locations.png)

Figure 1. Starting locations for each bike trip. Higher numbers of trips start in Manhattan in the city center. This is where some of the main tourist attractions in the city are found and a large number of tourists and visitors in these areas could be a potential cause for the high bike usage. Additionally, it could also be that the population living in this part of the city is higher, or that more people travel to work in this area. Larger numbers of people may also be working in the same high density areas that toursits are likely to frequent due to the abundance of shops, restaurants, etc. It may be that biking is one of the only, or most convenient forms of travel in these parts of the city due to traffic issues or lack of other public transport and people may have arrived to the area by other means before using the bike share. It could be that there are more stations in these areas or that the bike stations have more capacity for bikes.

![](https://github.com/jkenning/bikesharing/blob/main/Images/august_peak_hours.png)

Figure 2. Peak hours for riding during August. The most popular times for rides is in the evening between 5.00 and 7.00 PM. There is also a slightly smaller peak in the mornings between 7.00 and 9.00 AM. These are typically hours that people start and finish work, suggesting that significant numbers of people may be using the bikes for commuting.

![](https://github.com/jkenning/bikesharing/blob/main/Images/checkout_times_for_users.png)

Figure 3. Amount of time bikes are checked out for rides. The vast majority of riders use the bikes for less than 15 minutes (with a mode of around 6 minutes), suggesting most riders use the bikes for very short journeys at a time. Very few riders use the bikes for more than around 50 minutes, suggesting the bikes are using for quick, convenient, and casual use rather than significant workouts or marathons. It is also possible riders may take more than one trip to a make up a larger overall journey, returning bikes between stops rather than hanging on to the bike for extended periods.

![](https://github.com/jkenning/bikesharing/blob/main/Images/checkout_times_by_gender.png)

Figure 4. Bike usage by Gender. Several times more men use the service compared to women, however there are no significant differences in the duration of usage, suggesting men and women exhibit similar riding habits and bike usage. 

![](https://github.com/jkenning/bikesharing/blob/main/Images/trips_by_weekday_by_hour.png)

Figure 5. Number of trips by hour of the day and day of the week. It can be observed that the majority of trips occur during the week in the morning and evening hours, as observed in Figure 2. This supports the hypothesis that the majority of the bike usage may be used to commute to and from work betwen Monday and Friday and the bikes see relatively little usage in the middle of the day (but increasing slightly in the afternoons towards the end of the week as more people take off). Usage patterns across the weekend differ, peak usage is lower but consistently higher numbers of rides occur during the middle of the day and far fewer in the early mornings and mid evenings compared to the typical work weekdays of monday to friday. 

![](https://github.com/jkenning/bikesharing/blob/main/Images/trips_by_gender.png)

Figure 6. Number of trips by gender. Similar to the results from Figure 4. - more men can be observed to use the service than women, however, there are no significant differences in usage for the time of day and days of the week, again suggesting usage habits are similar between the genders.

![](https://github.com/jkenning/bikesharing/blob/main/Images/user_trips_by_gender_by_weekday.png)

Figure 7. Number of trips by gender by weekday, split by customer type. Interestingly, the number of male and female riders who are non-subscribing customers is relatively similar between the sexes and across the length of the week. However it is important to note that similar numbers of riders are unreported so it is possible the data split between the sexes may be less reliable. It is clear that the majority of people using the bike share are subscribers to the service rather than casual customers suggesting this is important to the success of the program. 

For subscribers there are a significantly larger number of men using the service compared to women but the most common days of the week to use the service are similar between the sexes which is consistent with the previous analyses. Among both men and women subscribers, thursday and friday, followed by monday and tuesday show the most number trips occuring. Subscribers may be using the service for day-to-day commuting and are more likely to be locals. Whereas ordinary customers show a slight increase in usage at the weekends and may be visitors to the area or purely recreational users. It is not immediately clear why there are slightly lower numbers of trips on wednesdays for subscribers.

## Summary

1. The majority of trips start in the city center, particularly near major landmarks, this could be due to the presence of tourists, however there are number of potential reasons as described above

2. The most popular times for rides is in the evening between 5.00-7.00 PM, followed by the morning between 7.00-9.00 AM

3. Most riders use the bikes for short journeys of less than 10-15 minutes duration

4. Significantly more men use the service than women however patterns of usage are similar for both genders

5. The highest number of trips occur in the morning and evening from Monday to Friday, peak usage is slightly lower but consistent for hours during the middle of the day for saturday and sunday

6. Subscribers account for the vast majority of rides on the service and are much more likely to be men, which differes to "one-off" customers. Subscribers appear more likely to use the bikes during the week during commuting hours and suggests this demographic may be more important to target than the relatively lower number of rides by weekend-prone, recreational-use customers. This also suggests tourists may not necessarily account for the high numbers of bike journeys starting in Manhattan

**Additional analyses:**

* Analysis performed on data from other months of the year - it is possible more people are using the bikes during the summer months as the weather is better and may not be year-round users. How does the weather differ throughout to year in Des Moines. 

* What is the usage by length of subscription? Are they by year, month, week etc? how does usage differ. Its possible tourists could still be subscribers rather than locals if the majority of subscriptions are for a weeks vacation.

* What is the purpose of a trip? Work, recreation, etc? Can/are people likely to use it for similar reasons in Des Moines?

* How many trips per day and per week do individual users take? It is possible they may take several short journeys in one day rather than one long one which may account for the short trip durations

* What other forms of transport did the user take as part of the same overall journey, or on the same day?

* What are the demographics in terms of sex, income, etc. versus usage or locations of trips, and how does this differ to Des Moines. 

* If lower numbers of women are subscribing to the service than men, why is that? Are the reasons for travel or destinations more common for men or if not, what alternate transportation are they using to get to the same destinations? How do the locations of citibikes relate to levels of crime, etc. 

* Usage versus supply and demand for bikes at different station locations, are the number of rides lower in some areas due to lack of demand or supply of available bikes?

