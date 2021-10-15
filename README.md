# NYC Bike-Sharing Data 

## Project Overview

### Purpose
Use New York Citi Bike data and Tableau to present a business proposal for a bike-sharing company in Des Moines.

### Resources ###
- Data Source: 201908-citibike-tripdata.csv (via https://ride.citibikenyc.com/system-data)
- Software: Tableau Public 2021.3.1; Jupyter Notebook 6.3.0

## Analysis ##

### Results ###

The results of the analysis are described below, with the screen shots taken from the Tableau Story [linked here](https://public.tableau.com/shared/QTSRTRWWS?:display_count=n&:origin=viz_share_link).

![](/Resources/Dashboard.png)
The first page in the Tableau Story is a dashboard summarizing the New York dataset.  The two maps show the top starting and top ending locations from the 2,344,224 total number of rides.  While the maps show a heavy concentration in a tourist-heavy area, you can see there are a large number of popular starting and ending locations further away. These are most likely from residents and suggests that bike-sharing is not just for tourists. 

![](/Resources/1_Times.png)
The second page in the Story groups the checkout times by minute (separated by hour-intervals) shows the most frequent number of rides  of rides are 5-10 minutes; however, the data is skewed to the right meaning that the average ride is longer and a significant number of rides are between 15 and 45 minutes.  

![](/Resources/2_TimesbyGender.png)
The third page in the Story adds more detail to the previous page, breaking down the checkout times by gender. As you can see, a large majority of bikes are rented by men which can be expected in Des Moines as well. 

![](/Resources/3_TripsbyWeekday.png)
The fourth page in the Story shows the number of bike trips by weekday for each hour of the day as a heatmap, showing most rides occur during the week before or after work hours (which are more "red"). This suggests that many users use bike-sharing as their mode of transportation, further illustrating the potential in any city. 

![](/Resources/4_TripsbyGender.png)
The fifth page in the Story adds more detail to the previous page by breaking down the heatmap by gender. The results show that the service is used most frequently by men during the week before or after work hours, which again can be seen as a potential market in another city. 

![](/Resources/5_GenderbyWeekday.png)
The final page in the Story is another heat map of the number of bike trips by weekday by gender with an additional grouping by user type. Here we see that most users are subscribers and once again predominately male. This is further evidence of the notion that the service is not tourist-dependent and can be profitable in other cities.  


### Summary ###
Based on the provided data, it can be assumed that a bike-sharing business would do well in Des Moines. If potential investors are still undecided, it is recommended that the following analysis & visualizations be added to the project:
1. A breakdown of the number of bikes rented from each station.
2. A heatmap of the number of bikes rented by weekday by age.  

Again the visualizations displayed here can be accessed and interacted with (e.g. filters) from the Tableau Story [linked here](https://public.tableau.com/shared/QTSRTRWWS?:display_count=n&:origin=viz_share_link).
