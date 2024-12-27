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
Calculate the mean of the X -values and the mean of the Y -values.
### Step3
Find the slope m of the line of best fit using the formula.
### Step4
Compute the y -intercept of the line by using the formula:
### Step5
Use the slope m and the y -intercept to form the equation of the line.
## Program:
```
Developed by: K Rahul Royal
#Reg number:24001378

import numpy as np
import matplotlib.pyplot as plt
x = np.array([2,3,4,5,6,7,8,9])
y = np.array([3,4,5,6,7,8,9,10])
plt.scatter(x,y)
plt.show()
xmean = np.mean(x)
ymean = np.mean(y)
num=0
den=0
for i in range(len(x)):
num+=(x[i]-xmean)*(y[i]-ymean)
den+=(x[i]-xmean)**2
m = num/den
b = ymean - m*xmean
print(m,b)
ypred = m*x+b
print(ypred)
plt.scatter(x,y,color=
plt.plot(x,ypred,color=
plt.show()
'Red')
'Blue')
```
## Output:

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
