# BSAN_6070_CA05_kNN_Recommender

## Description

### This code is utilizing data that can be used to help identify similar movies. Based on certain binary categorical variables (ie. genre classifications) and IMDB score of the movies, this code will be using the kNN (k Nearest Neighbors) model to find the top 5 movies that are similar to the another movie that the user is watching. The data will be trained without the classifying label column because we are not asking the model to classify the movie. Since kNN models can only use numerical data to help determine the relationship between the data points, the data will be separated into numerical and nominal data and then the numerical data will be used to determine the 5 nearest neighbors to the movie of interest once the model is fitted around the movie the user is watching.  

## Necessary Libraries and Versions

* Numpy (Version 1.18.0)
* Pandas (Version 2.2.3)
* Scikit Learn (Version 1.6.1)
* NearestNeighbors (function from Scikit Learn Neighbors library) (Version 1.6.1)

## Data Set and the Source

### The data set is an excel sheet with movies and binary classifying information (mainly genre) and numerical data (IMDB score) that is all compiled in one place. This data set was provided by Professor Arin Brahma. You can find the dataset either on this GitHub repository with movie_recommendation_data.csv or you can link it online at ([https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true](https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv)). 

## Source Code Acknowledgement

### There was no source code that was being utilized for this project.

## Software Being Used

### Google CoLab


## Installation

### In order to run this code you need to make sure the following:
* You have internet connection if you plan on getting the data from the direct link to Professor Brahma's GitHub
* If you are planning on doing it on Jupyter Notebook or Google Colab through a direct file, download the movie_recommendation_data.csv file and access it by using the right directory when using the read_csv function.
* Make sure that all necessary packages and libraries are installed.
