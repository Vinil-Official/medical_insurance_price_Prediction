
# Medical Insurance Price Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

Predict the cost of medical insurance for individuals using **Linear Regression**. This project estimates insurance premiums based on personal and health-related features.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Algorithm](#algorithm)
- [Model Performance](#model-performance)
- [Installation](#installation)
- [Usage](#usage)
- [Future Improvements](#future-improvements)
- [Author](#author)
- [License](#license)

---

## Project Overview
Medical insurance costs depend on multiple factors such as age, BMI, lifestyle, and number of dependents. This project uses **Linear Regression** to predict insurance charges with an accuracy of **85%**.

---

## Dataset
The dataset includes the following features:

| Feature   | Description                              |
|-----------|------------------------------------------|
| age       | Age of the individual                     |
| sex       | Gender (male/female)                      |
| bmi       | Body Mass Index (weight/height²)         |
| children  | Number of children covered by insurance  |
| smoker    | Smoking status (yes/no)                  |
| region    | Residential area in the US               |
| charges   | Medical insurance cost (target variable) |

**Source:** [Medical Cost Personal Dataset on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)

---

## Features
- Age  
- Sex  
- BMI  
- Number of children  
- Smoking status  
- Region  

---

## Algorithm
**Linear Regression** predicts the insurance cost based on input features.  

**Why Linear Regression?**
- Simple and interpretable  
- Efficient for small-to-medium datasets  
- Works well with linearly correlated data  

---

## Model Performance
- **Accuracy (R² Score): 85%**  
- Suitable for predicting insurance costs for most cases.  
- Extreme values (outliers) may affect accuracy.  

---

## Installation
1. Clone the repository:
```bash
git clone <repository-url>
