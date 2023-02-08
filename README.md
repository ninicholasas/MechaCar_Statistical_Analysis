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
T-Test All Lots

<img width="403" alt="t-test_suspension_coil" src="https://user-images.githubusercontent.com/110373282/217465252-aa2df174-9b72-4fc3-90d4-6a27605362e8.png">

T-Test Lot 1

<img width="413" alt="t-test_Lot1" src="https://user-images.githubusercontent.com/110373282/217465066-44a36036-fd4b-431f-bc3c-60a39c1cdbe0.png">

Lot 1: p-value = 1, 'true sample mean' = 1500 => We can't reject the null hypothesis.

T-Test Lot 2

<img width="402" alt="t-test_Lot2" src="https://user-images.githubusercontent.com/110373282/217465084-7dd2cc54-a374-47f0-82d8-cca393ccd23a.png">

Lot 2: p-value = 0.6072, 'true sample mean' = 1500.2 => We can't reject the null hypothesis.

T-Test Lot 3

<img width="406" alt="t-test_Lot3" src="https://user-images.githubusercontent.com/110373282/217465121-2b515955-bc60-414a-84a2-7e10513922f9.png">

Lot 1: p-value = 0.04168, 'true sample mean' = 1499.849 => __We should reject the null hypothesis.__

From the above T-Test results, something appears to be happening with Lot 3 while production.
## Study Design: MechaCar vs Competition

* What metric or metrics are you going to test?
  * Fuel Economy and Emissons

* What is the null hypothesis or alternative hypothesis?
  * Null hypothesis: MechaCar fuel economy and emissions are statistically similar to it’s competitors
  * Alternative hypothesis: MechaCar fuel economy and emissions are not statistically similar to it’s competitors

* What statistical test would you use to test the hypothesis? And why?
  * Two sample T-Test: this wasy we could compare the fuel economy and the emissions means between the 2 companies.

* What data is needed to run the statistical test?
  * WE will need emission data from both MechaCar and competitor.

