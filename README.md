# Dominant-Colour-Extraction
Dominant colour extraction in an image using KMeans 

K-means clustering is a method through which a set of data points can be partitioned into several disjoint subsets where the points in each subset are deemed to be ‘close’ to each other (according to some metric). 

In our case, the ‘data points’ are colours, and the distance function is some measure of ‘how different’ two colours are. Our task is to group these colours into a given number of sets, and then calculate the mean colour of each set. 

## Dependencies ##

* OpenCV
* Numpy
* Sklearn
