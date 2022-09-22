# MechaCar_Statistical_Analysis

We analyzed data for AutosRUs’ newest prototype, the MechaCar, which is suffering from production issues that are blocking the manufacturing team’s progress. We helped the data analytics team to review the production data for insights that may help the manufacturing team.

## Overview

Deliverable 1 - Linear Regression to Predict MPG: Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes

Deliverable 2 - Summary Statistics on Suspension Coils: Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots

Deliverable 3 - T-Test on Suspension Coils: Run t-tests to determine if the manufacturing lots are statistically different from the population mean

Deliverable 4 - Design a Study Comparing the MechaCar to the Competition: Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

# Results

### Linear Regression to Predict MPG
The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle.

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
vehicle_length with p-value=2.60e-12 which is << 0.05
ground_clearance with p-value=5.21e-08 which is << 0.05

2. Is the slope of the linear model considered to be zero? Why or why not?
No. Have Multiple R-squared = 0.7149, which indicates a strong correlation.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 Since (Intercept) != 0, it means that the intercept term explains a significant amount of variability in the dependent variable when all independent variables are equal to zero. 
 
### Summary Statistics on Suspension Coils

The manufacturing data for all lots shows that the suspension coil variance is 62.29356, which is below the limit of 100 pounds per square inch.However, the per-lot breakdown of the data shows Lot3 has a suspension coil variance of 170.2861224, which is above the limit of 100 pounds per square inch. Lot 1  and Lot 2  are within the variance limit.

### T-Tests on Suspension Coils

Using our knowledge of R, we performed t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch. The only lot with a statistical difference is Lot 3 



# study Design: MechaCar vs Competition

Description: 
What metric or metrics will be tested?

Overall Safety Rating:  category is made up of various sub-categories like: Frontal Crash, Side Crash, Rollover, etc.; but we just need a categorical 'overall safety rating'.

Vehicle Weight: We need the vehicle weight for all current cars.

- What is the null hypothesis or alternative hypothesis?

Null Hypothesis: Heavier cars are no safer than lighter cars

Alternative Hypothesis: Safety Rating increases by one letter grade for each increasing weight 

- What statistical test would will be used to test the hypothesis? And why?

Chi-Squared Test: This test can be used to determine if there is a difference in categorical frequencies between groups. 

If the p-value of our Chi-Squared Test is below 0.05, then we can reject our Null Hypothesis, and we will know that increasing vehicle weight also increases overall safety rating.

- What data is needed to run the statistical test?

Vehicle Weight data for all current vehicle models 

Crash Test Results converted into Overall Safety Rating 

Verify Pre-conditions for Chi-Squared Test















### Summary

 R Programming Language was not very positive. If I have an opportunity to use R professionally in the future, I will look forward to learning more about it.






