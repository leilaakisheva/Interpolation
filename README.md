# Interpolation
In this assignment we interpolate the given function using various methods and then compare their efficiency. It was found that cubic interpolation of logarithm of the given function is the most efficient method in terms of computational cost.

## ntroduction
In this assignment, we are given the values of a function f(x) at 9 data points and asked to interpolate between them using linear and cubic splines. We will then plot all the interpolating functions obtained from both methods and perform a visual assessment of their quality. After, it is asked to compare the quantitative accuracy and computational cost of both methods to determine which one is better.

The main hypothesis is that cubic spline interpolation of log of our function will work out the best because it provides a smooth and continuous approximation of the underlying data.

By using the logarithm of the function as the input to the interpolation algorithm, we can further improve the accuracy and stability of the interpolation, especially when dealing with data that exhibits large variations or extreme values. Overall, the cubic spline interpolation of the logarithm of our function is expected to provide the most reliable and efficient method for approximating the function over a wide range of input values.

![image](https://github.com/leilaakisheva/Interpolation/assets/128895782/453bacab-6932-47b1-a3b0-40c13b15322a)

Method           RMSD         Time         Cost
----------  ---------  -----------  -----------
Cubic        6.9556    0.000901479  1.2366e-06
Linear      11.7389    0.000238126  2.97658e-05
Log Cubic    0.378471  0.000328589  4.50739e-07
Log Linear   0.982317  0.0166966    0.00208708


## Results
It can be seen in the plot that all the methods visually are pretty accurate. However, if we look at the Root Mean Squared Deviation error and Cost, it can be seen that methods significantly vary. It can be clearly seen that the most efficient method with the least error is Log Cubic method.

In conclusion, this problem involved generating linear and cubic splines to interpolate between 9 data points of the given function. The interpolation was done both directly and after taking the logarithm of the function. It was found that logarithmic cubic spline interpolation was the most efficient method with the least error, indicating that it provided the best quantitative accuracy with the least computational cost.
