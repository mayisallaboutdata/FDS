# Spaceship Titanic: Binary Classification

## Overview

This repository contains the final project for the Fundamentals of Data Science course at Sapienza University of Rome. In this project, we tackle a futuristic binary classification problem using the "Spaceship Titanic" dataset. Our goal is to predict which passengers were transported to an alternate dimension following a catastrophic collision with a spacetime anomaly.

## Project Description

Set in the year 2912, the Spaceship Titanic dataset presents a unique challenge: some passengers vanish into an alternate dimension during a space disaster. The dataset features numerous missing values and complex relationships among 14 passenger-related features. Our analysis covers every step of the data pipeline—from exploratory data analysis (EDA) and feature engineering to model selection and evaluation. We employ multiple machine learning models, including Random Forest, Gradient Boosting, Neural Networks, and a Stacked model, to understand and optimize predictive performance.

## Contents

- **Dataset**  
  - `train.csv`: Training dataset (8693 x 14)  
  - `test.csv`: Testing dataset (4277 x 13)

- **Presentations & Reports**  
  - Final project report detailing methodology, experiments, and results  
  - Supplementary presentations and documentation (if applicable)

- **Notebooks & Code**  
  - Jupyter notebooks containing EDA, preprocessing, model training, and evaluation scripts

## Methodology

### Data Processing
- **Exploratory Data Analysis (EDA):**  
  We start by understanding the dataset’s distribution, identifying missing values, and exploring correlations between features.

- **Feature Engineering:**  
  Critical features are generated through careful preprocessing, including handling missing data, scaling, and dimensionality reduction techniques to focus on the most relevant information.

### Model Selection & Evaluation
- **Models Explored:**  
  - **Random Forest**  
  - **Gradient Boosting**  
  - **Neural Network**  
  - **Stacked Model** (an ensemble combining multiple algorithms)

- **Hyperparameter Tuning:**  
  Each model undergoes tuning to optimize performance metrics such as accuracy, recall, F1-score, and ROC AUC.

- **Observations:**  
  - Neural networks exhibited the highest precision.
  - Gradient Boosting achieved the best ROC AUC.
  - The Stacked model delivered superior accuracy, recall, and F1-score.
  - Our experiments revealed that aggressive feature engineering or excessive missing value correction can sometimes diminish performance by removing useful signal.

## Results

Our findings underscore the importance of balancing data preprocessing with model complexity. While more sophisticated feature engineering can sometimes hurt performance, a minimal yet thoughtful approach may lead to more robust models. The differences in model performance also highlight how various algorithms prioritize features differently.

## Conclusion and Future Work

The project demonstrates a nuanced landscape where each model brings its strengths:
- **Key Insights:**  
  - The choice of data preprocessing techniques significantly affects model outcomes.
  - Different models excel in various performance aspects, emphasizing the need for a balanced approach.

- **Future Directions:**  
  - Further exploration of advanced missing data imputation methods.
  - Investigation into ensemble techniques to synergize the strengths of different models.
  - Continuous refinement of feature selection and hyperparameter tuning to push the limits of prediction accuracy and reliability.

## Authors

- **Ambar Chatterjee**
- **Himel Ghosh**
- **Paul Jèzèquel**
- **Mayis Atayev**

## References

1. Samuel Cortinhas, "Spaceship Titanic: A Complete Guide", Kaggle Code Repository.
2. KD Sharma, "Spaceship Titanic Competition: End-to-End Project", Kaggle Code Repository.
3. Gusthema, "Spaceship Titanic with TF-DF", Kaggle Code Repository.
