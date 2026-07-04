# Titanic Ensemble Learning

A machine learning project that predicts passenger survival on the Titanic dataset using Decision Trees and Ensemble Learning techniques. This project demonstrates data preprocessing, model training, and performance comparison between individual and ensemble-based classifiers.

## Project Overview

The objective of this project is to build classification models capable of predicting whether a passenger survived the Titanic disaster. The notebook explores how ensemble learning methods such as Random Forest and Bagging can improve predictive performance compared to a single Decision Tree model.

## Dataset

The project uses the Titanic dataset, which contains information about passengers, including:

* Passenger Class (Pclass)
* Sex
* Age
* Fare
* Embarked Port
* Family Information
* Survival Status

### Target Variable

**Survived**

* 0 = Did Not Survive
* 1 = Survived

## Models Implemented

* Decision Tree Classifier
* Bagging Classifier
* Random Forest Classifier

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Feature Encoding
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Performance Comparison

## Results

| Model | Accuracy |
|---------|---------|
| Decision Tree | 78.21% |
| Bagging Classifier | 81.56% |
| Random Forest | 83.24% |

### Key Findings

* Ensemble methods outperformed the standalone Decision Tree model.
* Random Forest provided more stable predictions by combining multiple decision trees.
* Bagging reduced model variance and improved generalization performance.
* Ensemble learning demonstrated its effectiveness in classification tasks.

> Replace the accuracy values above with the results from your notebook.

## Repository Structure

```text
titanic-ensemble-learning/
├── .gitignore
├── README.md
└── Titanic_Ensemble_Learning.ipynb
```

## Key Learning Outcomes

* Understanding Decision Tree algorithms
* Implementing ensemble learning techniques
* Comparing model performance using classification metrics
* Reducing overfitting through Bagging and Random Forest
* Building an end-to-end machine learning workflow


## Getting Started

Clone the repository:

```bash
git clone https://github.com/amaaan01/titanic-ensemble-learning.git
```

Navigate to the project directory:

```bash
cd titanic-ensemble-learning
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook Titanic_Ensemble_Learning.ipynb
```

## Conclusion

This project demonstrates how ensemble learning techniques can improve classification performance compared to a single Decision Tree. By leveraging multiple models, Random Forest and Bagging achieve better generalization and robustness, making them powerful tools for predictive machine learning tasks.
