# Movie Recommendation with Year Prediction Project

## Overview

This project demonstrates the application of various machine learning techniques learned during the course. It includes data preprocessing, regression analysis, and clustering to provide movie recommendations and predict the year of release based on movie genres.

## Project Structure

### 1. Data Loading and Preprocessing

The first step involves loading the movie dataset from a CSV file and preprocessing the data to create dummy variables for movie genres. This is essential for converting categorical data into a format suitable for machine learning algorithms.

### 2. Data Transformation

Convert the categorical genre data into dummy/indicator variables to facilitate machine learning model training. This step helps in transforming the data into numerical format, which is required for most machine learning models.

### 3. Year Prediction Using Linear Regression

Using the preprocessed data, we build a linear regression model to predict the year of release of a movie based on its genre. This involves:
- Splitting the data into training and testing sets.
- Training the linear regression model on the training data.
- Predicting the release years for the movies in the testing set.

### 4. Movie Clustering Using K-Means

Apply K-Means clustering to group movies into clusters based on their genres. This helps in identifying similar movies. Each movie is assigned a cluster label, which can be used for recommending similar movies.

### 5. Movie Recommendation System

Based on the clustering results, we create a recommendation system that suggests movies similar to a given movie. This is done by finding movies in the same cluster as the given movie.

## Project Objectives

- **Demonstrate Machine Learning Skills**: The project showcases various machine learning techniques, including regression, clustering, and data preprocessing.
- **Understand Genre Influence**: Analyze how different genres relate to the year of release and how movies can be grouped based on genres.
- **Build a Recommendation System**: Create a simple movie recommendation system based on genre clustering.

## Tools and Libraries Used

- **Pandas**: For data manipulation and preprocessing.
- **Scikit-Learn**: For implementing linear regression and K-Means clustering.

## Conclusion

This project highlights the practical application of machine learning techniques to real-world data. By predicting movie release years and recommending similar movies, we demonstrate how machine learning can provide valuable insights and enhance user experiences.
