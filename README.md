# Bikesharing
[link to dashboard](https://public.tableau.com/profile/eunji.chung#!/vizhome/Bikesharing_16157419224070/Bikesharing)
## Overview of the statistical analysis:
The purpose of this analysis was to assist the key stakeholders in solidifying the proposal by creating a visualization for a bike trip analysis. For the analysis, Pandas was used to change the "tripduration" column from an integer to a datetime datatype. Using the converted datatype, a set of visualizations were created to show the following:
- The length of time that bikes are checked out for all riders and genders</br>
- The number of bike trips for all riders and genders for each hour of each day of the week</br> 
- The number of bike trips for each type of user and gender for each day of the week</br> 

## Results:
A majority of bike users would check out bikes within the first 4-7 minutes of the opening hour, but there are more males who checked out bikes than females.  
![checkout](https://github.com/echuung94/bikesharing/blob/main/images/checkout.png)

The visualizations below show that throughout the weekday, a majority of riders are taken between 5PM-7PM with more males riders as well. 
![weekdaytrips](https://github.com/echuung94/bikesharing/blob/main/images/weekdaytrips.png)

The heatmap chart below shows that both women and men are riding bikes during commuting hours - from 6AM-9AM and 4PM-7PM. 
![tripsbygender](https://github.com/echuung94/bikesharing/blob/main/images/tripsbygender.png)

In the month of August, the peak for customer bike rides was from 5 PM to 7PM. Bike riding activity from 2AM to 4AM is the lowest, so that would be the best time for any bike maintenance. The circle chart below shows a total usage time per bike along with which bikes were used the most frequently. The largest bubble shows that bike ID 39570 was the highest with a duration of 3,838,467. 
![augustpeak](https://github.com/echuung94/bikesharing/blob/main/images/augustpeak.png)
![bikeutilization](https://github.com/echuung94/bikesharing/blob/main/images/bikeutilization.png)


## Summary:
The gathered data shows that the highest amount of bikeshare activity occurred in the month of August. Majority of the rides were taken by male users during the morning and evening. The visualizations show that a significant amount of bikes are used as an alternative method of transportation in New York by commuting females and males. 
</br> 
Two additional visualizations: 
- Compare other months besides August to see when it would be most effecient to run the bikeshare service. 
- Include weather in the analysis, weather could affect the usage of bikes during commuting hours. 
