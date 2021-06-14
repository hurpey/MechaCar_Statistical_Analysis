# MechaCar_Statistical_Analysis - AutosRUs

**Overview**

The purpose of this analysis is to help Jeremy and the data analytics team on a special project for the AutosRUs’ newest prototype, the MechaCar. The MechaCar is suffering from production troubles that are blocking the manufacturing team’s progress and AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

The following will be completed for this analysis:

 - Multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes;
 - Collection of summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots;
 - Run t-tests to determine if the manufacturing lots are statistically different from the mean population;
 - Design of a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers; 
 - For each statistical analysis, a summary interpretation of the findings is included.
 
 **Results:**
 **Deliverable 1**__
 ## Linear Regression to Predict MPG
 Below is a screenshot of the oupout from the linear regression: 
 
 <img width="249" alt="1 1" src="https://user-images.githubusercontent.com/79670933/121825812-69562480-cc82-11eb-9f26-4e2fcda24f2e.png">

From the screenshot above, the following can be observed.

a. The vehicle length, and vehicle ground clearance are the variables/coefficients more likely to provide a non-random amount of variance to the mpg values in the dataset.This can be attributed to the significant impact they have on miles per gallon on the MechaCar prototype. However, the vehicle weight, spoiler angle, and All Wheel Drive (AWD) have p-Values that indicate a random amount of variance with the dataset.

b. The slope of the linear model is not considered to be zero? This is because the p-Value for this model, p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis.

c. This linear model predicts the mpg of MechaCar prototypes effectively his linear model, as it has an r-squared value of 0.7149, which means that approximately 71.49% of all mpg predictions will be determined by this model. 

**Results:**
 **Deliverable 2**__
 ## Summary Statistics on Suspension Coils
 Below are screenshots of the total summary and lot summary dataframes from analysis performed:

Total Summary

![1 3](https://user-images.githubusercontent.com/79670933/121826123-2f861d80-cc84-11eb-8915-323d2f6e50fd.png)

 
 <img width="219" alt="1 5" src="https://user-images.githubusercontent.com/79670933/121826331-36f9f680-cc85-11eb-87c6-f3c3e76cc755.png">

 
 Lot Summary

![1 4](https://user-images.githubusercontent.com/79670933/121826122-2eed8700-cc84-11eb-9bd2-d2eaf3c12d03.png)

<img width="289" alt="1 6" src="https://user-images.githubusercontent.com/79670933/121826340-3c574100-cc85-11eb-8320-95f8237534cd.png">


The current manufacturing data meets this design specification for all manufacturing lots in total. When looking at the entire population of the production lot, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variance requirement.

Similarly, but significantly more consistent, Lot 1 and Lot 2 are well within the 100 PSI variance requirement; with variances of 0.98 and 7.47 respectively. However, Lot 3 shows a much larger variance in performance and consistency, with a variance of 170.29, thereby causing the variance at the full lot level.
