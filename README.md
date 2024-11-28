# Iris Dataset Analysis and Visualization

This project demonstrates a complete pipeline for analyzing and visualizing the Iris dataset using Python. It includes data preprocessing, model training, evaluation, and data visualization with PCA.

## Features

1. **Data Preparation**: 
   - Loads the Iris dataset.
   - Splits the dataset into training and testing subsets.

2. **Model Training**:
   - Implements a K-Nearest Neighbors (KNN) classifier with `k=3`.

3. **Model Evaluation**:
   - Evaluates model accuracy on the test data.
   - Outputs a classification report for detailed performance metrics.

4. **Visualization**:
   - Uses Principal Component Analysis (PCA) to reduce the data from 4D to 2D for easier visualization.
   - Plots the dataset to visualize the clustering of different species.

## Requirements

The following Python libraries are required to run the project:

- scikit-learn
- matplotlib
- pandas
- numpy

Install the required packages using:
```bash
pip install scikit-learn matplotlib pandas numpy
