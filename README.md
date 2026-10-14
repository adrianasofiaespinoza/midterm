# Credit Score Classification with K-NN

## Overview

This project predicts credit score categories using the **K-Nearest Neighbors (K-NN)** classification algorithm as part of a Kaggle competition.

## Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. **Data cleaning:** Handle invalid values, inconsistent data, and missing values.
2. **Feature engineering:** Convert credit history age into months and remove identifiers from predictive features.
3. **Preprocessing:** Impute missing numerical values using the median, standardize numerical features, and encode categorical features using One-Hot Encoding.
4. **Model training:** Train a K-NN classifier with `n_neighbors=5`, `weights="distance"`, and Euclidean distance.
5. **Evaluation:** Measure accuracy, macro F1-score, weighted F1-score, and analyze the confusion matrix.
6. **Prediction:** Train the final pipeline on all labeled data and generate `submission.csv` for Kaggle.

## Repository Contents

- `knn1.ipynb` — Complete code, preprocessing, training, evaluation, and predictions.
- `README.md` — Project documentation.
- `submission.csv` — Generated Kaggle predictions.
- `video`

## Author

Adriana Sofia Espinoza
