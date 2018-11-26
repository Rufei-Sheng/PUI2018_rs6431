# PUI2018 HW 10.


### Assignment 1. 
This assignment aims at practicing polynomial model and interpreting the likelihood ratio to choose the model. I do this assignment alone. 


### Assignment 2. 
This assignment amis at builing model from real life data (the units of the building and its energy consumption), with the analysis of polynomial model, errors, how to fit a line, and likelihood ration. In addtion, I learned the magic of log scales.

I do this assignment most by myself. But several points consult others: (1) when coverting to log base, the Geopandas fail to plot. After consulting Dr.Bianco, I find the reason is that log(0) is infinite. Therefore, we need to use log(x+1) rather than log(x). (2) When fitted the line to the polynomial model, the "line" is mass. After helping by Borong, I change the line to the point "o" to adress this problem. (or I can use sort to address this problem).

However, several points need to further clarify: such as why we need error (x-axis/y-axis), how it influences the interpretation of the model, the error Vs the chi-square, and why "maximizing the log likelihood is the same as minimizing the chi square".

