# PyBer_Analysis

Overview of the Analysis

The purpose of this analysis is to evaluate the relationship between a city type and the average fare over time in order to determine where we should focus our efforts. We do so by examining Ride-share data such as the total number of rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. 

Results

Looking at the diagram below, we can make several observations. We can see that we receive the greatest amount of fares overall from rides that take place in Urban cities, followed by Suburban cities, and finally Rural cities. Now this is to be expected since there's a greater consumer base in cities so it stands to reason there would be more incidences of people using our ride-sharing service to get to where they need to go. 

Looking at the amount of fares over the first few months of the year, you can see that there is a significant drop in fares in the month of April, which is something that we should dedicate additional resources to determine the root cause. 

Examining the chart below, we can come to an interesting conclusion. While urban rides were the most numerous out of the three city types, they also have the lowest average fare per ride, as well as the lowest average fare per driver. Conversely, at an average fare per ride of $34.62 and an average fare per driver of $55.49, rural rides tend to produce the highest fares. This coould likely be due to the fact that in urban and suburban areas, destinations are generally closer to the point of departure, whereas in rural areas destinations generally tend to be farther away, lengthening the duration of the ride and therefore increasing the fare price.

One other thing I noticed was that urban drivers are overrepresented in our data set. There are 2,405 urban drivers, compared with 1605 total urban rides. Meanwhile there are 490 suburban drivers who performed 625 rides, and 78 rural drivers who performed 125 rides. I'm not sure if this is just a fluke or error in the data set, but if it's true, then some of our idle drivers should be diverted elsewhere. 

<img width="632" alt="Screen Shot 2022-04-04 at 12 01 10 AM" src="https://user-images.githubusercontent.com/99847786/161472765-c9c75cb6-3a4b-4132-8298-b0b363f1e6d3.png">


![PyBer_fare_summary](https://user-images.githubusercontent.com/99847786/161470388-b40364da-09e1-449c-8b45-15da911d8dea.png)


Summary

My first recommendation would be to conduct furthr analysis on the drop in rides during the first few weeks of April. If we discover the root cause for the sudden drop in demand, we can better adapt our policies to promote our ride-sharing service during this time. 

Secondly, I would recommend further analysis on the cost per mile for each city type. I noted above that rural rides tend to produce the highest fares, likely because of the greater distance traveled. By analyzing the cost per mile, we could determine if rural rides truely are more profitable than urban and suburban rides, or if the greater fare price is solely due to the larger distance covered. 

Finally, I would recommend diverting some of our drivers in urban areas focus their efforts on rural areas, as they're overrepresented in their current location and rural areas tend to produce the highest fares. 
