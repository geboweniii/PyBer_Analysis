# PyBer Analysis

## Overview
PyBer, a ride-sharing app company, requires an analytical review and presentation of its data for the period of January to early May 2019. Specifically, the company is inetersted in ride fare totals across urban, suburban and rural areas over the early part of the calendar year. This analysist has been provided two comma separated value (CSV) files as data sources for the review. PyBer has requested the delivery of a Python-based dataframe and Matplotlib multi-line graph representing the results of the analysis.

PyBer provided the following CSV files as source data for the analysis:

* city_data.csv
* ride_data.csv

The analysis was conducted using:

* Jupyter Notebook 6.1.4
* Python 7.19.0
* GitBash 2.31.1
* GitHub

## Results

Analysis of the data provide reveal urban cities have seen the most number of rides (1,625), the most drivers (2,405) and the greatest fare amount ($39,854.38). However, the rural communities experienced the highest average fare per ride ($34.62 per ride) and average fare per driver ($55.49 per driver). See the table below for a full set of summary results of this analysis.

*City Type Summary Dataframe*

![alt text](https://github.com/geboweniii/PyBer_Analysis/blob/main/analysis/City_Type_Summary_Dataframe.PNG)

Development of the data visualizations required aggregation of the fare data for each city type by week. The results of this aggregation of data resulted in the dataframe below. This dataframe served as the source for the multi-line graph.

*City Type Weekly Summary Dataframe*

![alt text](https://github.com/geboweniii/PyBer_Analysis/blob/main/analysis/City_Type_Weekly_Summary_Dataframe.PNG)

The following multi-line chart was produced from the *City Type Weekly Summary Dataframe* found above. This chart reveals urban cities consistently earned the greatest total fares over the period of Jan through May 2019. Suburban cities were second over that period of time with rural communities earning the least in total fares. All three areas saw some increase in total fares from the beginning of the period to the end. All city types also experienced a spike in fares in late February. Total fares are impacted by population density and demand as ride counts were highest in urban cities. Due to lengthier distances between destinations in rural communities, average fares per ride and driver were higher but overall demand was substantially lower as there were only 125 rides.

*Total Fare By City Type*

![alt text](https://github.com/geboweniii/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
Based on the results of the analysis, PyBer should consider the following:

1. As urban settings experienced the highest demand for rides, PyBer should consider additional drivers to address higher demand. Assuming a higher demand for rides than is currently addressed, this would result in higher total fares.
2. Because of the ratio of drivers to rides in suburban settings, Pyber should consider adding additional drivers in those areas. This would bring the average fare rates closer to urban settings but potentially increase total fares.
3. Because of the high volatility in total fares in urban areas between March and April, PyBer should consider having additional drivers on hand to address these fluctuations in the event they are due to an inability to meet demand during that time of year.
