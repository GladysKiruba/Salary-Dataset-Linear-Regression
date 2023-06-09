# Salary-Dataset-Linear-Regression
Regression algorithms are used to predict continuous variables like weather, temperature, price etc. It is used when there is a relationship between the input and output labeled data.

**Linear regression:**

Linear regression is one of the most popular widely used algorithms. It is used to predict continuous numerical values. 
Linear regression understands the relationship between the dependent and independent variables. Then it draws a straight line in between the data points and tries to predict the future values.

![image](https://github.com/GladysKiruba/Salary-Dataset-Linear-Regression/assets/121846055/e6264e45-9dd9-4c85-9f09-bcf6965046a5)


The line of regression is also called as best fit line. It is drawn based on the linear equation given below
Y=mx + b    =>     Y=a0+a1*X
Y=Dependent variable
X=Independent variable
a0=Intercept of the line
a1= Linear regression coefficient

**Positive Linear Relationship:**

When the dependent variable in the y axis is increasing as the x axis is increasing, then it is called as positive linear relationship.
Y=a0+a1*X
![image](https://github.com/GladysKiruba/Salary-Dataset-Linear-Regression/assets/121846055/37eabf93-c4d2-4e88-a295-b4e8f997b9d6)


**Negative Linear Relationship**
When the dependent variable in the y axis is decreasing as the x axis increasing, then it is called as positive linear relationship.
Y=-a0+a1*X

![image](https://github.com/GladysKiruba/Salary-Dataset-Linear-Regression/assets/121846055/ea026fda-164c-4a0f-b582-8354c97f8bef)



**Cost function:**

The main aim in regression is to find the best fit line. The best fit line will have minimum error. Error is the difference between the actual value and the predicted value. The coefficient of a0 and a1 determines the best fit line. So cost function is used to find the coefficient of a0 and a1 for the best fit line.

In linear regression we use Mean squared error(MSE) cost function.
MSE=1(1/N)∑i=1 n(yi-(a1x i+a0))2
	N= Total number of observations
	Yi=Actual value
	a1x i+a0=predicted value
  
Residual is the distance between the predicted value and the actual value. If the cost function is high then the observed point is far from the regression line and the residual is also high. If the cost function is less, the observed point is close to the regression line and the residual is also small.


 **Gradient Descent:**
To minimize the cost function (MSE) gradient descent is used. The coefficients of a0 and a1 are updated by the gradient descent method.
The goal is to reach the optimal value. For that the coefficients are randomly selected and step by step it is proceeded to reach the optimal value. The number of steps taken is called as learning rate. This learning rate decides how fast the algorithm reaches the optimal value.
![image](https://github.com/GladysKiruba/Salary-Dataset-Linear-Regression/assets/121846055/9e36ce7b-edca-4261-a240-6c0daef8da92)




 
