# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Get the independent variable X and dependent variable Y.
### Step2
from sklearn import linear_ model
### Step3
And then read the cs file
### Step4
Then get the input and assume as X and Y
### Step5
regression=linear_model LinearRegression) regression.fit(x,y)
## Program:
```
import pandas as pd from sklearn import linear_model df=pd. read_csv("car.csv")
x=df|[ 'Volume', 'Weight ']]
y=df[ 'CO2']
regression=linear _model. LinearRegression()
regression. fit(x,y).
print ("Coefficent", regression. coef_)
print ("Intercept"
', regression. intercept_)
-print ("CO2 required is", regression predict(L[3300,1300]1))

```
## Output:

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
