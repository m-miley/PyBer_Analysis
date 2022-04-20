# PyBer_Analysis

Resources
- Python 3.9.7, Jupyter Notebook
- Data: city_data.csv, ride_data.csv

## Overview

PyBer is a python-based ride sharing application. This analysis is performed on 4 months of ride sharing data for the start of 2019 to glean insights into the profitability and distribution of rides and drivers based on city type categories.  We will look at summary statistics as well as average fares and average driver counts for rural, suburban, and urban cities so that PyBer may make informed decisions.

Furthermore, this analysis presents visualizations using pyplot from the matplotlib library to further describe the statistics and relationships such as a bubble chart for total number of rides, by city per city type, and fare amount whilst also showing driver counts.
This analysis includes research of outliers using box-and-whisker plots, pie charts showing total fare percentages by city type, and a line chart representing a trend on weekly sum aggregations for our 3 city types.  Firstly, however, we will have a look at a summary statistics report highlighting key stats for each city type.

## Results

### Summary Report

![Screen Shot 2022-04-20 at 1 38 21 PM](https://user-images.githubusercontent.com/100544761/164299951-01c66223-0ea9-49d1-afa9-7daad7450cf6.png)

As one would expect, Urban cities carry a bulk of the volume when it comes to rides, revenue, and drivers for PyBer seeing how this city type has the most economic activity. Without any knowledge or data on fare rates, we can see that the average fare per ride and average fare per driver is lower in Urban settings.  This makes sense seeing how the areas are more compact and distances are likely shorter per ride which would impact both of these fields of measure.  A question we could ask with more data would include mileage per ride and thusly total fare per mile and provide us with a deeper understanding for fare rates by city type.

### Bubble Plot

![Fig1](https://user-images.githubusercontent.com/100544761/164301280-668175ce-0d54-4bac-ab8a-d3beaeca7cb2.png)

Here we see that perhaps there's no strong correlation with number of rides and fare prices.  If anything there seems to be a negative correlation, meaning that the more total rides a city has the lower the average fares, again likely due to distances and compaction of landscape.  We can also clearly see again that Urban cities have bigger bubbles, meaning more drivers coinciding with the higher ride counts.

### Pie Charts

![Fig5](https://user-images.githubusercontent.com/100544761/164302185-a0425ad7-2b2c-4bda-b65e-bc7dab5f04ba.png) ![Fig6](https://user-images.githubusercontent.com/100544761/164302206-30c1849b-a211-4eeb-880b-88ca5e34cd73.png) ![Fig7](https://user-images.githubusercontent.com/100544761/164302230-cb05b3ea-75c4-40db-8552-3483d3dbd9b2.png)

These figures express visually the summary statistics totals from our report in a different way, via percentages.  We see here just how significant each city type is pertaining to PyBer's total revenue.

### Line Graph

![Fig8](https://user-images.githubusercontent.com/100544761/164302763-4871db7b-3b06-488c-997b-69bf06510c8d.png)

Total revenue was aggregated by week here and expressed over time showing us the trends during the selected time period.  Something happened late february that caused a spike in total fares for all categories followed by a month leveling out for suburban and rural cities, while urban cities continued to see fluctuations in revenue.  The environment and conditions for that time period is worth investigating further to discover reasons why we're seeing this undulating activity.

## Summary

Based on the information gathered from the analysis, I make the following suggestions:

1. We continue to support the urban drivers with the resources they need to be successful as they fulfill the bulk of our services.
2. Focus our marketing and promotions on urban cities to maintain relations with our customers and continue to grow our business.
3. Not neglect our rural communities as there is opportunity for growth. With 5.3% of total rides and only 2.6% of total drivers, perhaps they are not adequately reached and could use more drivers to open up more ride opportunities.  With a little incentive, maybe we can persuade and increase driver count here.  
4. Consider other forms of transportation to diversity our options for our customers in the urban settings.  
5. Investigate late February and March more to see if there is a pattern or anomaly.

All in all, this analysis is more orienting than action driven.  Now, PyBer knows where it is in terms of best locations that support its business, how much it's bringing in weekly and from where, and how many employees and drivers are recorded completing rides.  If we are to conduct further analysis and zoom in more granularly, we can get more fulling insights on marketing, pricing, promotions, transportaion options, etc.  We could dig deeper to unearth insights that can lead us toward the best opportunities for effective growth and efficiency by looking at demographics, distance, trip duration, vehicle types, positional displacement in regards to start location and end location, time of day if we could get time stamp data.  There are many more questioins that arise from here where we can fine tune operatioins and make bigger and more confident decisions, however, this analysis report is a good place to start.  
