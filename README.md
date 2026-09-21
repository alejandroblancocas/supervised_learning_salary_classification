# Salary Classification with Supervised Learning

Machine Learning project developed as part of the **Aprendizaje Automático I** course.

The objective is to predict whether a person's annual income is above or below $50K using demographic and employment-related information. The project covers the complete supervised learning workflow, including preprocessing, feature selection, model comparison, hyperparameter tuning and final prediction generation.

## Project structure

- `preprocess.ipynb` - Data cleaning, transformation, encoding and feature selection.
- `supervised.ipynb` - Training and comparison of several supervised learning algorithms.
- `best_model.ipynb` - Final model selection, feature importance analysis and prediction generation.
- `memoria.pdf` - Full explanation of the methodology, experiments and results.

## Models explored

Several supervised learning approaches were evaluated, including:

- Linear and Logistic Regression
- Decision Trees
- Random Forest
- Extra Trees
- K-Nearest Neighbors
- Support Vector Machines
- Neural Networks with TensorFlow/Keras

Hyperparameter tuning and model selection were performed using techniques such as cross-validation, `GridSearchCV` and Keras Tuner.

## Technologies

**Python · Pandas · NumPy · Scikit-learn · TensorFlow/Keras · Imbalanced-learn · Matplotlib · Seaborn**

## Dataset

The original training and test datasets are not included in this repository.

They were provided as part of the university assignment and contain demographic and employment-related information for an income classification problem.

The notebooks contain the complete preprocessing pipeline and expect the corresponding CSV files to be available locally before execution.

## Documentation

A detailed description of the preprocessing decisions, models tested, experiments and results can be found in [`memoria.pdf`](./memoria.pdf).
