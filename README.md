# Aerospace Alloy Strength Prediction using Machine Learning

## Overview

This project applies Machine Learning and Materials Informatics techniques to predict the tensile strength of aerospace aluminum alloys based on alloy composition and heat-treatment parameters.

The objective is to demonstrate how data-driven approaches can assist material design and optimization while reducing the time and cost associated with traditional experimental testing.

---

## Problem Statement

The aerospace industry requires lightweight materials with high strength and durability. Predicting material performance using conventional experimentation can be expensive and time-consuming.

This project uses Linear Regression to predict tensile strength from alloy composition and processing conditions.

---

## Dataset Features

### Input Features

* Magnesium (Mg)
* Copper (Cu)
* Zinc (Zn)
* Heat Treatment Temperature (°C)
* Aging Time (Hours)

### Target Variable

* Tensile Strength (MPa)

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

---

## Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Train-Test Split
5. Linear Regression Model Training
6. Model Evaluation
7. Prediction and Optimization

---

## Model Performance

| Metric   | Value     |
| -------- | --------- |
| R² Score | 0.958     |
| RMSE     | 4.658 MPa |

The model achieved high prediction accuracy and demonstrated strong correlation between predicted and actual tensile strength values.

---

## Results

The trained model successfully predicted the tensile strength of aerospace aluminum alloys using alloy composition and heat-treatment parameters.

The project also explored optimized alloy compositions for improved material performance.

---

## Repository Structure

```text
Aerospace-Alloy-Strength-Prediction
│
├── README.md
├── Aerospace_Materials_Informatics_Project.ipynb
├── Final_Aerospace_Materials_Report.pdf
└── dataset/
    └── aerospace_alloy_dataset.csv
```

---

## Future Improvements

* Increase dataset size
* Compare multiple machine learning algorithms
* Implement Random Forest Regression
* Apply Support Vector Regression (SVR)
* Explore Deep Learning approaches
* Perform experimental validation

---

## Author

**Venkat Jyoshit Potnuru**

B.Tech – Artificial Intelligence and Data Science

Amrita Vishwa Vidyapeetham
