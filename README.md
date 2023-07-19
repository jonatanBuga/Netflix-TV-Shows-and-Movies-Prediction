# Netflix TV Series and Movies Analysis

This repository contains preliminary data analysis and prediction phase for a dataset called `titles.csv`. The dataset includes information about TV series and movies available on Netflix. The primary purpose of this repository is to predict a target column named `type`, which indicates whether the entry is a TV series or a movie. We will perform preliminary data analysis (EDA phase) to gain insights into the dataset and then split the data into training and testing files to run classification models for predicting the `type` attribute.

## Table of Contents

1. [Introduction](#introduction)
2. [Preliminary Data Analysis (EDA Phase)](#preliminary-data-analysis)
3. [Data Preprocessing](#data-preprocessing)
4. [Splitting Data](#splitting-data)
5. [Classification Models](#classification-models)
6. [Usage](#usage)
7. [Contributing](#contributing)

## Introduction

Netflix has a vast collection of TV series and movies, and the dataset `titles.csv` provides a snapshot of the available content. The primary objective of this repository is to predict the `type` column, which differentiates between TV series and movies. We will start by performing preliminary data analysis on this dataset to gain insights into the content distribution, genres, and other relevant features. After the EDA phase, we will preprocess the data and then split it into training and testing files to run classification models for predicting the `type` attribute.

## Preliminary Data Analysis (EDA Phase)

The EDA phase involves exploring the dataset to understand its structure and characteristics. We will conduct the following analyses:

- Summary statistics: Analyzing basic statistics like mean, median, minimum, maximum, etc., for numerical features such as ratings, duration, release year, etc.
- Data visualization: Creating various plots, such as bar plots, pie charts, histograms, and scatter plots, to visualize the distribution of genres, ratings, release years, and other relevant features.
- Genre distribution: Investigating the frequency of different genres and identifying the most common genres available on Netflix.
- Content ratings: Analyzing the distribution of content ratings and determining the prevalence of different rating categories.

## Data Preprocessing

Before running the classification models, we need to preprocess the data to handle any missing values, convert categorical variables into numerical representations (if required), and standardize the data. This ensures that the data is in a suitable format for training and testing the models.

## Splitting Data

To assess the performance of our classification models accurately, we will split the dataset into two parts: the training set and the testing set. The training set will be used to train the models, while the testing set will be used to evaluate their predictive accuracy.

## Classification Models

For the prediction phase, we will implement several classification models, such as:

- Logistic Regression
- Random Forest
- Support Vector Machines (SVM)
- Neural Networks (Deep Learning)

We will use popular libraries like scikit-learn, TensorFlow, or PyTorch to build, train, and test these models. After training the models, we will evaluate their performance using appropriate metrics such as accuracy, precision, recall, and F1 score.

## Usage

To use this repository, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Python and the required libraries installed.
3. Run the Jupyter notebook `TV-Show_OR_Movie_at_Netflix.ipynb` to perform the preliminary data analysis and classification model training.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.


---
By following the steps in this README, you will be able to perform preliminary data analysis on the Netflix TV series and movies dataset (`titles.csv`) and run classification models to predict the `type` column, differentiating between TV series and movies. Enjoy exploring the data and experimenting with the models! If you have any questions or need further assistance, feel free to reach out. Happy coding!
