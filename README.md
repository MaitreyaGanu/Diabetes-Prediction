# Diabetes Prediction using K-Nearest Neighbors (KNN)

This project focuses on predicting diabetes using the Pima Indian Diabetes Database. The **K-Nearest Neighbors (KNN)** algorithm was employed, achieving an accuracy of **80.5%**. The dataset was split with **80% for training** and **20% for testing**, in line with the Pareto principle for effective model evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Results](#results)


---

## Introduction

Diabetes is a growing health concern worldwide. Early prediction based on health metrics can aid in timely intervention and treatment. This project uses the **KNN algorithm** to classify individuals as diabetic or non-diabetic based on the Pima Indian Diabetes dataset.

---

## Dataset

- **Source**: The Pima Indian Diabetes Database, widely used for diabetes prediction tasks.
- **Description**: The dataset contains several health indicators such as glucose levels, BMI, age, and more.
- **Target Variable**: A binary variable indicating the presence or absence of diabetes.

---

## Features

- **Data Exploration**: Perform exploratory data analysis (EDA) to understand feature importance and relationships.
- **Data Preprocessing**: Normalize features, handle missing values, and split the data (80% training, 20% testing).
- **K-Nearest Neighbors Algorithm**: Train the KNN model to classify diabetes status.
- **Model Evaluation**: Assess performance using accuracy, precision, recall, and F1-score.

---

## Technologies Used

- **Python**: Programming language for data processing and model implementation.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib/Seaborn**: For visualizing data and evaluation results.
- **Scikit-learn**: For implementing the KNN algorithm and model evaluation.
- **NumPy**: For numerical computations.

---

## Results

The model was evaluated using **Scikit-learn**, with the following metrics:  

### Evaluation Metrics:
| Class            | Precision | Recall | F1-Score | Support |
|-------------------|-----------|--------|----------|---------|
| **Non-Diabetic (0)** | 0.85      | 0.88   | 0.86     | 107     |
| **Diabetic (1)**     | 0.70      | 0.64   | 0.67     | 47      |

| **Overall Metrics** |               |        |          |         |
|----------------------|---------------|--------|----------|---------|
| **Accuracy**         |               | 0.81   |          | 154     |
| **Macro Avg**        | 0.77          | 0.76   | 0.76     |         |
| **Weighted Avg**     | 0.80          | 0.81   | 0.80     |         |

The **confusion matrix** provides a visual summary of the classification results:

| Predicted/Actual | Non-Diabetic (0) | Diabetic (1) |
|-------------------|------------------|--------------|
| **Non-Diabetic (0)** | 94               | 13           |
| **Diabetic (1)**     | 17               | 40           |

The model demonstrates strong performance in identifying non-diabetic individuals, with room for improvement in diabetic classifications.
