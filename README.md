# Bike-sharing set of interactive visualizations using Pandas and Tableau.

## `-Contents-`	
	
- [Overview of the Project](#overview-of-the-Bikesharing-Analysis)	
- [Resources](#resources)	
- [The Bikesharing Analysis Result](#Bikesharing-Analysis-Result)	
  - [The cleaning data for the Bikesharing analysis](#the-cleaning-data-for-the-Bikesharing-analysis)	
  - [Seven visualizations for the Bikesharing analysis](#seven-visualizations-for-the-Bikesharing-analysis)
  - [Story for the Final Presentation](#Story-for-the-Final-Presentation)
- [The Bikesharing Analysis Summary](#Bikesharing-Analysis-Summary)	

## `Overview of the Bikesharing Analysis`	
	
The purpose of the bikesharing analysis challenge is to create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis with a set of visualizations:
  - The length of time that bikes are checked out for all riders and genders.
  - The number of bike trips for all riders and genders for each hour of each day of the week.
  - The number of bike trips for each type of user and gender for each day of the week.
  - The customer trips analysis by age and for each day of the week.

## `Resources`	
The analysis is created using next software: Python 3.8.8, Pandas 1.2.4, Jupyter-notebook 6.3.0, Tableau Public 2021.3.	

## `Bikesharing Analysis Result`	
### `- The cleaning data for the Bikesharing analysis`	

To use datetime data correctly it needs to convert the "tripduration" column from an integer to a datetime datatype by Pandas. The result of that can be found in the [Bikesharing_Challenge](./NYC_Citibike_Challenge.ipynb) file.	
### `- Seven visualizations for the Bikesharing analysis`	

First 2 visualizations show how long bikes are checked out for all riders and genders. 
So, the chart "Checkout Times for Users" shows that almost 80% of all checked out times is less than 20 minutes and 50% is less than 10 mins for checked out times for all riders. As male customers are 65% and female line chart shows the same graph it allows to say that almost 80% of all checked out times is less 20 minutes for genders.

![image](https://user-images.githubusercontent.com/68247343/135767508-e601fa45-c5db-4ed1-9fb8-d96378a78aae.png)

Next visualizations show the trips are taken by the hour for each day of the week for all riders and genders.

So, the heatmap chart shows that the most of busy weekdays are 8am-9am from Monday to Friday and weekends are from 10am-5pm for all riders.

Also, as male customers are 65% it allows to say that the heatmap chart shows the same tendance of number of bike trips for the same hours during weekdays by genders.

![image](https://user-images.githubusercontent.com/68247343/135767525-3ed5b4ea-bb26-4682-8353-cf0cd2ea84e7.png)

Additionally, as learning the rider customers will important assist the analysis there are two visualizations that show usertype trips by weekday and by age. 

So, the bar charts show that the most occupied weekdays are Thursday and Fridays for Subscribers and Saturdays and Sundays for Customers.
However Customers have longer trips then Subscribers.

If we take a look at the area chart "Usertype trips by Age" which shows that young riders use a bike more often then older. But Customers have longer trips then Subscribers for all ages. 

![image](https://user-images.githubusercontent.com/68247343/135767537-bd5ea111-8bb1-4808-9f16-4116b2300de1.png)

### `- Story for the Final Presentation`	

The created Story for the Final Presentation can be found in the following link:

[link to dashboard](https://public.tableau.com/app/profile/olesya.irkhina/viz/Challenge14_5_16332597080320/Story_Keyfindings?publish=yes)

![image](https://user-images.githubusercontent.com/68247343/135767557-98e5d828-f680-4ec7-bb14-6043e6c6cda9.png)

## `Bikesharing Analysis Summary`	

The analysis provides a lot of summarizing. 
But the main show following:
- Almost 80% of all checked out times is less than 20 minutes and 50% is less than 10 mins for checked out times for all riders. As male customers are 65% and female line chart shows the same graph it allows to say that almost 80% of all checked out times is less 20 minutes for genders.

- The most of busy weekdays are 8am-9am from Monday to Friday and weekends are from 10am-5pm for all riders.
Also, as male customers are 65% it allows to say that the heatmap chart shows the same tendance of number of bike trips for the same hours during weekdays by genders.

 - The most occupied weekdays are Thursday and Fridays for Subscribers and Saturdays and Sundays for Customers. However Customers have longer trips then Subscribers. Additionally young riders use a bike more often then older, but Customers have longer trips then Subscribers for all ages. 
