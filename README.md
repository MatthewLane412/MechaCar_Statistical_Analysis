# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle Length
- Ground Clearance

#### Is the slope of the linear model considered to be zero? Why or why not?
- The P value of the line has a slope because it is less than .05

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- The multiple R squared predicts MPG 71% of the time. This is not enough to assume it predicts prototypes effectively. 

![June_Temp](/Images/Deliverable_1_Summary_Linear_Regression.PNG)
![June_Temp](/Images/Deliverable_1_Linear_regression.PNG)

## Summary Statistics on Suspension Coils


##### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

- Lot 1 and Lot 2 meet the specifications with variances of ~1 and ~7, respectively. However, Lot 3 has a variance of 170 exceeding the 100 pounds per square inch limit. 

![Total_Summary](/Images/Deliverable_2_Total_Summary.PNG)

![Lot_Summary](/Images/Deliverable_2_lot_summary.PNG)

## T-Tests on Suspension Coils

#### Summarization of my interpretation and findings for the t-test results
- Whole sample size has a p-value above .06, resulting in an inability to reject the null hypothesis
- Lot 1 - The null hypothesis has a p-value above .06, resulting in an inability to reject the null hypothesis
- Lot 2 - The null hypothesis has a p-value above .06, resulting in an inability to reject the null hypothesis
- Lot 3 - The null hypothesis is rejected with a p-value under .05

![Lot_Summary](/Images/Deliverable_3_t.test_question_1.PNG)

![Lot_Summary](/Images/Deliverable_3_t.test_question_2.PNG)


## Study Design: MechaCar vs Competition

##### Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horsepower, maintenance cost, or safety rating.


### What metric or metrics are you going to test?
 - City or highway fuel efficiency
 - Cost
 - Cylinders
 - Hybrids

### What is the null hypothesis or alternative hypothesis?
 - The Mechacar has better fuel efficiency and cost less
 - The Mechacar has better fuel efficiency with the same amount of cylinders
 - The Mechacar hybrids are more efficiency.

### What statistical test would you use to test the hypothesis? And why?
- I would use a 2 sample t-test to compare the competition

### What data is needed to run the statistical test?
 - Total cost of the base model cars
 - Fuel efficiency
 - Total cylinders per car
 - Type of car (e.g. Hybrid, Non-Hybrid)




