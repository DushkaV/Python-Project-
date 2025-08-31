# Overview

This project demonstrates the use of Python and scikit-learn for image-based machine learning through an eigenfaces exercise. The dataset consists of Spanish chamber of representatives’ images and metadata (name, surname, gender, political party). The notebook walks through the process of data preparation, descriptive analysis, clustering, dimensionality reduction with PCA, and classification.

# Project Workflow

## 1. Data Modeling

- Diputado class stores information (name, surname, gender, party, image).
- Parlament class stores a collection of representatives.

## 2. Data Preparation

- Import dataset (CSV + image files).
- Stack images into arrays and create dependent variables.

## 3. Exploratory Analysis

- Gender proportions.
- Most common male/female names.
- Dataset size and party distribution.

## 4. Image Statistics

- Compute and visualize the mean representative.
- Compute and visualize the standard deviation representative.

## 5. Unsupervised Learning

- K-Means clustering (10 clusters).
- Visualize group samples.

## 6. Dimensionality Reduction

- Principal Component Analysis (PCA) to compute eigenfaces.
- Visualize score plots colored by gender and political affiliation.
- Plot eigenvectors and explained variance.

## 7. Classification

Apply a non-linear classifier to predict gender from representative images.

# Dependencies

Python 3.x
scikit-learn
numpy
matplotlib
seaborn
pandas

# How to Run

## Clone this repository:

git clone https://github.com/yourusername/eigenfaces-project.git
cd eigenfaces-project

## Install dependencies:

pip install -r requirements.txt

## Open the Jupyter notebook:

jupyter notebook "Final work_Python project.ipynb"

# Results

- Gender and party distribution insights.
- Visualization of mean and variance in faces.
- PCA decomposition into eigenfaces.
- Clustering of representatives.
- Gender classification performance using images.

# License

This project is for educational purposes.
