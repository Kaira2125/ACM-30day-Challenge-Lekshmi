# **TEXT DATASET – PHASE 4**
## **1. Importing Libraries & Loading Dataset**
- I started by importing the necessary Python libraries for text processing, dimensionality reduction, and clustering.
- The dataset used is the 20 Newsgroups dataset, which contains documents categorized into 20 different topics.
## **2. Text Preprocessing with TF-IDF**
- I applied TF-IDF vectorization, which transforms raw text into numerical vectors based on word importance.
- The resulting TF-IDF matrix is high-dimensional and sparse, which is typical for text datasets.
## **3. Dimensionality Reduction with Truncated SVD**
- I used Truncated SVD to reduce the number of features while preserving essential structure.This makes the data easier to visualize and speeds up computations.
- I also created a 2D scatter plot using the first two components for a better visual understanding.
## **4. Clustering with KMeans**
- I applied KMeans clustering to group the documents into 20 clusters, matching the original number of categories.
- The clustering was unsupervised, meaning it was done without using the actual labels.
- A Silhouette Score was calculated to evaluate how well the documents were clustered.

