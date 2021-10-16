# PyBer Analysis #

## Overview ##

The data analysis has been developed for PyBer, a ride-sharing app company. Purpose of the engagement: enable PyBer to improve ride-sharing services and determine affordability to underserved neighborhoods. 

### Exploratory Data Analysis (EDA) ###

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

First, a **scatter plot chart** was created that showed the *average fare* versus the *total number of rides* with bubble size based on the *average number of driver*s for each *city type*: urban, suburban, and rural.

![Ride-Sharing Data](/analysis/Fig1.png)

Then, three **statistical analyses** were added to help demonstrate the relevance of the data, such as the *number of rides* for each *city type* that are instrumental in making decisions about which types of cities need more driver support.

   1. Ride Fare Statistical Analysis:

![Ride Fare](/analysis/Ride_Fare_Plot_Box.png)

   2. Ride Count Statistical Analysis:

![Ride Count](/analysis/Ride_Count_Box_Plot.png)

   3. Driver Count Statistical Analysis:

![Driver Count](/analysis/Driver_Count_Box_Plot.png)

Finally, three **alternative visualizations** have been created to support the analysis showing the *percentage of fares*, *rides*, and *drivers* for each *type of city*.

   1. Fares by City Type:

![Fares by City Type](/analysis/Fares_percent.png)

   2. Rides by City Type:

![Rides by City Type](/analysis/Rides_percent.png)

   3. Drivers by City Type:

![Drivers by City Type](/analysis/Fig7.png)

### Deliverable 1 ###

The *average fare per ride* and *average fare per driver* for each *city type* summary is presented below:

![Average Fares by Driver and Ride](/analysis/Deliverable1.png)

### Deliverable 2 ###

The multiple-line graph that shows the *total fares* by week by *city type* is presented below:

![Pyber Fare Summary](/analysis/PyBer_fare_summary.png)

### Summary Report ###

The analysis identified the following key metrics for each city type:
| City Type | Fares | Rides | Drivers |
|-------|-----|-----|-----|
| Urban | $39,854 (total) | 1,625 rides (total)  | 2,405 drivers (total)  |
|       | 62.7 % of total fares | 68.4 % of total rides | 80.9 % of total drivers |
|       | Mean: $24.5 (per ride), St. Dev: $11.7 (per ride) | Mean: 24.6 (per city), St. Dev: 5.4 (per city) | Mean: 36.7 (per city), St. Dev: 20.1 (per city) |
|       | $16.6 per driver | | |
| Suburban |  $19,356 (total) | 625 rides  (total) | 490 drivers  (total)  |
|       | 30.5 % of total fares | 26.3 % of total rides  | 16.5 % of total drivers |
|       | Mean: $31.0 (per ride), St. Dev: $10.7 (per ride)| Mean: 17.4 (per city), St. Dev: 4.3 (per city) | Mean: 13.7 (per city), St. Dev: 8.0 (per city) |
|       | $39.5 per driver | | |
| Rural | $4,328 (total) | 125 rides (total)  | 78 drivers (total)  |
|       | 6.8 % of total fares  | 5.3 % of total rides  | 2.6 % of total drivers |
|       | Mean: $34.6 (per ride), St. Dev: $14.6 (per ride) | Mean: 6.9 (per city), St. Dev: 2.5 (per city) | Mean: 4.3 (per city), St. Dev: 2.7 (per city) |
|       | $55.5 per driver | | |

**Key Conclusions:**

1. There are 8 times **fewer drivers** in **Rural** cities in comparison to the Urban areas 
2. There is a disproportional **shortage** of **Rural drivers**: 2.6% of total drivers vs 5.3% of total rides and 6.8% of total fares
3. There is a disproportional **shortage** of **Suburban drivers**: 16.5% of total drivers vs 26.3% of total rides and 30.5% of total fares
4. **Fares per driver** are 3 times **higher** in **Rural** areas as a result of fewer drivers 
5. **Rural** and some **Suburban** area **fares per trip are high** and may be **hard to afford** by local consumers
6. There is **underutilization** of **Urban drivers**: 2,405 drivers for 1,625 rides

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

## Summary Recommendations ##

Based on the analysis, the following recommendations have been developed to PyBer CEO for addressing any disparities among the city types
1. Attract more drivers in Rural and Suburban areas by providing better benefits in Rural areas 
     - increase the per mile/per hour compensation as % of the Rural fare 
     - provide Rural drivers with special bonuses
2. Reduce fares per ride in Rural and Suburban areas to increase affordability to consumers and increase the customer base
3. Improve the utilization of Urban drivers 
     - encourage Urban drivers to serve Suburban areas
     - provide better visibility of the Suburban ride requests and potential incremental earnings opportunity for Urban drivers 
     - provide location analytics and ride demand predictions to Urban drivers to optimize their routing and waiting locations in Suburban areas
