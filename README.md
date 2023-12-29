# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import panda as pd

### Step2
Import linear model from sk learn

### Step3
Read the csv file

### Step4
Find the multivariate regression

### Step5
Display the output

## Program:
```
#Developed by: DEVA ABISHEK P
#Register Number: 23012976

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))

```
## Output:
![Multivariate](https://github.com/DEVAABISHEK/Multivariate-Linear-Regression/assets/150319305/483c44e0-1db1-45f8-b199-f86128495562)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
