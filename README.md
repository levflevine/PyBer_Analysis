# PyBer Analysis #

## Overview ##

The data analysis has been developed for PyBer, a ride-sharing app company. Purpose of the engagement: enable PyBer to improve ride-sharing services and determine affordability to underserved neighborhoods. 

### Eploratory Data Analysis (EDA) ###

The scope of the first phase was conducting the exploratory analysis of the data in source CVS files that resulted in creating several types of visualizations showing the relationships between the *city types*, the *number of drivers*, and the *number of riders*, as well as the *percentage of total fares*, *riders*, and *drivers* by *city type*.

### Deliverable 1: ###
- Get the total *number of rides*, *total number of drivers*, and the *total fares* for each *city type*
- Calculate the *average fare per ride* and *average fare per driver* for each *city type*
- Generate and format a *Ride-Sharing Summary DataFrame* based on specific requirements

### Deliverable 2: ###
- Create a multiple-line graph that shows the *total fares* by week by *city type*

### Summary Report: ###
- Produce a report with analysis of how to address any disparities in the *ride-sharing data* among the *city types*
 
### Resources and Disclosures ###
The PyBer Data Analysis has used  following programming tools: 
- Python Scripts
- Pandas Library
- Matplotlib Library
- Jupyter Notebook

The PyBer analysis used the following data sources:

1. [City Data](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_5/city_data.csv)
2. [Ride Data](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_5/ride_data.csv)

## Results ##

### Eploratory Data Analysis (EDA) ###

First, we've created a scatter plot chart that showed the average fare versus the total number of rides with bubble size based on the average number of drivers for each city type: urban, suburban, and rural.

![Ride-Sharing Data](/analysis/Fig1.png)

Then, we've added a statistical analysis to help demonstrate the relevance of the data, such as the number of rides for each city that is instrumental in making decisions about which types of cities need more driver support.

Ride Fare Statistical Analysis:
![Ride Fare](/analysis/Ride_Fare_Plot_Box.png)

Ride Count Statistical Analysis:
![Ride Count](/analysis/Ride_Count_Box_Plot.png)

Driver Count Statistical Analysis:
![Driver Count](/analysis/Driver_Count_Box_Plot.png)

![Drivers by City Type](/analysis/Fig7.png)

### Deliverable 1 ###

![Average Fares by Driver and Ride](/analysis/Deliverable1.png)

### Deliverable 2 ###

![Pyber Fare Summary](/analysis/PyBer_fare_summary.png)

### Summary Report ###

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

## Summary ##

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
