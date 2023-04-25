# Final-Project

## Breast Cancer Classification using SVM's.
By: Aarav Desai, Sanjay Subramanian, Tanmay, Runze Shao, Shahab Khorasanizadeh, and Justin Estes

We got our data from [BCSC](https://www.bcsc-research.org/data/rfdataset/dataset). We used the 2nd risk estimation dataset in our project, which contained over 100,000 rows of data.



# Support Vector Machines #

“The support-vector network is a new learning machine for two-group classification problems.”

- Corinna Cortes and Vladimir Vapnik (1995) in their paper “Support-Vector Networks”

An SVM is a supervised machine learning model that is trained using past examples of successfully completed predictions. Then it is provided with new testing data to perform operations based on samples.

According to Rohith Gandhi, in his article “Support Vector Machine — Introduction to Machine Learning Algorithms,” the main objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space that distinctly classifies the data points.

A hyperplane is a decision boundary that helps with classifying data points.The problem with finding a hyperplane is that there are multiple possible hyperplanes (as shown in Fig. 2). The goal of an SVM is to find a hyperplane in an N-dimensional space that distinctly classifies the data points.

### But how can we define such a hyperplane? ###

# Hyperplanes #
When defining a hyperplane in an SVM, the number one thing to consider is maximizing the margin distance. This enables future data points to be classified by the agent with more confidence. In short, this means that SVMs aim to make the margin distance between the hyperplane and the data points as large as possible to ensure that data points are correctly classified. This is part of a concept called Large Margin Intuition.

Large margin intuition refers to the idea that having a larger margin between the decision boundary (or hyperplane) and the closest data points from each class is more desirable. A larger margin leads to a more robust and generalizable model.

Some key properties of a hyperplane include:

Linearity — A hyperplane is a linear boundary that separates the data into different classes. It is represented mathematically by a set of coefficients (w) and a bias (b) that define the equation of the hyperplane: w.x + b = 0

Dimensionality — a hyperplane is a subspace with one dimension less than the space it is in. In a two-dimensional space, a hyperplane is a line. In a three-dimensional space, it’s a plane, and so on.

Separability — hyperplanes are used to separate data into different classes by finding the optimal boundary that maximizes the margin, which is the distance between the boundary and the closest data points from each class.

Margin — the margin is the distance between the hyperplane and the closest data points from each class. The goal is to find the hyperplane that maximizes the margin, which improves the generalization ability of the model.

Support Vectors — the data points that are closest to the boundary are called support vectors and have the greatest impact on the position of the boundary.

Non-unique — Hyperplane is not unique, there can be multiple hyperplanes which can separate the data into different classes.
Computationally efficient — SVM algorithm is computationally efficient, it can handle large amount of data set and able to classify them.

The data points closest to the boundary formed by the hyperplane are called support vectors. They have the most significant impact on the position of the boundary. These data points are crucial in programming an SVM.


## Description

### Motivation

The motivation for this project was to use power of machine learning and its tools to analyze large amounts of data to visualize the various patterns between the patients and quickly identify the patients that are diagnosed with breast cancer which may not be visible to experts.

### Tools Used

- For the exploratory data analysis part we used a combination of Matplotlib and seaborn to create various plots like histograms, heatmap, correlation matrix, violin plots and strip plots. 

- In the machine learning part we used the sklearn library to create a linear regression model to predict the R-squared value amongst the cancer feature in the dataset with the others.

- In the sklearn library we also used the svm function to create a support vector machine that splits our data into testing and training dataset and gives us a confusion matrix with the classified data with 0 representing patients without cancer and 1 representing patients with cancer.


```python

```
