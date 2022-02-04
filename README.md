# MechaCar_Statistical_Analysis
## Overview
Using data analysis to help the production team identify ideal vehicle performance factors on AutosRUs’ newest prototype, the MechaCar. 

## Linear Regression to Predict MPG
Using RStudio's multiple linear regression, the following data was collected:

![MPG_Capture](https://user-images.githubusercontent.com/90974647/148656303-5e74b5d4-63c0-4326-b56c-bed56d3c434c.PNG)

According to our results, we can conclude:
  - A:  Vehicle length and ground clearance are statistically unlikely to provide random amounts of variance to the linear model. The p-scores show that vehicle length and ground clearance have a significant impact on mpg. The p-value of our linear regression analysis is 2.60 x 10<sup>-12</sup> & 5.21 x 10<sup>-8</sup> respectively, which is much smaller than our assumed significance level of 0.05%. 
  - B:  The slope of our linear model is not zero.  This is shown in the estimate column for each varible.  
  - C:  The r-squared value, shows that 71.4% of the variation in mpg can be explained by the prototype specifications reveiwed.  Meaning this is a fairly effective model to predict mpg of MechaCar prototypes.

## Summary Statistics on Suspension Coils
![summary_dev 2](https://user-images.githubusercontent.com/90974647/148853099-9e00b78d-ec3c-48f5-aebf-8837b58e35d0.PNG)
![lost-summary_dev 2](https://user-images.githubusercontent.com/90974647/148853105-08e864fc-ae8b-4b5d-bddd-ea490abf6945.PNG)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

There is a summary that addresses the design specification requirement for all the manufacturing lots and each lot individually
