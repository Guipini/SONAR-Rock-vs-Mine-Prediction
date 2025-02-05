# Sonar Analysis Project

This project contains sonar data and analysis resources.

## Files

- **Copy of sonar data.csv**: Contains the sonar measurement data.
- **Sonar.ipynb**: A Jupyter Notebook for exploring and analyzing the sonar data.

## How to Use

1. Open the Jupyter Notebook (`Sonar.ipynb`) in Visual Studio Code or your favorite Jupyter environment.
2. Review the data in the CSV file as needed for your analysis.

## Notebook Analysis

### Data Collection and Overview
- Loaded data from `Copy of sonar data.csv` with 208 rows and 61 columns.
- Inspected data using `head()`, `shape`, and `describe()` to understand its structure.
- Analyzed label distribution and group statistics for 'M' (Mine) and 'R' (Rock).

### Data Preprocessing and Modeling
- Separated features (X) and labels (Y) from the dataset.
- Performed a train-test split (10% test size with stratification).
- Trained a Logistic Regression model on the training data.

### Model Evaluation
- Training accuracy achieved approximately 83.4%.
- Test accuracy achieved approximately 76.2%.

### Predictive System
- Implemented a predictive system to classify a sample input.
- The system outputs both the predicted label and a message indicating whether the object is a Rock or a Mine.

