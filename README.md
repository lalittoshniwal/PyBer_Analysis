# PyBer_Analysis

## Overview of the analysis:

The purpose of this analysis was to create a DataFrame using Pandas to summarize ride-sharing data by city type: rural, suburban, urban. I then plotted the data using Matplotlib in a line graph showing weekly fares for each city type over a course of four months to analyze any trends and make business recommendations to the CEO to address any disparities among different city types.


## Results:

As follows is a print of the DataFrame I created summarizing ride-sharing data which includes the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type:

<img src="/Analysis/PyBer_summary_data.png" >

As follows is the multiple-line graph I created that shows the total weekly fares for each city type:

<img src="/Analysis/PyBer_fare_summary.png" >


## Summary:

Based on my analysis of the data, I would recommend the CEO to consider following to address disparities among the city types:
1. Since we are only analyzing data for a short period, it is hard to predict longer term trends, but it appears that the total fare is growing in urban and suburban cities while it is staying flat in rural cities. Further analysis is needed to understand longer term trends and determine root cause of stagnant growth in rural cities.

2. When compared with urban cities the rural cities have twice the average fare per ride but three times the average fare per driver. So, either the urban cities have too many drivers or rural cities do not have enough drivers. Further analysis is needed to understand trip to driver ratio and determine what is an optimal ratio for rider and driver satisfaction.

3. The rural and sub-urban cities may be underserved. Additional data is needed to analyze wait time for rides to arrive, distance traveled per ride. Accordingly, company may consider campaigns to recruit more drivers in those cities.