# PyBer_Analysis

## Overview of the analysis

### Purpose of the analysis
This analysis involves using the knowledge of Python and Panda to create a summary DataFrame of ride-sharing data by city type. Multiple line graph was created using Panda and Matplotlib to show the total weekly fare for urban, suburban and rural city types. This is rounded up with this written report that summarizes how the data differs by city type and the inferences that can be drawn based on those differences by decision makers at PyBer.

## Results

The datasets for this analysis was merged using left join based on the city column resulting in one dataset. Next, the summary dataframe was created by city type revealing there are few drivers and rides in rural cities with higher average fares compared to urban cities.

![image](https://user-images.githubusercontent.com/91093413/139569784-c87c5cd6-4c40-4b4a-a584-c8d0f9863f09.png)

The total number of rides in urban cities is 13 times more than those in rural cities. The total rides are 1,625 and 125 for urban and rural cities respectively.

Urban areas have more than 4 times the total number of drivers than both rural and suburban cities.

The total fares are 9 times higher in urban cities than in rural cities.

The average fare per ride is 1.4 times less in urban cities than in rural cities – 24.53 and 34.62. The average fare per driver is 3.3 times lower in urban cities than in rural cities – 16.57 and 55.49.

![image](https://user-images.githubusercontent.com/91093413/139569874-7be01a17-8c91-4df7-bc55-0155425860ef.png)

The weekly multiple line graph shows the total weekly fares for urban, suburban and rural cities. The line plot for urban cities (yellow line) is higher than the line for suburban and rural cities. The trend shows that PyBer has higher total fares and revenue in urban cities compare to suburban and rural cities.

![image](https://user-images.githubusercontent.com/91093413/139570132-9858e993-8dd7-4950-9a33-48f5209e02b9.png)

## Summary

There is the need to focus on profitability of urban cities rides because urban rides make more revenue but rural cities record more profit.

There is also the need to reduce the number of drivers in urban cities. The current 2,405 number of drivers far exceeded the 1,625 rides.

Calculating the average fare per minute or kilometre will give an insight and enable comparison of the value among city types. A higher 1 minute ride in rural cities compare to the fare in urban cities might lead to increase in ride fare in urban cities and this might lead to an even higher revenue in these cities.


Jupyter notebook

Pandas

Matplotlib
