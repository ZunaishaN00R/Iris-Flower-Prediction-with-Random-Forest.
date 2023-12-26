# Iris-Flower-Prediction-with-Random-Forest.
Use a Random Forest on the famous iris dataset. Begin with default settings (10 trees), then enhance accuracy by finding the sweet spot for the number of trees. Witness the simplicity of predicting iris flower species with Random Forests!

# Random Forest Classifier for Iris Flower Species Prediction

This Python script demonstrates the use of the Random Forest classifier to predict the species of Iris flowers using the famous Iris dataset from scikit-learn. The dataset consists of measurements for 150 iris flowers from three different species: setosa, versicolor, and virginica.

## Usage

The script is divided into two parts:

### 1. Default Random Forest Classifier

In the first part, the script uses a default Random Forest classifier with `n_estimators=10` (default value). It splits the dataset into training and testing sets, fits the classifier, makes predictions, and calculates the accuracy score. The accuracy score for the default configuration is printed.

### 2. Fine-tuning with Grid Search

The second part utilizes a Grid Search approach to fine-tune the Random Forest classifier by testing different values for the number of trees (`n_estimators`). The script creates a parameter grid with values `[10, 50, 100, 150, 200]` for `n_estimators` and performs a grid search using cross-validation.

The best-performing Random Forest model is extracted from the grid search results, and its accuracy on the test set is calculated and printed. Additionally, a plot is generated to visualize how the mean test score changes with different numbers of trees.

## Dependencies

- scikit-learn
- numpy
- matplotlib

## Instructions

1. Ensure you have the required dependencies installed.
2. Run the script in a Jupyter environment or a Python environment that supports the specified dependencies.

## Results

The script outputs the accuracy of the default Random Forest classifier and the best accuracy achieved after fine-tuning with different numbers of trees. The plot visually represents the mean test scores for each configuration.

