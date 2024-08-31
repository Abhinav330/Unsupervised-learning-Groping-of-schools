[![Codacy Badge](https://app.codacy.com/project/badge/Grade/f592894c3aa54b9fa3a6c4e877c68ff7)](https://app.codacy.com/gh/Abhinav330/Loan-Repayment-Analysis/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
![GitHub Pipenv locked dependency version](https://img.shields.io/github/pipenv/locked/dependency-version/Abhinav330/Unsupervised-learning-Groping-of-schools/matplotlib?color=yellow)
![GitHub Pipenv locked dependency version](https://img.shields.io/github/pipenv/locked/dependency-version/Abhinav330/Unsupervised-learning-Groping-of-schools/numpy?color=yellow)
![GitHub Pipenv locked dependency version](https://img.shields.io/github/pipenv/locked/dependency-version/Abhinav330/Unsupervised-learning-Groping-of-schools/pandas?color=yellow)
![GitHub Pipenv locked dependency version](https://img.shields.io/github/pipenv/locked/dependency-version/Abhinav330/Unsupervised-learning-Groping-of-schools/scikit-learn?color=green)
![GitHub Pipenv locked dependency version](https://img.shields.io/github/pipenv/locked/dependency-version/Abhinav330/Unsupervised-learning-Groping-of-schools/scipy?color=silver)
![GitHub Pipenv locked dependency version](https://img.shields.io/github/pipenv/locked/dependency-version/Abhinav330/Unsupervised-learning-Groping-of-schools/seaborn?color=silver)
![GitHub Pipenv locked Python version](https://img.shields.io/github/pipenv/locked/python-version/Abhinav330/Unsupervised-learning-Groping-of-schools?color=dark%20green)
![GitHub repo size](https://img.shields.io/github/repo-size/Abhinav330/Unsupervised-learning-Groping-of-schools)

# Unsupervised-learning-Groping-of-schools
# Code Summary

TThis Python notebook demonstrates an exploratory data analysis (EDA) and clustering exercise using the pandas, seaborn, and matplotlib libraries. The code works with a dataset called 'College_Data' and explores college-related attributes, including 'Private' status, graduation rates, and enrollment data.

## Data Exploration and Visualization

The code begins by importing the necessary libraries and loading the dataset 'College_Data' using pandas. It then conducts several data exploration and visualization tasks:

- Displays the first few rows of the dataset using `df.head()`.
- Provides dataset information using `df.info()`.
- Generates summary statistics of the dataset using `df.describe()`.
- Creates scatterplots and pairplots to visualize relationships between variables, with points color-coded by 'Private' status.

## Data Preprocessing

The code performs some data preprocessing steps, including:

- Filtering and visualizing data points where 'Grad.Rate' is greater than 100. This might be a data error, and the code appears to set the 'Grad.Rate' of 'Cazenovia College' to 100.
- Using the 'KMeans' clustering algorithm from scikit-learn to cluster colleges into two groups based on their features, excluding the 'Private' column.
- Displaying a scatterplot of 'Enroll' vs. 'F.Undergrad' with points colored by cluster labels.

## Clustering

The code uses the K-means clustering algorithm to cluster colleges into two groups based on their features. It computes cluster centers and assigns each college to a cluster label. The scatterplot at the end visualizes the clustering results.

Overall, this code showcases the use of EDA and K-means clustering for analyzing college data, with a focus on distinguishing between private and non-private institutions based on various features.
