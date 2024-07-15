# Diabetes Prediction

This repository contains a Jupyter Notebook designed to predict diabetes in patients using various machine learning models. The notebook covers data loading, exploratory data analysis, preprocessing, feature extraction, and model evaluation.

## Dataset

The dataset used in this notebook is related to diabetes and includes various medical predictor variables and one target variable, `Outcome`, indicating whether a patient has diabetes (1) or not (0).

## Steps Covered in the Notebook

1. ## Loading the Dataset
   - The dataset is loaded into a pandas DataFrame for analysis.

2. ## Exploratory Data Analysis (EDA)
   - Descriptive statistics and dataset information
   - Checking for missing values
   - Plotting histograms for data distribution
   - Generating a correlation matrix
   - Visualizing data distribution of diabetic and non-diabetic patients
   - Pair plots to observe relationships between features

3. ## Outliers Detection and Removal
   - Box plots are used to detect outliers in the dataset.
   - Outliers are removed to improve model accuracy and learning.

4. ## Feature Extraction
   - Features (`X`) and target (`y`) variables are extracted from the cleaned dataset.

5. ## Splitting Data
   - The dataset is split into training and testing sets in an 80-20 ratio.

6. ## Model Training and Evaluation
   - Random Forest
   - Decision Tree

   For each model, the following steps are performed:
   - Initialization and fitting the model on training data
   - Predicting outcomes on test data
   - Evaluating model performance using accuracy, classification report.
