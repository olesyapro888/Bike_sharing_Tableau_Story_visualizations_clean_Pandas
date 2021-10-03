# Bikesharing analysis. Project 14 of the UofT.
## `-Contents-`	
	
- [Overview of the Project](#overview-of-the-Bikesharing-Analysis)	
- [Resources](#resources)	
- [The Bikesharing Analysis Result](#Bikesharing-Analysis-Result)	
  - [The cleaning data for the NYC Citibike analysis](#The-cleaning-data-for-the-NYC-Citibike-analysis)	
  - [Seven visualizations for the NYC Citibike analysis](#Seven-visualizations-for-the-NYC-Citibike-analysis)
  - [Story for the Final Presentation](#Story-for-the-Final-Presentation)
- [The Bikesharing Analysis Summary](#Bikesharing-Analysis-Summary)	
## `Overview of the Bikesharing Analysis`	
	
The purpose for the bikesharing analysis challenge is to create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis with a set of visualizations:
  - The length of time that bikes are checked out for all riders and genders.
  - The number of bike trips for all riders and genders for each hour of each day of the week.
  - The number of bike trips for each type of user and gender for each day of the week.
  - The customer trips analysis by age and for each day of the week.

## `Resources`	
The analysis is created using next software: Python 3.8.8, Pandas 1.2.4, Jupyter-notebook 6.3.0, Tableau Public 2021.3.	
## `Bikesharing Analysis Result`	
### `- The cleaning data for the NYC Citibike analysis`	

To use datetime data correctly it needs to convert the "tripduration" column from an integer to a datetime datatype by Pandas. The result of that can be found in the [Bikesharing_Challenge](./NYC_Citibike_Challenge.ipynb) file.	
### `- Seven visualizations for the NYC Citibike analysis`	

First 2 visualizations are to show how long bikes are checked out for all riders and genders.

screen db Checkout

 Next, How many trips are taken by the hour for each day of the week, for all riders and genders.

 A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender

 screen db Weekday

Additionally, as learning other details about the riders will further assist the analysis. So, there are two visualizations that show usertype trips by weekday and by age. 

screen db Usertype
### `- Story for the Final Presentation`	

Create a Story and Report for the Final Presentation

[link to dashboard](https://public.tableau.com/app/profile/olesya.irkhina/viz/Challenge14_5_16332597080320/Stories_Keyfindings?publish=yes)

screen Stories

## `Bikesharing Analysis Summary`	

The analysis provides a lot of summarizing. But the main are:
