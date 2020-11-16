# Description of numpy.random package within Numpy v 1.19
## Author: Manuel Fernandez
### Subject: Programming for Data Analysis
### Course: 2020-2021

## Introduction:
The aim of this repository is to give description about the random package within numpy library by in a more visual and statistical way. It is broken down in four parts:

### A) Explanation of the overall purpose of the package:[1],[2]
The first part of the file Assignment.ipynb, consists to play a bit with the creation of random numbers taking getting control with the BitGenerators the Generators and the seeds, in order to get conclusions and to know more in detail the overall purpose of the package. 

### A.1) Comparation between the default_rng and Generator mehtod [1], [2]
Within the section A.1 in the script, there is a comparation between the old method to produce random numbers (default_rng) and the new infrastructure of a bit generator within Generator. 

It has been generated 1000 random numbers by using both methodologies, to analysie the scatter distribution, and the distribution by bins. In this last one, we can observe with 1000 values, the new infrastructure seems to be better distributed than the old one.


### B) Explanation of the use of the “Simple random data” and “Permutations” functions [1],[5],[6]:

The first part try to go throughly through each of the simple random data variables. To describe each of the variables, it has been add a print to see what is the output, and a plot to represent distributions:


The second part describes the two permutation options numpy.random function provides, which are Shuffle and Permutations. Basically, each of the positions of the array. The only difference it has been noticed is, as demonstrated in Assignment.ipyb file, when it comes to save shuffle function to a variable, it doesnt't allow to meanwhile with permutation it does.


### C) Explanation of the use and purpose of five “Distributions” functions:
Those are the functions explained in this file:
-numpy.random.chisquare [7]: it takes 2 variables, which are degrees of freedom and the size (this last one is optional, if no number in size, output is one number). Interesting to see that if we increase the degrees of freedom and the size to very large values, we will get a normal distribution.

-numpy.random.binomial [8]: It takes three arguments, number of trials, probability of each trial and the numbe of times. Interesting again to see, if the probability is 0.5 the numbers will be generated following a normal distribution 100% of those will be between the range (0,n), where n is the number of trials. If the probability is below 0.5, the distribution will go to the left, if above 0.5 will tend to do the oposite. Allways the distribution mean will be centered at the number = probability (p)x number of trials (n)


### Explanation of the use of seeds in generating pseudorandom numbers:


### Bibliography

#### [1]: numpy.org, numpy.random (https://numpy.org/doc/stable/reference/random/index.html#module-numpy.random)
#### [2] machinelearningmastery.com : (https://machinelearningmastery.com/how-to-generate-random-numbers-in-python/)
#### [3] matplotlib.pyplot.hist (https://matplotlib.org/3.3.2/api/_as_gen/matplotlib.pyplot.hist.html)
#### [4] matplotlib.pyplot.scatter: (https://matplotlib.org/3.3.2/api/_as_gen/matplotlib.pyplot.scatter.html)
#### [5] numpy.org, numpy.random.shuffle: (https://numpy.org/doc/stable/reference/random/generated/numpy.random.shuffle.html)
#### [6] numpy.org, numpy.random.permutation: (https://het.as.utexas.edu/HET/Software/Numpy/reference/generated/numpy.random.permutation.html)
#### [7] numpy.org, numpy.random.chisquare: (https://numpy.org/doc/stable/reference/random/generated/numpy.random.chisquare.html)
#### [8] numpy.org, numpt.random.binomial : (https://het.as.utexas.edu/HET/Software/Numpy/reference/generated/numpy.random.binomial.html)