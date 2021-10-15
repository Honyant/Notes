# Chapter 3

- [Chapter 3](#chapter-3)
  - [Some Cases of Unusual Points](#some-cases-of-unusual-points)
  - [Getting LSRL from those values](#getting-lsrl-from-those-values)
  - [What removing things does](#what-removing-things-does)
    - [Removing the point for child 18](#removing-the-point-for-child-18)
    - [Removing the point for child 19](#removing-the-point-for-child-19)
      - [Sample Problem on sheet](#sample-problem-on-sheet)
  - [Test Stuff to know](#test-stuff-to-know)
  
## Some Cases of Unusual Points

The point $(\bar{x} , \bar{y}) $is always on the LSRG.

$\bar{y} =a +b \bar{x}$

$b=r\frac{S_y}{S_x}$

$a= \bar y -b \bar x$

## Getting LSRL from those values

$$b=\frac{0.49*12.7}{2.3}=2.71$$

$$104.9=a+2.71(12.3)$$

$$a=104.9-2.71(12.3)$$

$$a=71.5y$$

$$\hat{y}=71.57+2.71x$$

$\therefore \hat y$ increases by $0.49S_y$ per increase in x

Regression to the mean means that the predicted value of y changes by less than 1 SD when x changes by 1 SD.

Specifically by r SDs.

Points with **high leverage** in regression have much larger or smaller x cause thant the other points in the dataset.

An **outlier** in regression is a point that doesn't not follow the pattern of the data and has a large residual. (No formal def for outliers, its just a judgement call)

An **influential point** in regression is any point that, if removed, substantially changes $(b,a r,r^2,s)$. The are outliers + points with high leverage are influential pts.

## What removing things does

*Child 18 is an outlier on x axis (on the right), Child 19 is an outlier for the residuals (up)*

### Removing the point for child 18

- decrease the magnitude of the slope
- decrease the y intercept
- slightly increased $S_{d Residuals}$
- greatly decreased $r^2$

### Removing the point for child 19

- decreased the slope.
- barely increased the y intercept
- greatly decreased $S_{d Residuals}$ (we got rid of a large residual)
- increased $r^2$

#### Sample Problem on sheet

$\frac{5}{7} = 0.7142857142=71.428\%$

$\frac{6}{9}=0.6666666666=66.666\%$

## Test Stuff to know

- Use "predict" or "prediction"
- all the "interpret" language.
- 4 characteristics of a scatterplot
- outlier vs high leverage
- reading calc outputs
- patterns in residual plots
- patterns in residual plots if you see a linear pattern w/ + or - slope, check that xlist is $L_1$ not $L_2$
- when does the value of r tell me anything useful(only when linear assoc)
  