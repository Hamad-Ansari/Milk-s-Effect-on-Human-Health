# 🥛 Milk's Effect on Human Health - Advanced Data Analysis

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Dataset Description](#-dataset-description)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Methodology](#-methodology)
- [Results](#-results)
- [Model Performance](#-model-performance)
- [Key Insights](#-key-insights)
- [Visualizations](#-visualizations)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Future Work](#-future-work)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 Project Overview

This project presents a **comprehensive machine learning analysis** exploring the relationship between milk consumption and human health outcomes. Using a synthetic dataset of **10,000 records**, we developed predictive models to understand factors influencing doctor recommendations regarding milk intake.

The analysis employs **state-of-the-art ML techniques**, hyperparameter optimization, and advanced visualization to deliver actionable health insights and build a robust classification system.

> **Objective**: Predict doctor recommendations (Maintain/Increase/Reduce intake) based on demographic, health, and lifestyle factors.

---

## 📊 Dataset Description

| Attribute | Details |
|-----------|---------|
| **Source** | Synthetic Health Dataset |
| **Records** | 10,000 |
| **Features** | 17 (Mixed: Numerical & Categorical) |
| **Target Variable** | `Doctor_Recommendation` (3 classes) |
| **Missing Values** | None |
| **Duplicates** | None |

### Target Variable Distribution

- 🟢 **Maintain Intake**: ~79.8%
- 🟡 **Increase Intake**: ~20.0%
- 🔴 **Reduce Intake**: ~0.2%

### Key Features

| Feature | Type | Description |
|---------|------|-------------|
| `Age` | Numerical | Patient age |
| `Gender` | Categorical | Male/Female |
| `Country` | Categorical | 6 countries (USA, UK, India, Australia, Pakistan, Canada) |
| `Milk_Type` | Categorical | Type of milk consumed |
| `Lactose_Intolerant` | Binary | Yes/No |
| `Digestive_Issues` | Binary | Presence of digestive problems |
| `Physical_Activity_Level` | Ordinal | Activity intensity |
| `Allergy_Reaction` | Categorical | Allergy response type |

---

## ✨ Features

### 🔬 **Exploratory Data Analysis (EDA)**
- Comprehensive univariate and bivariate analysis
- Correlation heatmaps with custom color schemes
- Distribution plots for all features
- Missing value and outlier detection

### 📊 **Power BI-Style Interactive Dashboard**
- Executive KPI cards
- Multi-panel Plotly visualizations
- Sunburst and Treemap hierarchical views
- Real-time interactive filtering

### 🤖 **Machine Learning Pipeline**
- **4 Advanced Models**:
  - Logistic Regression (with regularization)
  - Random Forest Classifier
  - XGBoost Classifier
  - LightGBM Classifier

- **Hyperparameter Tuning**:
  - GridSearchCV
  - RandomizedSearchCV
  - Optuna Bayesian Optimization

### 📈 **Model Evaluation**
- Beautiful ROC Curves (Multi-class)
- Styled Confusion Matrices with percentages
- Comprehensive Classification Reports
- Precision-Recall analysis

### 🧠 **Model Explainability**
- SHAP (SHapley Additive exPlanations) values
- Feature importance analysis across models
- Individual prediction explanations

### 🎨 **Custom Design System**
- Professional color theme: `#3d5c3d`, `#046105`, `#3b473b`
- HTML-styled sections and info cards
- Publication-ready visualizations
- Kaggle-friendly notebook structure

---

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- Jupyter Notebook / JupyterLab
- Git

### Clone Repository

```bash
git clone https://github.com/yourusername/milk-health-analysis.git
cd milk-health-analysis
