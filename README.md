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

Development of the multi-line chart required aggregation of the fare data for each city type by week. The results of this aggregation of data resulted in the dataframe below. This dataframe served as the source for the multi-line graph.

*City Type Weekly Summary Dataframe*

![alt text](https://github.com/geboweniii/PyBer_Analysis/blob/main/analysis/City_Type_Weekly_Summary_Dataframe.PNG)

## Summary
