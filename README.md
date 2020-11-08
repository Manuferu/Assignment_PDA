# Description of numpy.random package within Numpy v 1.19
## Author: Manuel Fernandez
### Subject: Programming for Data Analysis
### Course: 2020-2021

## Introduction:
The aim of this repository is to give description about the random package within numpy library by in a more visual and statistical way. It is broken down in four parts:

### A) Explanation of the overall purpose of the package:
The first part of the file Assignment.ipynb, consists to play a bit with the creation of random numbers taking getting control with the BitGenerators the Generators and the seeds, in order to get conclusions and to know more in detail the overall purpose of the package. 

### A.1) Comparation between the default_rng and Generator mehtod
Within the section A.1 in the script, there is a comparation between the old method to produce random numbers (default_rng) and the new infrastructure of a bit generator within Generator. 

It has been generated 1000 random numbers by using both methodologies, to analysie the scatter distribution, and the distribution by bins. In this last one, we can observe with 1000 values, the new infrastructure seems to be better distributed than the old one.


### B) Explanation of the use of the “Simple random data” and “Permutations” functions:



### Explanation of the use and purpose of five “Distributions” functions:



### Explanation of the use of seeds in generating pseudorandom numbers:


### Bibliography

#### [1]: numpy.org, numpy.random (https://numpy.org/doc/stable/reference/random/index.html#module-numpy.random)
#### [2] machinelearningmastery.com : (https://machinelearningmastery.com/how-to-generate-random-numbers-in-python/)
#### [3] matplotlib.pyplot.hist (https://matplotlib.org/3.3.2/api/_as_gen/matplotlib.pyplot.hist.html)
#### [4] matplotlib.pyplot.scatter (https://matplotlib.org/3.3.2/api/_as_gen/matplotlib.pyplot.scatter.html)