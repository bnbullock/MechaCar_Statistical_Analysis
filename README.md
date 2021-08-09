# MechaCar_Statistical_Analysis

- A few weeks after starting his new role, Jeremy is approached by upper management about a special
project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are 
blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the
data analytics team to review the production data for insights that may help the manufacturing team.

- In this challenge, you’ll help Jeremy and the data analytics team do the following:

	- Perform multiple linear regression analysis to identify which variables in the dataset predict the 
	mpg of MechaCar prototypes
	- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
	- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
	- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other 
	manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

- Deliverables:
  1. Using Python, update the CSV bike trips CSV file.
  2. Create 5 different visualizations in Tableau
  3. Create 2 additional custom visualizations
  4. Craft a Tableau Story based on the visualizations
  5. Written Analysis
------------------------------------------------------------------------------------------------------------

## Resources
- Software: Visual Studio Code 1.56.2, Python 3.7.10, jupyter Notebook Server 6.3.0
- Browser : Google Chrome v91.0.4472.124 
- Data Source: https://s3.amazonaws.com/tripdata/index.html#:~:text=ZIP%20file-,201908-citibike-tripdata.csv.zip,-Sep%2018th%202019

------------------------------------------------------------------------------------------------------------

## Results


## Linear Regression to Predict MPG
- write a short summary using a screenshot of the output from the linear regression, and address the 
following questions:

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Is the slope of the linear model considered to be zero? Why or why not?
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

![Image1](images/1Linear_regression.png)

![Image2](images/2Summary.png)

## Summary Statistics on Suspension Coils
- write a short summary using screenshots from your total_summary and lot_summary dataframes, and 
address the following question:

- The design specifications for the MechaCar suspension coils dictate that the variance of the 
suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet 
this design specification for all manufacturing lots in total and each lot individually? Why or why not?

![Image3](images/3Summarize.png)

![Image4](images/4Group_Summarize.png)

## T-Tests on Suspension Coils
- briefly summarize your interpretation and findings for the t-test results. Include screenshots 
of the t-test to support your summary.
- Hint : Use ?t.test() in the R console to determine what arguments are needed to test against the 
PSI column across all manufacturing lots and for each lot.

![Image5](images/5t_test.png)

![Image6](images/6t_test_lot1.png)

![Image7](images/7t_test_lot2.png)

![Image8](images/8t_test_lot3.png)


## Study Design: MechaCar vs Competition

- Write a short description of a statistical study that can quantify how the MechaCar performs against the 
competition. In your study design, think critically about what metrics would be of interest to a 
consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or 
safety rating.

- In your description, address the following questions:
	- What metric or metrics are you going to test?
	- What is the null hypothesis or alternative hypothesis?
	- What statistical test would you use to test the hypothesis? And why?
	- What data is needed to run the statistical test?
	
- Hint : Use the stat cheat sheet pdf to help with your design

## Overall Summary