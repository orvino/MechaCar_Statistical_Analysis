# **MechaCar_Statistical_Analysis**
## **Deliverable 1**
## *Multiple Linear Regression*
Multiple Linear Regression(MLR) is a statistical model that extends the scope and flexibility of a simple inear regression model.  In an MLR, we us multiple independent variables to account for parts of the total variance observed in the dependent variable, in this case, miles per gallon(mpg).  

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
According to our results, the probability that each variable(coefficient) contributes a random amount of variance to the model, vehicle length and ground clearance are statistically unlikely to provide random amounts of variance to the model.  

### Is the slope of the linear model considered to be zero? Why or why not?
By observing the p-value of less than 0.05, our slope is not zero.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
We are using variables vehicle lenght, vehicle weight, spoiler angle, ground clearance and all wheeel drive(AWD) to see the effects on mpg.  To determine which variables provide significant contribution to the model, we observe the individual p-values.

Then we can answer our question for the test, *Does this model predict the mgp of the MechCar prototypes effectively?*.  Based on our R-squared of 0.7149 or 71%, our model predicted the mpg values accruately.  To increase our comfort of predicatability, we would need to look for other factors not included in this dataset or model.

## **Deliverable 2**
## *
