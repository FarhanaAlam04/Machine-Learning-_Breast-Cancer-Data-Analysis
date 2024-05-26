The Breast Cancer Wisconsin (Diagnostic) Data Set, used in this story is publicly available and was created by Dr. William H. Wolberg, physician at the University Of Wisconsin Hospital at Madison, Wisconsin, USA.The features from the data set describe characteristics of the cell nuclei and are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.Ten real-valued features are computed for each cell nucleus:

radius (mean of distances from center to points on the perimeter)
texture (standard deviation of gray-scale values)
perimeter
area
smoothness (local variation in radius lengths)
compactness (perimeter^2 / area - 1.0)
concavity (severity of concave portions of the contour)
concave points (number of concave portions of the contour)
symmetry
fractal dimension ("coastline approximation" - 1)
The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.


The aim of this notebook is  to understand the process of organizing and preparing the data, selecting the features, selecting hyper parameters, choosing and applying the machine learning tools, comparing, and improving the models. Though it is a well known dataset to all, for learning purpuse, I supposed to work on this project as if know nothing about the dataset. So, I started working with Dimentionality check and Unsupervised methods of machine learning to know about the dataset and then worked with Supervised learning.
