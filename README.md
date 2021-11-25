# PyBer_Analysis

Week 5 of Columbia's DS Bootcamp
---
## Overview of Pyber ride share project
The purpose of this project was to perfom an analysis on PyBer to determine rider-ship and fare costs from city to city. Using Pandas and Python I created a summary DataFrame that held the metrics needed to create tables and visualizations via matplotlib. The visualization, a multiple-line graph, showed the total weekely fares for each city type and allowed for a clearer understanding of the data. The multiple-line graph as seen below allows for an easy interpretation.  

## Results
Created a ride-sharing summary dataframe by city type by:
* Getting the total rides for each city type
* Getting the total drivers foreach city type
* Retrieve thte total amount of fares for each city type
* Calculate the average fare per ride for each city type
* Calculate the average fare per driver for each city type
* Created the data frame and formated the columns  
![PyBer data frame table](https://user-images.githubusercontent.com/48603147/143360311-40e98c09-5a69-4982-8f4c-1d098bb8bd00.png)

From the results we can infer that:
* There were 125 Rural rides, 625 Suburban rides and 1625 Urban rides
  * For every Rural ride there was 5 Suburban rides and 13 Urban rides
* There were 78 Rural drivers, 490 Suburban divers and 2405 Urban drivers
  * For every Rural driver there was 6.28 Suburban drivers and 30.93 Urban drivers    
From these results alone we can see that there is a surplus of drivers in Urban cities when looking at the ratio of rides to drivers. There are 30X more Urban drivers then rural drivers while there were only 13X more Urban rides then Rural rides. We can see how this impacts the average fare per driver in the PyBer ride share table.
* Average fare per driver in the Rural locations was at $55.49, Suburban avereage fare per driver was at $39.50 and Urban avereage fare per driver was at $16.57
---
## Summary
