# PyBer_Analysis
Module 5 Challenge is utilizing `Anaconda`, `Jupyter Notebook`, `Panda`, and `Python` using Panda, NumPy, and SciPy programs. 

##Overview
V. Isualize has given me and Omar a brand-new assignment to create a summary DataFrame of the ride-sharing data by city type. Another task is to create a multiple-line graph that shows the total weekly fares for each city type. Lastly, we will submit  a report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer. By having these information, PyBer can make better business decisions for each city type that will improve the service quality for the customer which will possibly increase satisfaction rate and company's profit and value in the future. 

The Updated PyBer DataFrame will include: (for each city type)
  * Total Rides 
  * Total Drivers 
  * Total Fare 
  * Average Fare per Ride
  * Average Fare per Driver


##Results
- Below is a graph of multiple line charts of 'Total Fare by City Type':
![PyBer_fare_summary](https://user-images.githubusercontent.com/95068439/151635153-68cdf7b9-8009-45f2-9108-64807aa8c560.png)
***Observations*** :
  * Rural total fare started with $200 in January and relatively fluctuating with dropping to its lowest in January to about $50 and spiking till about $500 in early April and slowly dropping to around $200 again
  * Suburban total fare started in around $750 and continue to rise and reached its peak close to $1,500 by mid-February and significantly dropping and stayed around the $1000 area until it starts to rise again in early to mid-April 
  * Urban total fare started with about $1600 and continue to rise and reached its peak of close to $2500 twice in late February and early March and fluctuate for a little bit and consistently stay around the $2300 range


Here is the **Pyber Summary DataFrame** containing ride-sharing data by city type
<img width="1113" alt="Module 1 Pyber Summary DataFrame" src="https://user-images.githubusercontent.com/95068439/151636054-0661e7b4-bb12-4b01-8497-fba7edc898c4.png">
***Significance***: 
1. Urban has significantly more `Total Rides` and `Total Drivers` which results on ranked 1st on `Total Fare`. However, urban ranked the lowest for both `Average Fare per Ride` and `Average Fare per Driver` which may signify that Urban rides tend to be shorter both in distance and duration of the ride
2. Suburban ranked 2nd in all aspects with a huge difference (for `Total Rides`, `Total Drivers`, and `Total Fare`) from both Urban and Rural and about $6 more expensive in `Average Fare per Ride` and about $25 more expensive in `Average Fare per Driver` than Urban
3. Rural ranked last for `Total Rides`, `Total Drivers`, and `Total Fare` but ranked first for `Average Fare per Ride` and `Average Fare per Driver`. This might be caused by shortage of drivers(supply) which potentially lead to a higher fare combined with longer distance and duration due to rural conditions located outside towns and cities where homes and businesses are located far away from one another


##Summary

Based on the data provided and visualization, here are my three business recommendations to address any disparities among the city types:
  1. With a high Average Fare numbers for Rural with lower count for Rides and Drivers, PyBer need to consider expanding their business in Rural areas by hiring more drivers which will increase their total ride and fare and increase their profit and company's value
  2. Similar situation for Rural, Pyber also need to consider hiring more drivers which will also increase the total rides which will result in an increase in total fare
  3. With a booming business in the Urban area, PyBer might need to consider expand and diversify into other services such as food delivery or groceries shopping utilizing the high number of drivers and potentially increase it
