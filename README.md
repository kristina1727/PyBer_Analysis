# PyBer_Analysis

## Overview
Provide V. Isualize a summary DataFrame of the ride-sharing data by city type while also creating visualizations to show the total weekly fares for each city type. This was to be done using the groupby function with the sum and count methods as well as the pivot function to help create the new DataFrame. To create plot the results we utilized the object-oriented method with the df.plot method.

## Results
As shown at the summary DataFrame below, there a few difference that stand out.
1. The number of total rides in the Urban city type is 2.6 times that of the Suburban total rides and 13 times greater than the total rides for the Rural city type.
2. The Urban city type is saturated with more drivers than the other city types. In fact, they have more drivers than they do total rides. I believe this could be a contributing factor in the decreased average fare per driver. 

![Summary_DF](https://user-images.githubusercontent.com/88597956/139161706-922c8e9b-d3b6-4d2b-bf50-71ea182424a3.PNG)

You are also able to see some interesting differences in looking at the Total Fare by City Type line chart below as well.
1. As expected based on the summary DataFrame, the weekly fare for the Urban city types rarely dips below $1,600. Whereas in some cases the weekly fare for the Rural city types dips near $0.
2. I also found it interesting that the peaks and valleys for the different city types do not follow the same trend. While they all have a peak towards the end of February and a dip shortly thereafter the rest tend to vary from city type to city type. For example, the Urban city type has a dip the end of March while Suburban and Rural are either increasing or remaining flat. 

![Total_Fare_by_City_Type](https://user-images.githubusercontent.com/88597956/139162145-9075ab01-4808-4658-8c9d-b6f02f77cf65.png)


## Summary
Outlined below are three recommendations for the CEO V. Isualize to ponder.
1. Decrease the number of drivers located in the Urban areas, this would then increase the potential average fare per driver.
2. Consider decreasing the price per ride for the Rural city types. This could lead to increase in customers thus increasing the total weekly fare amount.
3. Look at if the peaks and valleys are similar year over year for each city type. If so, look at increasing and decreasing the pricing accordingly.
