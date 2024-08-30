# Iris Classification Project

This project involves the acquisition, exploration, and classification of the famous Iris dataset. The goal is to build and evaluate machine learning models to classify iris flowers into three species based on their features.

## Table of Contents

- [Introduction](#introduction)
- [Data Acquisition](#data-acquisition)
- [Data Exploration](#data-exploration)
- [Model Selection](#model-selection)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Iris dataset contains features of iris flowers and their corresponding species. This project aims to explore the dataset, experiment with different classifiers, train selected models, and evaluate their performance using various metrics.

## Data Acquisition

The Iris dataset is obtained from the `sklearn` library. It contains 150 samples with four features each:
- Sepal length
- Sepal width
- Petal length
- Petal width

The target variable represents the species of the iris flower:
- Setosa
- Versicolor
- Virginica

## Data Exploration

In this step, the dataset is explored to understand its structure and characteristics. We print the feature names, target names, and a few sample rows to get an overview of the data.

## Model Selection

We experiment with the following classifiers:
- K-Nearest Neighbors (KNN)
- Decision Trees

## Model Training

The selected models are trained on the Iris dataset. The data is split into training and testing sets, and the features are standardized before training.

## Evaluation

The models' performance is evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score

## Requirements

- Python 3.x
- scikit-learn
- numpy
- pandas (optional, for data handling)

You can install the required packages using the following command:

```bash
pip install scikit-learn numpy pandas
