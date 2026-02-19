# 🥛 Milk's Effect on Human Health - Advanced Data Analysis
<div style="background: linear-gradient(135deg, #3d5c3d 0%, #046105 50%, #3b473b 100%); 
            padding: 40px; 
            border-radius: 20px; 
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);">
    
<h1 style="color: white; font-size: 42px; margin-bottom: 10px;">
    🥛 Milk's Effect on Human Health
</h1>

<h3 style="color: #c8e6c9; font-size: 20px;">
    Advanced Machine Learning Analysis & Predictive Modeling
</h3>

<hr style="border: 1px solid #a5d6a7; width: 60%; margin: 20px auto;">

<p style="color: white; font-size: 16px;">
    📊 10,000+ Records | 🤖 4+ ML Models | 🎯 Hyperparameter Tuning | 📈 Interactive Dashboards
</p>

</div>
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
```
<img width="2380" height="731" alt="data_quality" src="https://github.com/user-attachments/assets/9bedeae9-d2b8-41f4-9172-3c16d9e9b55a" />
<img width="3199" height="2375" alt="model_comparison" src="https://github.com/user-attachments/assets/d1678805-626d-49b9-8b74-dd848541e00c" />
<img width="1400" height="1200" alt="newplot" src="https://github.com/user-attachments/assets/888d5b9a-1f9f-4ba2-be47-c4447b5d785c" />


<div style="background: linear-gradient(135deg, #3d5c3d 0%, #046105 50%, #3b473b 100%); 
            padding: 40px; 
            border-radius: 20px; 
            text-align: center;
            color: white;
            margin-top: 40px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);">

<h1 style="margin: 0; font-size: 36px;">🙏 Thank You for Reading!</h1>

<p style="font-size: 18px; margin: 20px 0; color: #c8e6c9;">
    If you found this notebook helpful, please consider:
</p>

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 25px 0;">
    <div style="background: rgba(255,255,255,0.2); padding: 15px 25px; border-radius: 30px;">
        ⭐ <b>Upvote this Notebook</b>
    </div>
    <div style="background: rgba(255,255,255,0.2); padding: 15px 25px; border-radius: 30px;">
        💬 <b>Leave a Comment</b>
    </div>
    <div style="background: rgba(255,255,255,0.2); padding: 15px 25px; border-radius: 30px;">
        🔔 <b>Follow for More</b>
    </div>
</div>

<hr style="border: 1px solid rgba(255,255,255,0.3); margin: 30px 0;">

<h2 style="color: #c8e6c9; margin-bottom: 20px;">👨‍💻 About the Author</h2>

<p style="font-size: 16px; line-height: 1.8; max-width: 600px; margin: 0 auto;">
    I am a passionate <b>Data Scientist & Machine Learning Engineer</b> with expertise in 
    predictive modeling, deep learning, and data visualization. I love solving real-world 
    problems with data and sharing knowledge with the community.
</p>

<div style="margin-top: 30px;">
    <a href="https://kaggle.com/hammadansari7" style="background: white; color: #3d5c3d; 
       padding: 12px 25px; border-radius: 25px; text-decoration: none; margin: 5px;
       display: inline-block; font-weight: bold;">
       🏆 Kaggle Profile</a>
    <a href="https://linkedin.com/in/hammad-zahid-xyz" style="background: white; color: #046105; 
       padding: 12px 25px; border-radius: 25px; text-decoration: none; margin: 5px;
       display: inline-block; font-weight: bold;">
       💼 LinkedIn</a>
    <a href="https://github.com/Hamad-Ansari" style="background: white; color: #3b473b; 
       padding: 12px 25px; border-radius: 25px; text-decoration: none; margin: 5px;
       display: inline-block; font-weight: bold;">
       🐙 GitHub</a>
    <a href="https://twitter.com/zahid_hamm57652" style="background: white; color: #3d5c3d; 
       padding: 12px 25px; border-radius: 25px; text-decoration: none; margin: 5px;
       display: inline-block; font-weight: bold;">
       🐦 Twitter</a>
</div>

<p style="margin-top: 30px; font-size: 14px; opacity: 0.8;">
    © 2026 | Made with Hammad ❤️ and Python
</p>

</div>
