# Feature Engineering & Preprocessing Pipeline

## Project Overview

This project focuses on building a robust, leak-free machine learning preprocessing pipeline using Python and Scikit-Learn.

The Titanic passenger survival dataset is used to demonstrate data cleaning, feature engineering, preprocessing, and machine learning model evaluation.

## Objectives

- Handle missing values using imputation.
- Scale numerical features using StandardScaler.
- Encode categorical features using One-Hot Encoding.
- Prevent data leakage through proper train-test splitting.
- Build a reusable preprocessing pipeline using Pipeline and ColumnTransformer.
- Analyze feature importance and correlation between numerical features.

## Dataset

**Dataset:** Titanic Passenger Survival Dataset

**File:** `titanic.csv`

The dataset contains passenger information such as age, gender, passenger class, fare, and survival status.

**Target variable:** `Survived`

- `0` — Did not survive
- `1` — Survived

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Load and inspect the dataset.
2. Separate features and target variable.
3. Split the dataset into training and testing sets.
4. Identify numerical and categorical features.
5. Handle missing values using SimpleImputer.
6. Scale numerical features using StandardScaler.
7. Encode categorical features using OneHotEncoder.
8. Build a reusable preprocessing pipeline using ColumnTransformer.
9. Train a Random Forest classification model.
10. Evaluate model performance using accuracy, precision, recall, and F1-score.
11. Perform feature importance analysis.
12. Conduct correlation analysis using a heatmap.

## Machine Learning Model

A Random Forest Classifier is used to predict passenger survival.

The model is trained using the training dataset and evaluated using the testing dataset.

## Results

The notebook displays the model's evaluation metrics, feature importance rankings, and correlation heatmap.

The model's actual accuracy and other evaluation results are available in the Jupyter Notebook.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. Open the notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Feature_Engineering_Preprocessing_Pipeline.ipynb`.
5. Run all cells from beginning to end.

## Project Files

- `Feature_Engineering_Preprocessing_Pipeline.ipynb` — Complete machine learning project.
- `titanic.csv` — Dataset used for training and evaluation.
- `README.md` — Project documentation.

## Conclusion

This project demonstrates how to build a reusable machine learning preprocessing pipeline that handles missing values, scales numerical data, encodes categorical features, and prevents data leakage.

It also demonstrates model evaluation, feature importance analysis, and correlation analysis using the Titanic dataset.

## Author

Prachi Pingale

GitHub: [PPprachipingale2006](https://github.com/PPprachipingale2006)