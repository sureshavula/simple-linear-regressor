# simple-linear-regressor

#Problem Description :
Given an Employee Dataset which contains YOE(Overall Experience for the Employee in Years) and the salary of each employee in an IT company in India.The company does not have set of rules to set the salary for the new employee they are going to hire. Given this information,design a Machine Learning Model which helps the company to set the salary for a new employee they are going to hire based on no.years of experience. 


#Underlying Principle
Co-relations between the Years of Experience and the salary has to be determined during the proess of Learning.
Determining the correlation between the features and the dependent variable implies constructing a Linear Regressor
infinite number of lines are possible for the given data points.
Best model would be that for which sum of squares of (y^ - y) is minimal.

#Procedure
SciKit Learn has provided LinearRegression class whose instance is a simple Linear Regressor.
This Simple Linear Regressor is fitted with the dataset.
The same Linear Regressor will be used for finding the salary of new employee given his salary.



