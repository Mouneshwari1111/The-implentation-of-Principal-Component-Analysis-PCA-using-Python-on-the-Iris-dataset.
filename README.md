# PCA on Iris Dataset

## Overview
This project demonstrates the implementation of **Principal Component Analysis (PCA)** using Python to reduce the dimensionality of the Iris dataset. The original dataset contains **4 features**, and PCA is used to reduce them to **2 principal components** for easier visualization.

## Objective
The main objective of this project is to:
- Understand dimensionality reduction.
- Apply PCA on a real dataset.
- Visualize high-dimensional data in 2D.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Dataset
The program uses the **Iris dataset** available in the **scikit-learn library**.  
It contains **150 samples** of iris flowers with the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset includes **three classes**:
- Setosa
- Versicolor
- Virginica

## Methodology
1. Load the Iris dataset using sklearn.
2. Convert the dataset into a Pandas DataFrame.
3. Apply PCA to reduce the dataset from **4 dimensions to 2 dimensions**.
4. Store the transformed data.
5. Visualize the reduced data using a **scatter plot**.

## Output
The output shows a **2D scatter plot** where each color represents a different iris species. This helps visualize how PCA separates the classes while reducing dimensions.

## Conclusion
PCA helps reduce the complexity of data while preserving the most important information. It is widely used in **machine learning, data analysis, and visualization** for handling high-dimensional datasets.
