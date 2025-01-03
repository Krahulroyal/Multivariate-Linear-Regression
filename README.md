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
df. info()
df. head()
df.tailo
x=df[[ 'Weight', 'Volume' ]]
y=df ['CO2']|
regr-linear_model. LinearRegression()
regr. fit(x,y)
print('Coeffients:',regr.coef_)
print ('Intercept:' ,regr.intercept_)
predictedC02=regr-predict([[3300,1300]])
print( 'Predicted CO2 for the corresponding weight and volume', predictedC02)
```
## Output:
### Insert your output
![alt text](<Screenshot 2025-01-03 160625-1.png>)
<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
