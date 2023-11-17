# Prediction-of-fake-news-ML
 This project aims to identify and classify fake news articles using various machine learning algorithms. The code utilizes Python and several libraries for data manipulation, model training and evaluation. It aims in comparing 4 different ML models.

## Technologies Used
***Python***: Programming language used for data processing, analysis, and model implementation.
***Pandas***: For data manipulation and handling.
***NumPy***: Used for numerical computations.
***Seaborn and Matplotlib***: Libraries for data visualization.
***Scikit-learn (sklearn)***: Utilized for machine learning model implementation and evaluation.

## Overview
The code includes the following major steps:

## Data Loading and Preprocessing:
1. Loads two datasets (Fake.csv and True.csv) containing fake and true news articles.
2. Combines and preprocesses the data, including creating a 'class' column to differentiate fake (0) and true (1) news articles.
3. Removes unnecessary columns like "title," "subject," and "date."

## Text Preprocessing:
1. Converts text to lowercase, removes special characters, URLs, punctuation, and numbers.
2. Randomly shuffles the data for better training and testing.

## Feature Engineering:
1. Splits the dataset into independent (text) and dependent (class) variables.
2. Splits the data into training and testing sets.

## Text Vectorization:
1. Utilizes TF-IDF vectorization to convert text data into numerical vectors for model training.

## Model Building and Evaluation:
Implements and evaluates various classification models:
1. Logistic Regression
2. Decision Tree Classifier
3. Gradient Boosting Classifier
4. Random Forest Classifier
Generates classification reports and evaluates accuracy for each model.

## Manual Testing:
Provides functionality for manual entry of news text for testing against the trained models.

## Usage
Ensure Python and necessary libraries are installed.
Run the code in a Python environment.
Customize text preprocessing or model parameters as needed.
Use manual testing to input news text and evaluate against the trained models.

## Notes
Experiment with different machine learning algorithms or hyperparameters for better model performance.
Consider adding additional text preprocessing or feature engineering techniques for improved results.
Validate the models with a broader dataset for more robust evaluation.
