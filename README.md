# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
get the independent varible x and depent varible Y

### Step2
calculate the mean of the x-vlue and the maen of y=Y-value

### Step3
find the slpoe m of the line of best fit usinge the formula 

### Step4
comput the t intercept of the line by using the formula 

### Step5
use the slope m and the Y-intrecept to form the equation of the line 

## Program:
```
import numpy as np from matplotlib import pyplot
*=np. array (eval (input()))
Y=np -array (eval (input()))
Xmean=p-mean (X)
Ymean=p-mean (Y)
num, den =0,0 for i in range(len(X)):
num+= (X[i]-Xmean)*(Y[i]-Ymean)
den+=(X[i]-Xmean)**2
slope=num/den
c=Ymean-slope*Xmean
y_pred=slope*X+c
pyplot. scatter (X,Y, color='red') pyplot.plot(X,y_pred, color='blue')
pyplot. show()





```
## Output:

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
