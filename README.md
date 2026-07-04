# Titanic Ensemble Learning

A machine learning project that predicts passenger survival on the Titanic dataset using Decision Trees and Ensemble Learning techniques. This project demonstrates data preprocessing, model training, and performance comparison between individual and ensemble-based classifiers.

## Project Overview

The goal of this project is to build and evaluate classification models for predicting Titanic passenger survival. The notebook explores how ensemble methods can improve prediction performance compared to a single Decision Tree.

## Dataset

The project uses the Titanic dataset, which contains passenger information such as:

* Passenger Class (Pclass)
* Sex
* Age
* Fare
* Embarked Port
* Survival Status

**Target Variable:** `Survived`

* 0 → Did Not Survive
* 1 → Survived

## Models Implemented

* Decision Tree Classifier
* Random Forest Classifier
* Bagging Classifier

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Feature Encoding
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Performance Comparison

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Repository Structure

```text
titanic-ensemble-learning/
├── Titanic_Ensemble_Learning.ipynb
├── README.md
└── .gitignore
```

## Key Learning Outcomes

* Understanding Decision Tree algorithms
* Implementing Bagging and Random Forest models
* Comparing ensemble methods with single estimators
* Evaluating classification model performance
* Building reproducible machine learning workflows



## Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/titanic-ensemble-learning.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Open the notebook and run all cells:

```bash
jupyter notebook Titanic_Ensemble_Learning.ipynb
```
