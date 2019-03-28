# Final-Project

| Name | Date |
|:-------|:---------------|
|Mehdi Manouchehri | March 29, 2019|


## Research Question

The goal is to figure out whether the breast cancer is benign or malignant with the help of machine learning classification methods.

### Abstract

Breast cancer dataset was chosen for this project. It contains 560 instances with 30 numeric, predictive features. We want to find the best algorithm to be able to have a strong prediction whether is benign or malignant. 
We used KNN, Gaussian NB, and Decision Tree on two features. However, using only two features didn't give us the best prediction, on this phase, our focus was on comparing the accuracy of different algorithms. 
Based on the result, we ended up that Gussian NB was the best. 

### Introduction

The dataset is Breast Cancer Wisconsin which can be downloaded from [here](https://scikit-learn.org/stable/datasets/index.html#breast-cancer-wisconsin-diagnostic-dataset) or sklearn library. Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. The mean, standard error, and “worst” or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. <sup>1</sup> 

### Methods

The below are the algorithms have been used in this project to find out the best answer for the research question:

- K Nearest Neighbors: One of the simplest and most used classification algorithm. Its purpose is to use a database in which the data points are separated into several classes to predict the classification of a new sample point.<sup>2</sup> [(Pseudocode)](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm#Dimension_reduction) 
- Gaussian Naive Bayes: Is a special type of NB algorithm. It’s specifically used when the features have continuous values. It’s also assumed that all the features are following a gaussian distribution i.e, normal distribution.<sup>3</sup> [(Pseudocode)](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Gaussian_naive_Bayes)
- Decision Tree: One of the most popular machine learning algorithms but also the most powerful. One of the reasons they are so powerful is because they can be easily visualised so that a human can understand whats going on.<sup>4</sup> [(Pseudocode)](https://en.wikipedia.org/wiki/Decision_tree_learning#Gini_impurity)

### Results

![alt text](https://user-images.githubusercontent.com/20756635/55119681-2e7b6c80-50c9-11e9-81b3-50f0f85c9fdc.png) ![alt text](https://user-images.githubusercontent.com/20756635/55119717-566ad000-50c9-11e9-8b5b-5afb3d7d042e.png) ![alt text](https://user-images.githubusercontent.com/20756635/55119750-7ac6ac80-50c9-11e9-97cc-4a775c98fffa.png)


<p align="center"><img align="center" src ="https://user-images.githubusercontent.com/20756635/55121711-1a883880-50d2-11e9-932c-3cb4ab6a8163.png" /></p>


### Discussion

We used three algorithms with two features for prediction. Base on the result, Gussian NB gave us more accuracy than the other two.

In this step, no normalization was done on the data. For these kinds of problems like breast cancer which are vital, more accuracy is requeired. So as the next step, first, data normalization and second, using more algorithms on all features are proposed. 

### References
1- https://scikit-learn.org/stable/datasets/index.html#breast-cancer-wisconsin-diagnostic-dataset          
2- https://medium.com/@adi.bronshtein/a-quick-introduction-to-k-nearest-neighbors-algorithm-62214cea29c7     
3- http://dataaspirant.com/2017/02/20/gaussian-naive-bayes-classifier-implementation-python/      
4- https://towardsdatascience.com/a-beginners-guide-to-decision-tree-classification-6d3209353ea    
5- https://github.com/gkiar/cebd1160_project_template
