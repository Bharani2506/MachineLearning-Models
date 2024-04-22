# Machine Learning Customer Classification

## Project Overview
This repository hosts machine learning models to predict customer behavior for a telecommunication campaign. It aims to identify potential customers likely to subscribe to services using various machine learning models.

## Models Explored
The repository explores several machine learning models:
- Logistic Regression
- Decision Trees
- Random Forest
- Neural Networks
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- Ridge Regression

## Data Preprocessing
Data preparation involved:
- Loading data into a Python notebook.
- Handling missing values and irrelevant data.
- One-hot encoding for categorical variables.
- Splitting data into a 70/30 train-test ratio.

## Feature Selection
Features were selected based on the chi-squared test. A total of 20 random features were chosen for their significance in the models.

## Modeling and Evaluation
The models were evaluated based on:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Cross-validation was performed using a 10-fold strategy to ensure the robustness and generalizability of the models.

## Best Performing Model
K-Nearest Neighbors (KNN) was identified as the best-performing model based on cross-validation results due to its high accuracy and consistency.

## Implementation
Each model is implemented in Python, and the repository includes scripts for training, testing, and evaluating the models.

## Getting Started
To run the models locally:
1. Clone the repository.
2. Install required Python packages (`scikit-learn`, `numpy`, `pandas`, `matplotlib`).
3. Execute the scripts to train and evaluate the models.

## Contributions
Contributions to this project are welcome. You can contribute by improving the existing models, adding new models, or enhancing the data preprocessing steps.

## Licensing
This project is released under the MIT License. See the LICENSE file in the repository for more details.

## Further Reading
References and additional resources are provided to help understand the implementations and theoretical background of the models used.

## Contact
For more information or queries, please open an issue in the repository.

