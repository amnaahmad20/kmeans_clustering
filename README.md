# kmeans_clustering
# K-means Clustering - Lab

(http://learn.co/content-license)

## Introduction

In this lab, we'll learn how to use scikit-learn's implementation of the K-means Clustering algorithm to analyze a dataset!

## Objectives

You will be able to:

* Demonstrate an understanding of how the K-means Clustering algorithm works
* Perform K-means Clustering with scikit-learn and interpret results
* Use metrics such as Calinski Harabaz Scores (Variance Ratios) to determine the optimal number of clusters


## Understanding the K-means Algorithm 

The k-means clustering algorithm is an iterative algorithm that reaches for a pre-determined number of clusters within an unlabeled dataset, and basically works as follows:

- select k initial seeds
- assign each observation to the cluster to which it is "closest" 
- recompute the cluster centroids
- reassign the observations to one of the clusters according to some rule
- stop if there is no reallocation

## Creating a Dataset

For this lab, we'll create a synthetic dataset to work with, so that there are clearly defined clusters we can work with to see how well the algorithm performs. 
