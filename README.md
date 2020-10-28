# The median and percentiles

Congratulations on completing the last exercise.  If you are given a data set and are asked to describe the data within it using a sentence such as:

_z % of the data points are less than or equal to x._ 

You know how to determine the value of x if you are given z and the value of z if you are given x.

You are not the first person to realise that describing a data set using a sentence like the one above is useful.  Many other researchers will have written sentences like this about data sets and these researchers wrote codes like those that you have just written.  In addition, these researchers wrote functions that you can reuse to do these calculations for you.  For example, if you have an np array containing the results from some experiments called data you can calculate the x value that z % of the data is less or equal to by using the `np.percentile` function shown below:

````
x = np.percentile( data, z ) 
````

This function works exactly like the code you have written to compute this quantity.

__To complete this exercise I would like you to use `np.percentile` to calculate:__

1. the minimum of the data set
2. the lower quartile
3. the median
4. the upper quartile 
5. the maximum 

for the data contained in the np array called `x`.  These quantities should be saved in variables called `dmin`, `lowq`, `median`, `highq` and `dmax`.  

We can display these 5 points graphically by using a box plot.  I have included some code at the end of the program that will produce a box plot for you.
