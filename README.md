# Medical Insurance Cost Prediction

## Overview

Medical Insurance Cost Prediction is a Machine Learning Regression project that predicts a person's medical insurance charges based on health and demographic information such as age, BMI, smoking habits, region, and number of children.

This project demonstrates the complete machine learning workflow including data preprocessing, exploratory data analysis, feature encoding, model training, evaluation, and prediction.

---

# Problem Statement

Insurance companies calculate medical insurance premiums based on several health-related factors.

The goal of this project is to build a Machine Learning model that can accurately predict insurance costs using patient information.

---

# Project Objectives

- Analyze insurance dataset
- Perform data preprocessing
- Handle categorical variables
- Train regression models
- Evaluate model performance
- Predict medical insurance charges
- Understand feature importance

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Dataset Features

| Feature | Description |
|---|---|
| age | Age of the person |
| sex | Gender |
| bmi | Body Mass Index |
| children | Number of children |
| smoker | Smoking habit |
| region | Residential region |
| charges | Medical insurance cost |

---

# Project Workflow

Dataset Collection  
↓  
Data Cleaning  
↓  
Exploratory Data Analysis  
↓  
Feature Encoding  
↓  
Train-Test Split  
↓  
Feature Scaling  
↓  
Model Training  
↓  
Prediction  
↓  
Model Evaluation  

---

# Exploratory Data Analysis (EDA)

EDA is performed to:

- Understand data distribution
- Detect outliers
- Find relationships between variables
- Identify important features

Visualizations used:

- Histograms
- Countplots
- Heatmaps
- Pairplots
- Correlation Matrix

---

# Feature Encoding

Categorical columns such as:

- sex
- smoker
- region

are converted into numerical values using:

- Label Encoding
- One Hot Encoding

---

# Regression Models Used

- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/Prathyun01/Medical-Insurance-Cost-Prediction.git
```

## Move into Project Directory

```bash
cd Medical-Insurance-Cost-Prediction
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run the Project

```bash
jupyter notebook
```

Open:

```text
Medical Insurance Cost Prediction.ipynb
```

---

# Output

The project predicts medical insurance charges based on user information.

---

# Future Improvements

- Deploy using Streamlit or Flask
- Improve model accuracy
- Add real-time prediction system

---

# Author

Prathyun Reddy

GitHub: https://github.com/Prathyun01

---

# License

This project is licensed under the MIT License.
