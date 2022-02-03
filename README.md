# PyBer_Analysis
## Purpose
The purpose of this analysis is to evaluate the ride-share service variations including drivers, fares, and cities (by city type).

## Results - description of the differences in ride-sharing data among the different city types.  Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

### Scatter Plot
The PyBer Ride-Sharing Data scatter plot shows distinct differences between the city types in terms of number of drivers, number of rides and average fares.  

!["PyBer Ride-Sharing Data"](https://github.com/LauraZJ/PyBer_Analysis/blob/main/Analysis/Fig1.png)


#### Urban
The scatter plot shows that while the number of drivers and rides are generally higher in urban cities, the fares are lower. There are a few exceptions to the number of drivers in some of the urban cities, but the majority of urban cities consistently have both a large number of drivers and high ride volumes.

#### Suburban
Suburban cities, are, as would be expected, in the middle compared to urban and rural cities.  The number of rides ranges from below the rural numbers to approximately 2/3 the volume of urban cities.  The number of drivers per suburban city is also lower.  Intrestingly, the average fare is somewhat higher for suburban cities.  

#### Rural
When you look at the scatter plot, you see that rural cities not only have the lowest number of rides and the lowest driver count, but they have higher average fares.

The box and whisker plots (below) demonstrate that in a more focused view.  

!["Ride count data"](https://github.com/LauraZJ/PyBer_Analysis/blob/main/Analysis/Fig2.png)

!["Ride fare data"](https://github.com/LauraZJ/PyBer_Analysis/blob/main/Analysis/Fig3.png)

!["Driver count data"](https://github.com/LauraZJ/PyBer_Analysis/blob/main/Analysis/Fig4.png)


I believe there is a direct correlation between population and the number of available drivers and riders.  Urban cities have a higher populiation, likely many people who rely on public transportation (or ride-shares), people who are going short-distances.  

Suburban communities have a good population, but many people likley have their own transportation and may use ride-share services for special events rather than consistent use.  With that said, the need is less, the call for drivers is lower.  The distance traveled may be a bit farther as commercial and residential properties are not concentrated in as small an area as urban cities.  This added distance would be represented by an increase in the fare.

Rural communities are the smallest of the three in population and has less need for drivers and rides.  However, the distance of the trips are likely longer because of geographic logistics alone.  

##### Pie Charts:
When examining the pie charts, we see: 
1. Urban cities have a higher percentage of the total fares, total rides, and total drivers.  What I found interesting is that urban cities are within a few percentage points in both total rides and total fares, yet they have a larger percentage of total drivers.  Higher population = the availability of more drivers, as there may be people who work part time to pick up a little extra money. However, more rides doesn't equal higher fares. 

2. As we look at the % drivers in suburban and rural areas, we see that the percentage of drivers is aabout half the percentage when compared to the percent of total fares and total rides.  The overall need for rides is reduced so the number of drivers needed is lower.
!["% Total Fares by City Type"](https://github.com/LauraZJ/PyBer_Analysis/blob/main/Analysis/Fig5.png)
!["% Total Rides by City Type"](https://github.com/LauraZJ/PyBer_Analysis/blob/main/Analysis/Fig6.png)
!["% Total Drivers by City Type"](https://github.com/LauraZJ/PyBer_Analysis/blob/main/Analysis/Fig7.png)

##### Line Graph
Another way to view the difference in the fares by city type is to look at the data in a line graph.    This graph represents the actual dollars spent on ride-share fares by city type.  This doesn't show the detail of the number of rides or drivers, so we can't see that the rural fares are higher, it shows merely the sum of the fares earned in each city type, which as expected, shows that more fares are arned in Urban areas, with suburban next and rural earnings being the lowest when viewing the overall total fares.
!["PyBer Fare Summary"](https://github.com/LauraZJ/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

## Summary
Based on the results of this analysis and given my believe that the population of each city type drives the opportunity and outcomes, there is very little I feel I could recommend to address the disparaties.
1. PyBer service owners could perhaps work with business, airports, malls, etc. to subsidize the fare to increase rider utilization from rural communities.  If the riders see the ride-share as convenience, utilization would likely increase. 
2. Perhaps in suburban communities, start a rewards program that would provide some perk (or a free ride) to indidviduals who use the service frequently.  This would increase ridership.
3. Encouraging drivers in the urban areas to diversify into the suburban communities could also increase ridership if the service is more available.  This would be true of rural areas as well. 

