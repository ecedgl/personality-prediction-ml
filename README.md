# Personality Prediction (Introvert vs Extrovert):

A machine learning project to classify individuals as introverts or extroverts based on social behavior traits using logistic regression.

## Overview:

- Dataset: 2900 entries, 8 features
- Target: Personality (Introvert / Extrovert)
- Goal: Building a binary classification model

## Tools:

- Python 
- Pandas, NumPy
- scikit-learn
- Seaborn, Matplotlib

## Process Summary:

1. CSV file downloaded from Kaggle and used directly in the project
2. Missing values handled manually
3. Categorical encoding applied
4. Data split (%80 train, %20 test)
5. Logistic Regression model trained
6. Accuracy: 92.4%
7. Visualized results

## Project Structure:

- `personality_prediction_ml.ipynb`: main notebook
- `data/personality_dataset.csv`: dataset
- `visual/`: generated graphs
- `requirements.txt`: used packages

## Running the Project:

Open the notebook in Colab, make sure `data/personality_dataset.csv` is present, and run the cells in order.

## Notes:

This project was built for learning purposes with a focus on clear structure, readable code and straightforward model interpretation.