# **MechaCar_Statistical_Analysis**
## **Deliverable 1**
## *Linear Regression to Predict MPG*
Multiple Linear Regression(MLR) is a statistical model that extends the scope and flexibility of a simple inear regression model.  In an MLR, we us multiple independent variables to account for parts of the total variance observed in the dependent variable, in this case, miles per gallon(mpg).  

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
According to our results, the probability that each variable(coefficient) contributes a random amount of variance to the model, vehicle length and ground clearance are statistically unlikely to provide random amounts of variance to the model.  

### Is the slope of the linear model considered to be zero? Why or why not?
By observing the p-value of less than 0.05, our slope is not zero.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
We are using variables vehicle lenght, vehicle weight, spoiler angle, ground clearance and all wheeel drive(AWD) to see the effects on mpg.  To determine which variables provide significant contribution to the model, we observe the individual p-values.

Then we can answer our question for the test, *Does this model predict the mgp of the MechCar prototypes effectively?*.  Based on our R-squared of 0.7149 or 71%, our model predicted the mpg values accruately.  To increase our comfort of predicatability, we would need to look for other factors not included in this dataset or model.

## **Deliverable 2**
## *Summary Statistics on Suspension Coils*
### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Not all three lots meet the current manufacturing design specifications.  Lots 1 and 2 based on their nearly identical mean and mdeian score of nearly 1500 gets them within specs, statistically speaking.  Lot 1 is the top performer with a variance and standard deviation of less than one showing strong consistency.  Lot 2 has a variance of around 7.5 with a standard deviation of 2.73, while acceptable, could do with some improvement.  Lot 3 has the worst scores of all and do not consistently ensure the quality of the product with a mean score of 1496.14 and 13.05 of standard deviation.

## **Deliverable 3**
## *T-Tests on Supsension Coils*
### Summary of the t-test results across all manufacturing lots and for each lot 

#### All lots
The t-tests on All lots shows us while the mean of 1498.78 is close to the specifications outlined, the p-value of 0.06 suggests that we can not reject the null hypothesis and do not have sufficient evidence to say that the true mean of PSI to all manufacturing lots is 1,500 lbs/sqin.

<img width="404" alt="Screen Shot 2022-03-27 at 4 28 04 PM" src="https://user-images.githubusercontent.com/91889241/160302350-ff17047f-01f6-4e47-ab70-5e04571c4014.png">

#### Lot 1
The t-tests on Lot 1 shows us while the mean of 1500 is on par to the specifications outlined, the p-value of 1.00 suggests that we can not reject the null hypothesis and do not have sufficient evidence to say that the true mean of PSI to all manufacturing lots is 1,500 lbs/sqin.

<img width="433" alt="Screen Shot 2022-03-27 at 4 28 12 PM" src="https://user-images.githubusercontent.com/91889241/160302383-fb545ae1-44e4-4a0e-8c44-0bea1025ec57.png">

#### Lot 2
The t-tests on Lot 2 shows us while the mean of 1500 is on par to the specifications outlined, the p-value of 0.61 suggests that we can not reject the null hypothesis and do not have sufficient evidence to say that the true mean of PSI to all manufacturing lots is 1,500 lbs/sqin.

<img width="424" alt="Screen Shot 2022-03-27 at 4 28 20 PM" src="https://user-images.githubusercontent.com/91889241/160302391-73c608f9-e639-466c-8eb4-baa31a9f8269.png">

#### Lot 3
The t-tests on Lot 3 shows us while the mean of 1496 is on close to the specifications outlined, the p-value of 0.04 suggests that we can reject the null hypothesis and do have sufficient evidence to say that the true mean of PSI to all manufacturing lots is 1,500 lbs/sqin.

<img width="425" alt="Screen Shot 2022-03-27 at 4 28 28 PM" src="https://user-images.githubusercontent.com/91889241/160302404-b3095e38-fa51-42f5-b01a-048cc980a16b.png">
