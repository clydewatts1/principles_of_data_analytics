# Principals of Data Analytics ATU Course Tasks

Author : Clyde Watts

This repository contains the tasks associated with Prinicipals of Data Analytics Module in the 
24-25: Higher Diploma in Science in Computing in Data Analytics

## Files

| Directory        | File Name                            |  Description |
|------------------|--------------------------------------|--------------|
|                  | tasks.ipynb                          | Project task |


## Tasks

## Task 1: Source the Data Set

Import the Iris data set from the `sklearn.datasets` module.  
Explain, in your own words, what the `load_iris()` function returns.  

## Task 2: Explore the Data Structure

Print and explain the shape of the data set, the first and last 5 rows of the data, the feature names, and the target classes.  

## Task 3: Summarize the Data

For each feature in the dataset, calculate and display:  

- mean
- minimum
- maximum
- standard deviation
- median

## Task 4: Visualize Features

Plot histograms for each feature using `matplotlib`.  
Add appropriate titles and axis labels.  

## Task 5: Investigate Relationships

Choose any two features from the data set and create a scatter plot of them.  
Color-code the three different classes of the scatter plot points.

## Task 6: Analyze Relationship

Use `numpy.polyfit` to add a regression line to the scatter plot from Task 5.

## Task 7: Analyze Class Distributions

Create box-plots of the petal lengths for each of the three classes.

## Task 8: Compute Correlations

Calculate the correlation coefficients between the features.  
Display the results as a heatmap using `matplotlib`.  

## Task 9: Fit a Simple Linear Regression

For your two features in Task 5, calculate the coefficient of determination $R^2$.  
Re-create the plot from Task 6 and annotate it with the $R^2$ value.

## Task 10: Too Many Features

Use `seaborn` to create a `pairplot` of the data set.  
Explain, in your own words, what the `pairplot` depicts.  


## Notes

### Development Environments

1. OS : Windows 11
2. IDE : VSC , with Microsoft Python and Jupyter Notebook extension
3. Python / Jupyter - Anaconda
4. Github


### References

- [Iris Dataset]https://scikit-learn.org/1.5/modules/generated/sklearn.datasets.load_iris.html
- [Iris Dataset]https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-dataset
- [Iris Dataset] https://www.amnh.org/learn-teach/curriculum-collections/biodiversity-counts/plant-identification/plant-morphology/parts-of-a-flower
- [Iris Dataset] https://www.kaggle.com/datasets/uciml/iris
- [Numpy plolyfit documentation] https://numpy.org/doc/stable/reference/generated/numpy.polyfit.html
- [How to plot polyfit in scatter plot]https://stackoverflow.com/questions/46627629/how-to-use-numpy-polyfit-to-plot-
- [DataCamp] https://www.datacamp.com/
- [Seaborn pairplot documentation] https://seaborn.pydata.org/generated/seaborn.pairplot.html#seaborn.pairplot
- [Matplotlib documentation] https://matplotlib.org/stable/index.html
- [Github Copilot] 
- [Wikipedia]https://en.wikipedia.org/wiki/Coefficient_of_determinations