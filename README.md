# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="812" alt="Linear Regression" src="https://user-images.githubusercontent.com/109634784/210284803-81168da0-8c19-4f2e-8df7-34db90532bba.png">

Using Linear Regression, we are able to see that miles per gallon, vehicle length, and ground clearance all provided a non-random amount of variance to the mpg values in the dataset, as their values fell under the acceptable range of the 95% confidence interval. As for the slope of this model, it seems to be non-zero, as there are several values that are much higher than zero, which would lead to a non-zero slope. Lastly, I would say this linear regression model is able to predict mpg of MechaCar prototypes effectively, as the R squared value is a large enough value to show a positive correlation between the dataset.

## Summary Statistics on Suspension Coils

<img width="718" alt="Suspension Coil" src="https://user-images.githubusercontent.com/109634784/210285304-fa02545b-7289-4b17-850b-d4eabbe180b7.png">

Going off of both summaries, I would say that not every single lot meets this design specification, as you can see an extremely high amount of variance within lot 3, especially when compared to the lower variance in lots 1 and 2. I would say lots 1 and 2 pass individually, but if the question is do all three pass together, I would say no, solely due to lot 3. 

## T-Tests on Suspension Coils

<img width="603" alt="Lot 1" src="https://user-images.githubusercontent.com/109634784/210285480-bd680c92-a784-411f-ad52-b63094321139.png">

<img width="597" alt="Lot 2 " src="https://user-images.githubusercontent.com/109634784/210285489-a257f9a2-18a6-4c97-962d-39eaa6a7853f.png">

<img width="577" alt="Lot 3" src="https://user-images.githubusercontent.com/109634784/210285494-02353f1f-14cb-4973-80e0-e502ef6e1431.png">

Much like the last section, we can see that Lots 1 and 2 share similarities in that they both show normal distribution and their means fall within the expected 95% confidence interval. However, again we can see that Lot 3 strays from this, and the results show a deviation from normalcy, even though Lot 3's mean still falls within the condidence interval. 

## Study Design: MechaCar vs Competition

I think with this current day and age of more and more people moving to work remote, the cost to benefit ratio of owning cars and other vehicles is becoming an increasingly important factor when one is buying a vehicle, so being able to track overall maintenance of the MechaCar vs competition could be something that could push sales, if show to be a positive. The null hypothesis for this would be that the cost of maintenance would be the same between MechaCar and competitors, while the alternative hypothesis would be that there is a difference in cost for maintaining the vehicle. I believe the best test for this would be to get some sort of multiple linear regression statistical summary, to be able to see multiple sets of data calculated out. In order to perform this test, cost of maintenance per year, since year of purchase of new car would be absolutely necessary, while the addition of other variables such as miles driven per year and all thatwould be additional data to further refine this. 
