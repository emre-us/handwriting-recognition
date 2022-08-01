# handwriting-recognition

## Handwritten Numbers

This project attempts to predict digits from handwritten numbers. It was originally presented to AT&T Bell Labs to help build automatic mail-sorting machines for the USPS. It has been used since early 1990s to compare machine learning performance on pattern recognition.

The main aim is to predict the number written based on the darkness of each pixel. This is a classification problem and considers kNN and Random Forest approaches along with a simple ensemble of the two.

It uses the following packages:

dslabs for the MNIST data <\br>
tidyverse for tidy data <\br>
dplyr for data wrangling <\br>
ggplot2 for visualisations<\br>
caret for machine learning, for resampling and model training, including kNN
randomForest for carrying out random forest

and 

matrixStats as an option for calculating matrix statistics (eg rowSds, colSds)

The MNIST data is provided by the dslabs package. You can find more info on its online documentation here:  http://yann.lecun.com/exdb/mnist/

This is a project from HarvardX Data Science programme. For more information see www.edx.org and the book Introduction to Data Science: Data Analysis and Prediction Algorithms with R by Raafael A Irizarry (https://rafalab.github.io/dsbook/)

You may also want to check out the book Hands-on Machine Learning with R by Bradley Boehmke & Brandon Greenwell (https://bradleyboehmke.github.io/HOML/index.html), especially Chapter 8.
