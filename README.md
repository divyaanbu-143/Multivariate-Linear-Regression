# Implementation of Multivariate Linear Regression
# Date : 18.05.2024
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
1. import the NumPy library using the statement import numpy as np.

### Step2

2. Define the given matrix A
### Step3
3. Compute the Multivariate Linear Regression using np.linalg.inv()

### Step4
4. print and end the program


## Program:
```
'''
program to find 1-norm of a matrix.
Developed by: A.Divya
Register Number: 2305002007
'''
import pandas as pd
from sklearn import linear_model
Thus the multivariate linear regression is implemented and predicted the output using python
program.
data=pd.read_csv("car.csv")
x=data[['Weight','Volume']]
y=data['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print("Predicted CO2 for the corresponding weight and volume",predictedCO2)






```
## Output:

![Screenshot 2024-05-24 161831](https://github.com/divyaanbu-143/Multivariate-Linear-Regression/assets/155506447/4403eb88-fc67-4fc0-8639-65856951e3f0)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
