# NYC Citibike
[NYC August Citibike Dashboard](https://public.tableau.com/app/profile/conor.mcgrane/viz/NYCCitibikeAugust/NYCCitibikeAugust?publish=yes)
## Overview of Analysis
### Purpose
The purpose of this analysis was to look at bike sharing data from the company citibike in the city of New York, in order to determine whether it would be a good investment to start a similar bike sharing program in Des Moines, Iowa.  In order to show the advantages of such a bike sharing program, several criteria have been analyzed which can impact the success of bike sharing.
### Analysis and Challenges
In order to perform the analysis, citibike data from the month of August in New York city was added to Tableau Public, and then utilized to make a variety of visualizations as well as a story which shows the significance of each visualization.  In order to make some of the data usuable, the trip durations (which were in second format) had to be reformatted to datetimes so that they could be used to create continuous data for line charts.  
## Results
### Overview of rides in NYC in August

#### Total Rides
![Total_Rides](https://github.com/conpm/bikesharing/blob/main/Analysis/Total_Rides.PNG)
- This dashboard shows two basic visualizations, one simply showing the total ride count in NYC in the month of August, and one showing the distribution of rides based on the time of day they were taken.

#### Ride Count vs Trip Duration
![Ride_Count_vs_Duration](https://github.com/conpm/bikesharing/blob/main/Analysis/Ride_Count_vs_Duration.PNG)
- This visualization shows the number of bikes used based on the duration of the trip.  It shows that the vast majority trips last for less than 20 minutes and that the most common duration for a trip is around 5 min.

#### Ride Count vs Weekdays
![Rides_vs_Weekdays](https://github.com/conpm/bikesharing/blob/main/Analysis/Rides_vs_Weekdays.PNG)
- This visualization serves as a deeper look at the initial visualization of trips based on time of day.  In this visual we can see how the distribution of trips throughout the day changes between different days of the week.  Notably, the distribution is similar from Monday - Friday, while there is lower peak usage during the weekends.  Additionally, the peaks are during commuting hours on the weekdays, but during the weekends, the peaks take place during traditional working hours.

#### Gender Breakdown
![Gender_Breakdown](https://github.com/conpm/bikesharing/blob/main/Analysis/Gender_Breakdown.PNG)
- This dashboard displays 3 different visuals, the primary new visual is the gender breakdown pie chart which shows the distribution of total rides based on gender.  The other two visuals in this dashboard serve as deeper analyses of the previous two visuals ('Ride Count vs Trip Duration' and 'Ride Count vs Weekdays').  This version of those visuals breaks down the total ride counts to show the ride counts for each gender separately.  Additionally, in the Tableau Public story for this dashboard, you can select one of the genders to have it highlight the specific data for the selected gender.

#### Usertype Breakdown
![User_Breakdown](https://github.com/conpm/bikesharing/blob/main/Analysis/User_Breakdown.PNG)
- This visualization breaks down the total ride count based on three different criteria, those being weekday, gender, and usertype.  This chart shows gender and weekday trends that reflect previous data.  In addition, this visualization shows that the majority of users of the bike sharing service are subscribers rather than one time customers.  This means that most of the people who use the bike sharing service likely use it regularly.

#### Starting and Ending Locations
![Starting_Ending](https://github.com/conpm/bikesharing/blob/main/Analysis/Starting_Ending.PNG)
- This final visualization shows the starting and ending locations of bike sharing rides, with larger and darker points showing higher numbers of rides.  Using these maps we can see that most of the rides both start and end in urban centers.

## Summary
Through this series of analyses and visualization we can see that Citibike has a consistant userbase who regularly use their bike sharing service.  Additionally, by using the information about peak hours, we can infer that the most common type of users for bike sharing services are commuting workers who live in urban areas.  Also we can see that most of the users are subscribers, meaning that Citibike can expect regular payments from them regardless of how much they used the bike sharing services over the month.  Finally, we can see that the majority of users are men, however, this is not very significant for the area of Des Moines as they do not have any significant difference in the number of men to other genders.  In order to determine how this data will translate to Des Moines, I think it is important to understand the distribution housing of the population of Des Moines as well as the distribution employment locations.  We know from out ride count vs trip duration visualization that most people do not ride the citibikes for more than 20 minutes and therefore we would want to know how far the average commute in Des Moines is.  For additional visualizations which could be created from our current data, I think it would be helpful to create a visualization of cost of maintaining the service, by using a count of the BikeIds as well as their repair frequencies.  I also think it would be useful to see the frequency of bike trips which start at popular starting points and end in less common ending points, as if most of the trips are taken in urban areas it could lead to a need to move bikes back to urban areas if they stay in less common starting/ending points for prolonged periods of time.
