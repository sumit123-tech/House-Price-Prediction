# House Price Prediction

## Project Overview

This project aims to predict house prices using machine learning techniques based on various property features such as area, number of bedrooms, bathrooms, stories, parking availability, air conditioning, and furnishing status.

The project was completed as part of the **XYlofy AI – AI & Data Science Internship (Week 1 Assignment)**.

---

## Dataset

Dataset Source:
https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

Dataset Size:

* Rows: 545
* Columns: 13

Target Variable:

* Price

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Exploration

* Loaded dataset using Pandas
* Checked dataset structure
* Verified missing values
* Identified target and feature columns

### 2. Data Preprocessing

* Checked duplicate records
* Applied One-Hot Encoding to categorical variables
* Prepared data for machine learning models

### 3. Model Building

Two regression models were trained:

* Linear Regression
* Random Forest Regressor

Dataset Split:

* Training Data: 80%
* Testing Data: 20%

---

## Model Performance

| Model                   | R² Score |
| ----------------------- | -------- |
| Linear Regression       | 0.653    |
| Random Forest Regressor | 0.612    |

Best Performing Model:
**Linear Regression**

---

## Key Findings

The most influential features affecting house prices were:

1. Area
2. Bathrooms
3. Air Conditioning
4. Parking
5. Stories
6. Bedrooms

The analysis shows that larger houses with better facilities generally have higher market values.

---

## Visualizations

The project includes:

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot
* Feature Importance Chart

---

## Repository Structure

```text
House-Price-Prediction
│
├── analysis.ipynb
├── Housing.csv
├── Summary.pdf
├── actual_vs_predicted.png
├── correlation_heatmap.png
├── feature_importance.png
└── price_distribution.png
```

---

## Author

**Sumit Banerjee**

B.Tech (Computer Science & Engineering)

Asansol Engineering College

AI & Data Science Intern – XYlofy AI
