# MechaCar_Statistical_Analysis

## Overview of the Analysis
The goal for this project is to perform multiple linear regression analysis to analyze production data to find insights that may help the manufacturing team at MechaCar.
There were 2 data files provided for this analysis, that included Suspension Coil manufacturing data and vehicular data.
I performed Linear Regression, Summary Statistics and T-Testing.

## Results
### Linear Regression to Predict MPG

<img width="508" alt="summary" src="https://user-images.githubusercontent.com/110373282/217462793-b8af6c05-18a6-4b56-902c-d0fcf7d00921.png">

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  * Vehicle_Length and Ground_Clearance had a large amount of variance to the mpg values compared to the others.

* Is the slope of the linear model considered to be zero? Why or why not?
  * Since the p-value is extremely small, the linear model can not be considered zero.

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  * With a R-squared of 0.7149 we could say that this linear model is effictive at predicting mpg.
---
### Summary Statistics on Suspension Coils
Total Summary

<img width="335" alt="total_summary" src="https://user-images.githubusercontent.com/110373282/217463428-7380fed1-0740-408c-90a0-28b618b31168.png">

Lot Summary

<img width="492" alt="lot_summary" src="https://user-images.githubusercontent.com/110373282/217463450-9da21775-3eec-44d5-9fce-788685f11c50.png">

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
 * Taking a look at the __Lot Summary__ we could tell that Lot 3 has a very high Variance and SD. Since the design specification is that the variance must not exceed 100, Lot 3 does not meet the design specification.
___
### T-Tests on Suspension Coils




## Summary

