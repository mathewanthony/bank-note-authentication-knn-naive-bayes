# Bank Note Authentication using Machine Learning

This repository contains code for a machine learning project focused on bank note authentication. The project utilizes K-Nearest Neighbors (KNN) and Naive Bayes algorithms to classify bank notes as genuine or counterfeit based on various features extracted from images.

## Overview

The goal of this project is to demonstrate the effectiveness of machine learning algorithms in detecting counterfeit bank notes. The dataset used for training includes features such as variance, skewness, kurtosis, and entropy, which are extracted from images of bank notes. The project aims to showcase the application of machine learning algorithms in detecting counterfeit bank notes.

## Code Overview

This project consists of Python code for implementing K-Nearest Neighbors (KNN) and Naive Bayes classifiers. Here's a brief overview of the code:

- `bank_note_authentication.ipynb`: Jupyter Notebook containing the Python code for the project.
- `README.md`: This file providing an overview of the project.

## Dependencies

- pandas
- scikit-learn

Install the required packages using pip:

```bash
pip install pandas scikit-learn
```

## Usage


This code demonstrates the process of training and evaluating KNN and Naive Bayes classifiers for bank note authentication.
It follows these steps:

1. Loading the dataset: The features and labels are loaded from the dataset. (Note: The dataset file is not provided in this repository.)
2. Preprocessing the data: The features are scaled using StandardScaler.
3. Splitting the data: The dataset is split into training and testing sets.
4. Training the models: KNN and Naive Bayes classifiers are trained on the training data.
5. Evaluating the models: The accuracy, confusion matrix, and classification report are generated for both classifiers using the test data.

## Results

The results of the classification are printed, including accuracy, confusion matrix, and classification report for both KNN and Naive Bayes classifiers.

## Note

This repository does not include the dataset file (bank_note_dataset.csv) or any Python script (bank_note_authentication.py).

You'll need to provide your own dataset file and create Python scripts if needed.
