# PyBer Analysis
with Matplotlib
## Overview of the Analysis
Used python code and pandas libraries to analyze and visualize how well each types are doing in terms of fares, drivers, and number of rides by city types. 
1. First merged 2 datasets about rides and city types. After that get all the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type by using "groupby" functions in pandas. 
2. Created new dataframe by its date and city types. Used "pivot()" function to create a dataframe that has date as index, and types as columns, fares as values. 
3. Plotted the dataframe using the object-oriented interface method to show weekly fares by each city types.

## Results
Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. 
![](https://user-images.githubusercontent.com/64121596/143131652-47a5bc84-8563-4eb0-b96e-378ea150e4db.png)
* The Urban cities are more likely to have more rides and drivers. 
* Rural cities has the least rides and drivers. 
* As for average fare per ride or driver, the Rural is the most expensive one among city types. That means, as a driver, it's beneficial for them to work in rural areas. As a rider, it's really expensive rather than riding in urban or suburban cities. 

## Summary
The Urban city type has the most total fares, second is Suburban, and the least amount is for rural cities. 

![](https://user-images.githubusercontent.com/64121596/143097188-c4530c59-aa54-4316-a9be-f1e239a6d7ad.png)

### Three reccommendations for the CEO:
1. Late February, the total fares increase for each city types. That means people use ride-share a lot regardless of what city type they live in. As a CEO, the company could implement marketing to get hire more drivers for that week or give incentives and bonuses for more drivers to join only that week.
2. In the beginning of the year (January), both Urban and Suburban city types fares are low compared to rest of the weeks. Whereas, the Rural city fare rates increased. It could be related to holidays and people usually travel and leave the city. As a CEO, the company could promote ride-sharing, or give discount in urban or rural areas in the beginning of the year.
3. In March in urban cities, have unstable total fares. We should look further what is causing this scene and could take action.
