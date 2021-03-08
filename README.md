# PyBer_Analysis
## Overview of the PyBer Analysis
Exploratory analysis of ride data of the pyber was done and fare, no of rides & no of drivers dependency and variations for the different city types are derived.
Also plots which show relationships between different measures were also drawn and delivered.Now management needs the summary of the ride data which includes total number of rides,total number of drivers,total fare, average fare per ride and average fare per driver for each area.Also a plot which shows the variation in th fare weekly for each area is requested.Pyber analysis is to create a summary dataframe with total number of rides,total number of drivers,total fare, average fare per ride and average fare per driver for each area and to create a plot which shows the variation in th fare weekly for each area is requested.
## Results
Input Data used for anaysis is avaiable at below places.

1.Ride data (till May first week) :-https://github.com/merinanto/PyBer_Analysis/blob/main/resources/ride_data.csv

2.City metadata :-https://github.com/merinanto/PyBer_Analysis/blob/main/resources/city_data.csv

Script to used to create summary dataframe and plot is available at :-https://github.com/merinanto/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb

###Analysis of Summary Dataframe
Total number of rides, drivers and total fare is highest for urban area.But average fare per ride and average fare per driver is lowest for urban area.
Similary total number of rides, drivers and total fare is lowest for rural area.But average fare per ride and average fare per driver is highest for rural area.
Looks like number of rides per driver and fare for ride is more at rural and suburban area.Number of drivers is more than the number of rides and average fare is less at urban area. So there is a surplus number of drivers at urban area.
###Analysis of Weekly fares for city type.
Plot created weekly for city type is available at :-https://github.com/merinanto/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png
Total weekly Fares amount varies for more randomly within  range of $1000 for urban area.Rural area is comparatively stable within $500 for total weekly fares.
Even at suburban area Total weekly Fares amount varies for randomly within  range of $1000 to an extent.

##Summary
1.Number of rides per driver and fare for ride is more at rural and suburban area.Number of drivers is more than the number of rides and average fare is less at urban area. So there is a surplus number of drivers at urban area.There is a chance rural drivers is earning more than urban, but distance covered for each ride and cost of the ride also needs to considered to make accurate conclusion.
2.If drivers can be added in the rural and suburban area may be average fare per driver can be reduced.If canceled ride requests data along with reason can be pulled , then driver requirement can be confirmed.
3.Total weekly Fares amount varies for  randomly within  range of $1000 for urban area & suburban area.Rural area is comparatively stable within $500 for total weekly fares.
As schedules and people movement is more stable at rural arae, other than any community event,this can be expected.Urban area ride requests varies with weather conditions,events etc.Hence variation within a range is expected.
