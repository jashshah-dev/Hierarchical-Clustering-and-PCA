# Hierarchical-Clustering-and-PCA
Python Codebase that implements hierarchical clustering and effects of PCA on clustering



This repository provides a Python implementation of Hierarchical Clustering from scratch and demonstrates the comparison of clustering results before and after applying Principal Component Analysis (PCA). The code allows for the exploration and evaluation of Hierarchical Clustering algorithms, as well as the assessment of the impact of PCA on clustering performance. The analysis is conducted using the 130 Hospitals Diabetic Dataset from the US.

## Contents

- [Background](#background)
- [Features](#features)
- [Dataset](#dataset)
- [Implementation](#implementation)
- [Comparison Metric Used](#Comparison-Metric-Used)
- [Results](#results)


## Background

This project focuses on the implementation and evaluation of Hierarchical Clustering algorithms. Hierarchical Clustering is a widely used unsupervised learning technique that aims to discover inherent structures and patterns within a dataset by creating a hierarchy of clusters. Unlike other clustering algorithms, Hierarchical Clustering does not require the specification of the number of clusters in advance.

Hierarchical Clustering operates by iteratively merging or splitting clusters based on their proximity, resulting in a hierarchical structure called a dendrogram. This dendrogram provides a visual representation of the clustering process and enables the identification of meaningful clusters at various levels of granularity.

In this project, we explore the effectiveness of Hierarchical Clustering algorithms on the 130 Hospitals Diabetic Dataset from the US. The dataset contains a diverse set of features related to diabetic patients, including patient demographics, medical history, treatment details, and hospital-specific information. By applying Hierarchical Clustering to this dataset, we aim to uncover latent patterns and relationships among the patients, which can offer valuable insights for personalized healthcare and treatment strategies.

We implement three commonly used variations of Hierarchical Clustering: single-linkage, complete-linkage, and average-linkage. These algorithms differ in the way they measure the proximity between clusters and determine the optimal merging or splitting points. By comparing the results obtained from these algorithms, we gain a comprehensive understanding of their strengths and limitations in different scenarios.

Furthermore, we explore the combination of Hierarchical Clustering with Principal Component Analysis (PCA) for dimensionality reduction. PCA allows us to transform high-dimensional data into a lower-dimensional space while retaining most of the information. By applying PCA before performing Hierarchical Clustering, we can potentially improve the clustering results and gain insights into the most significant features driving the clustering patterns.


## Features

Implementation of Hierarchical Clustering algorithms.
Integration of PCA for dimensionality reduction and enhanced clustering performance
Comparison of clustering results before and after applying PCA
Utilization of the RNA Seq Dataset

## Dataset

For Hierarchical clustering the dataset used is RNA sequence Datasets



## Results

• After applying Heirarchial clustering on reduced dataset from PCA we can see the Square root of
Within Sum of Square Errors decreases.

• PCA is used to reduce the number of variables that are used to calculate the distance between
observations, which can in turn decrease the within sum of square errors.
Problem 2 continued on next page. . . Page 27 of 46

• When performing hierarchical clustering, the distance between two observations is typically calculated based on the values of all the variables in the dataset. However, if the dataset contains
many variables, some of which may be highly correlated, then including all of these variables
in the distance calculation can lead to redundant information and an overemphasis on certain
features.

• By using PCA to reduce the number of variables used in the distance calculation, we can focus
on the most important features of the data and eliminate the effects of correlated variables. This
can lead to a more accurate clustering solution and a decrease in the within sum of square errors.

• Thus after applying PCA we get the Normalized Sum of Square errors as 5600.074


![image](https://github.com/jashshah-dev/Hierarchical-Clustering-and-PCA/assets/132673402/7134c5dd-726f-4157-a686-4598b1332908)

![image](https://github.com/jashshah-dev/Hierarchical-Clustering-and-PCA/assets/132673402/fb4cd934-2703-4eaf-b84b-7ac086f48830)

![image](https://github.com/jashshah-dev/Hierarchical-Clustering-and-PCA/assets/132673402/74523fbd-ddd7-4063-a051-38c4182f2021)

![image](https://github.com/jashshah-dev/Hierarchical-Clustering-and-PCA/assets/132673402/0be642f5-67c3-41e8-ae79-fc1f94a4d1c6)

![image](https://github.com/jashshah-dev/Hierarchical-Clustering-and-PCA/assets/132673402/2c99980a-491c-4e71-b0fe-5a431d7a28d4)

![image](https://github.com/jashshah-dev/Hierarchical-Clustering-and-PCA/assets/132673402/281c7661-b084-4573-be32-6426907240e3)






