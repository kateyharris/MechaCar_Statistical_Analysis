# MechaCar_Statistical_Analysis

## OVERVIEW
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on the data analytics team to review the production data for insights that may help the manufacturing team.

## CHALLENGE
- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, and write a summary interpretation of the findings.
 
## OUTCOME

## Linear Regression to Predict MPG
### output from the linear regression<br>
![Snap227](https://user-images.githubusercontent.com/90797036/148480479-409bf6fa-0ba9-4cce-b42e-b4d23b0f3fef.png)<br>


- Vehicle Length and ground clearance provided a non-random amount of variance to the mpg values in the dataset.<br>
![Snap231](https://user-images.githubusercontent.com/90797036/148484060-08499028-7a54-4bbd-ae72-93dae513fd8f.png)![Snap232](https://user-images.githubusercontent.com/90797036/148484074-86ea6b0e-591a-4936-afae-d2a3b0c5dda8.png)<br>


- The slope of the linear model can not be considered to be zero. Note the upward path of the line on the graph.
- This linear model prediction of mpg of MechaCar prototypes is effectively accurate at 71.5% per the R-squared value.

## Summary Statistics on Suspension Coils
### total_summary<br> 
![Snap229](https://user-images.githubusercontent.com/90797036/148481323-9799fa27-0f8b-4ebc-9860-141c99bb1b8e.png)<br> 

### lot_summary<br>
![Snap228](https://user-images.githubusercontent.com/90797036/148481071-47f0116b-a829-4323-8bf5-e6bd5eba930d.png)<br>

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Current manufacturing data does meet this design specification for Lot1 and Lot 2, but lot 3 is in excess at 170.3.

## T-Tests on Suspension Coils
t-test results indicate no statistical difference<br>
![Snap234](https://user-images.githubusercontent.com/90797036/148490518-831ff6bf-8b97-4721-a152-ff2607ac8bb5.png)<br>

## Study Design: MechaCar vs Competition
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:<br>
![Snap235](https://user-images.githubusercontent.com/90797036/148490715-d4077f83-e3ac-45dd-ab65-6d906ab5d8e5.png)<br>

- What metric or metrics are you going to test?
- What is the null hypothesis or alternative hypothesis?
- What statistical test would you use to test the hypothesis? And why?
- What data is needed to run the statistical test?
