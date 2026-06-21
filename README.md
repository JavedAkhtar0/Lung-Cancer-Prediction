# Lung Cancer Detection and Stage Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Healthcare-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)

## Overview

This project applies Machine Learning techniques to support lung cancer analysis through three predictive tasks:

1. Lung Cancer Detection
2. Cancer Stage Prediction
3. Cancer Risk Assessment

The project demonstrates the use of classification and regression algorithms to analyze healthcare-related datasets and generate predictive insights from patient information.

The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction.

---

## Project Preview

### Data Analysis

![EDA](screenshots/eda.png)

### Model Performance

![Model Performance](screenshots/model-performance.png)

### Prediction Results

![Prediction](screenshots/prediction-output.png)

---

## Key Features

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Healthcare data analysis
* Lung cancer detection
* Cancer stage prediction
* Risk assessment modeling
* Classification and regression techniques
* Model evaluation and comparison

---

## Datasets

### Lung Cancer Detection Dataset

* 309 patient records
* 16 clinical and demographic features
* Binary classification problem
* Target: Lung Cancer (Yes / No)

### Cancer Stage Prediction Dataset

* 53,000+ patient records
* Demographic and medical attributes
* Multi-class classification problem
* Target: Cancer Stage (Stage I, II, III, IV)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Workflow

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Prediction and Risk Assessment
8. Result Visualization

---

## Machine Learning Models

### Logistic Regression

Used for lung cancer detection and binary classification of patient records.

### Random Forest Classifier

Used for cancer stage prediction and multi-class classification.

### Linear Regression

Used for risk assessment and prediction of continuous cancer-related outcomes.

---

## Evaluation Metrics

The classification models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The regression model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Repository Structure

```text
Lung-Cancer-Prediction
│
├── data/
├── notebooks/
├── screenshots/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/JavedAkhtar0/Lung-Cancer-Prediction.git
cd Lung-Cancer-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and run the cells sequentially.

---

## Results

The project demonstrates how machine learning techniques can be applied to healthcare datasets for predictive analysis.

The classification models successfully identify lung cancer cases and predict cancer stages, while the regression model provides insights into cancer-related risk assessment. The results highlight the potential of machine learning for supporting data-driven healthcare decision-making.

---

## Future Improvements

* XGBoost Integration
* Hyperparameter Optimization
* Deep Learning Models
* Explainable AI (XAI)
* Interactive Dashboard
* FastAPI Deployment
* Real-Time Prediction System

---

## Author

Javed Akhtar

MCA Student | Machine Learning & Python Enthusiast

GitHub Profile: [JavedAkhtar0](https://github.com/JavedAkhtar0)

Project Repository: [Lung-Cancer-Prediction](https://github.com/JavedAkhtar0/Lung-Cancer-Prediction)
---

## Disclaimer

This project was developed for educational and research purposes. It is not intended to replace professional medical diagnosis, treatment, or healthcare advice.
