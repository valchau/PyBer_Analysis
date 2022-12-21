# PyBer_Analysis

## Overview:

### what is Pyber?
Pyber is an Uber type business that wants to optimize their revenue by analyzing the best choices based on city type, number of drivers and fare options. We have been asked to create a summary DataFrame using Python, that will show V. Isulize, our manager,  ride sharing data by city types, using Rural,Urban & Suburban as the types of city. The end result we created is a multiple line graph that shows total weekly fares by each city type, that can be explained and presented to potential shareholders and investors.

### what we did
We started with two data files, one containing the driver count for some cities, along with the 'type' of city. The other data file contained the same cities along with the dates, the fare and the ride ID. These could have been imported and worked with in Excel,  but we decided to use Python because it has more powerful data analysis and visualization features. We mergedd our data in order to understand the fares, drivers and sing the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we combined this information, we calculated the average fare per ride and average fare per driver. This information can be used to measure driver's perfomanace and provide incentives to drivers that will make more money for Pyber.

### Image of weekly fares by city type and week
Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019. 

## Results by city type:

### Summary of Findings
- Rural cities has the smallest amount of drivers, rides and total fares.
- Urban cities have the largest amount of drivers, rides and total fares.
- Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
- Although Rural cities see the least amount of drivers,rides & fares they have the highest average of fare per ride and fare per driver. This means they make the most value for Pyber. 
- Although the Urban cities have the most drivers, rides and fares,  they have the lowest average of fare per ride and fare per driver. This implies their rates are not making Pyber enough money.
- 
<img width="629" alt="findings" src="https://github.com/valchau/PyBer_Analysis/blob/main/analysis/Totals and Averages.PNG">

### Total Fare by city type chart
Here is an image showing the weekly results from January through April 2019:

<img width="629" alt="findings" src="https://github.com/valchau/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png">


## Summary

From our data we are able to predict what kind of fares Pyber will likely earn based whether the city where the ride takes place  is classified as rural, urban or suburban. Plus we can see that rural areas are more lucrative business for Pyber than larger urban areas - unless the fare rates are higher in urban areas. Although we didn't explore every individual city we were able to analyze and show what fares will likely look like from week to week based on city type In conclusion we can effectively say that a rural area is likely to provide a higher fare per ride for Pyberbecause there are fewer workers that will come to this area, the travel time and distance is most likely longer, making the average fare per ride & driver the most out of all city types.

# Recommendations 

1. Charge more per mile in urban cities because trips most likely are shorter and drivers dont earn as much per trip.
2. Fare rates might need to flucuate when ridership either rises (holiday times) or falls (during times when people leave the cities for vacation). 
3. You might want to find out more about the ride/fare data by tracking the mileage of each ride as well as the time of data the ride occured to see if fares should change during certain times of day or based on mileage of the ride.

