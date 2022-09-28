# MechaCar_Statistical_Analysis
Module 15

Deliverable 1
Linear Regression to Predict MPG
-
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- The vehicle length and ground clearance variables provide non-random amounts of variance as applied to the mpg values.
Is the slope of the linear model considered to be zero? Why or why not?
- No - The multiple linear regression formula is considered to be a non-zero slope
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- Yes - R-square is 0.71 which means that 71% chance the model will predict mpg variations correctly. 

Deliverable 2
Summary Statistics on Suspension Coils
-
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- The design specs are followed for all manufacturing lots in total with a global variance of 62 psi < 100 within the expected design specifications of staying under 100 PSI.
- Lot 3 has a variance of 170 > 100 and does not meet the design specifications.

Deliverable 3
T-Tests on Suspension Coils
-
Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
Lot 1
The p = 1.568e-11 "A p-value higher than 0.05 (> 0.05) is not statistically significant and indicates strong evidence for the null hypothesis. This means we retain the null hypothesis and reject the alternative hypothesis. You should note that you cannot accept the null hypothesis, we can only reject the null or fail to reject it."

Lot 2
The p = .0005911 "A p-value less than 0.05 (typically ≤ 0.05) is statistically significant. It indicates strong evidence against the null hypothesis, as there is less than a 5% probability the null is correct (and the results are random). Therefore, we reject the null hypothesis, and accept the alternative hypothesis.

Lot 3
The p = .1589 "A p-value higher than 0.05 (> 0.05) is not statistically significant and indicates strong evidence for the null hypothesis. This means we retain the null hypothesis and reject the alternative hypothesis. You should note that you cannot accept the null hypothesis, we can only reject the null or fail to reject it."

Deliverable 4
Study Design: MechaCar vs Competition
-
What metric or metrics are you going to test?
- Metrics for safety Ratings, Horsepower, City and Highway Fuel Efficiency, Maintenance Cost, and Price per Unit
What is the null hypothesis or alternative hypothesis?
- Null Hypothesis = The MEAN of the safety rating is zero.
- Alternative Hypothesis = The MEAN of the safety rating is not zero.
What statistical test would you use to test the hypothesis? And why?
- I would use a statistical summary which would show how the different variables impact the safety ratings for MechaCar and their competitors.
What data is needed to run the statistical test?
- A random sample from MechaCar and their competitor for Safety Ratings, Horsepower, City and Highway Fuel Efficiency, Maintenance Cost, and Price per Unit 

