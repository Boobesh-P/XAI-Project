# XAI-Project
Explainable AI based diabetic retinopathy detection using SHAP and LIMEf

# Explainable AI Based Diabetic Retinopathy Detection using SHAP and LIME
## Project Overview

Diabetic Retinopathy is a retinal complication caused by diabetes that can lead to vision impairment if not detected early.
This project develops a machine learning based classification system for diabetic retinopathy detection using retinal clinical features and integrates Explainable AI techniques to interpret model decisions.
The objective is to build a predictive model and understand the reasoning behind individual predictions using SHAP and LIME.

## Technologies Used

* Python
* Google Colab
* Scikit-Learn
* Random Forest Classifier
* SHAP
* LIME
* Pandas
* Matplotlib
* Seaborn

## Dataset

Dataset:
Diabetic Retinopathy Debrecen Dataset

Source:
UCI Machine Learning Repository

Dataset Characteristics:
* Samples: 1151
* Features: 19 retinal related attributes
* Task: Binary Classification

Classes:

| Label | Meaning                 |
| ----- | ----------------------- |
| 0     | No Diabetic Retinopathy |
| 1     | Diabetic Retinopathy    |

# Methodology

## 1. Data Preprocessing

* Dataset loading
* Missing value handling
* Feature-target separation
* Train-test split

## 2. Machine Learning Model

A Random Forest Classifier is used for prediction.

Parameters:

Number of Trees: 150
Split Ratio: 80%-20%
Random State: 42

# Explainable AI

## SHAP Analysis

SHAP explains the contribution of every feature towards model prediction.

Implemented:

* Global feature importance
* SHAP summary plot
* Local prediction explanation
* Feature contribution analysis

Example output:

## LIME Analysis

LIME explains individual predictions by approximating the model locally.

Implemented:

* Instance level explanation
* Positive and negative feature contribution

Example output:

# Results

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score

The explainability analysis identifies important retinal characteristics influencing diabetic retinopathy prediction.

# Project Structure

Diabetic-Retinopathy-XAI

│
├── Diabetic_Retinopathy_SHAP_LIME.ipynb
├── README.md
├── requirements.txt
│
└── results
    ├── shap_summary_plot.png
    ├── shap_feature_importance.png
    └── lime_explanation.png

# How to Run

Clone repository:

```bash
git clone https://github.com/yourusername/Diabetic-Retinopathy-XAI.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook


# Future Improvements

* Apply deep learning models on retinal images
* Integrate Grad-CAM visualization
* Deploy as a web application
* Improve prediction performance using ensemble methods

#

Machine Learning | Explainable AI Project
