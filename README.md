# PyBer_Analysis

## Project Overview
* The purpose of this project is to clean and organize data for the PyBer Ride Share Company which will help inform future business decisions. The data contains information on rides provided in Urban, Suburban, and Rural city types. During the scope of the project, data is organized into a summary data frame which provides total rides, total driver count, and total fares by city type as well as average fare by driver and average fare by city type. Finally, we provide PyBer's stakeholders visual data, in the form of a graph, with the average weekly fare for each city type. These insights will allow PyBer to address disparities amongst riders in the various city types. 

## Resources
* Data source: city_data.csv, ride_data.csv
* Software: Python 3.9.12, Jupyter Notebook 3.1

## Results

### Total Rides by City Type
* Through our analysis, we find that Urban riders make up the vast majority of ridership totaling 1,625 of 2,375 total rides. They account for 68% of all of PyBer's riders. On the opposing end of the spectrum, Rural riders only make up 5% of total ridership with a total of 125 total rides. Suburban riders account for 625 of the 2,375, or 26%.
 ___total_rides_1___

### Total Drivers by City Type
* We also find that Urban cities have far more drivers available to them than their Rural counterparts. Of the 2,973 total drivers we found in the analysis, 2,405 of them are driving in Urban cities. These Urban drivers account for almost 81% of all drivers in the analysis. Suburban drivers account for 490, or 16% and Rural drivers account for only 78 total drivers, or 3%. 
___total_drivers_2___

### Total Fares by City Type
* Urban riders account for the vast majorty of rides and therefore we find that they also account for the majority of the fares for PyBer. Fares total $63,538.64 for all city types combined. Rural riders account for almost 7%, with fares totaling $4,327.93. Urban riders account for $39,854.38 almost 63% and Suburban riders $19,356.33 or 30%
___total_fares_3___

### Average Fare Per Ride
* The average fare per ride is highest amongst Rural riders at $34.62 per ride followed closely by Suburban riders who average $30.97 per ride. Urban riders pay the least per ride with PyBer, on average $24.52 per ride.
___avg_fare_per_ride_4___

### Average Fare Per Driver
* The average fare collected by each driver is also highest in Rural and lowest in Urban cities. Rural drivers collect on average $55.48 per fare followed by Suburban drivers, who average $39.50 per fare. Urban city drivers collect only $16.57 per fare, on average. 
___avg_fare_per_driver_5___

## Summary
* To summarize the findings, there is a wide disparity in every measurable metric in this summary between Urban and Rural riders and drivers. Urban riders have far more drivers available which appears to drive down the cost of the average fare. Additionally, when reviewing the summary data for Total Fares by City Type, we find that Urban riders are only accounting for 63% of total fares while they make up 68% of total riders. On the other hand, Rural riders make up only 5% and are paying close to 7% of total fares. Rural riders are also paying, on average, $10 more per ride than Urban riders. Rural drivers are also collecting 235% more than their Urban colleagues, a $38.92 difference on average per fare. It appears that the rule of supply and demand is in full effect at PyBer. Finally, further analysis would be needed to determine if there are any factors at play, such as average ride distance for example, that could account for such discrepencies amongst PyBer patrons based on their city type.
