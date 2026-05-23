# Weather Trend Forecasting and Climate Analysis

## PM Accelerator Mission
PM Accelerator empowers future AI professionals through hands-on product development and real-world AI collaboration.

---

# Project Overview

This project analyzes global weather data using data science and machine learning techniques. The goal is to forecast weather trends, uncover climate patterns, detect anomalies, and analyze environmental impacts using advanced exploratory data analysis and forecasting models.

The project was completed as part of the PM Accelerator AI Engineer Internship Technical Assessment.

---

# Dataset

Dataset Source:
https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code

Dataset Name:
Global Weather Repository

The dataset contains:
- 142,000+ weather records
- 40+ weather and environmental features
- Global city-level weather information

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

# Project Workflow

## 1. Data Cleaning & Preprocessing
- Removed duplicate records
- Converted datetime features
- Created time-series features
- Scaled numerical features

## 2. Exploratory Data Analysis (EDA)
- Temperature distribution analysis
- Precipitation analysis
- Correlation heatmap
- Country-wise climate analysis
- Environmental impact analysis

## 3. Forecasting Models
The following machine learning models were implemented:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Models were evaluated using:
- MAE
- RMSE
- R² Score

## 4. Advanced Analysis
- Feature Importance Analysis
- Anomaly Detection using Isolation Forest
- Spatial Weather Analysis
- Air Quality Impact Analysis

---

# Model Performance

| Model | R² Score |
|-------|-----------|
| Linear Regression | 0.978 |
| Random Forest | 0.996 |
| XGBoost | 0.996 |

Random Forest achieved the best forecasting performance.

---

# Key Insights

- Temperature showed strong correlation with feels_like_celsius and humidity.
- Random Forest achieved excellent prediction accuracy.
- Air quality indicators showed environmental relationships with weather conditions.
- Anomaly detection identified unusual weather observations.
- Spatial analysis revealed geographical weather variations globally.

---

# Project Structure

```text
weather-trend-forecasting/
│
├── data/
├── notebooks/
├── images/
├── README.md
├── requirements.txt
└── presentation.pdf
```

---

# Installation

Clone the repository:

```bash
git clone <your-github-repository-link>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

# Future Improvements

- Deep learning forecasting models
- Real-time weather prediction
- Interactive dashboard deployment
- Advanced time-series forecasting

---

# Author

Devangi Bhalala

BCA Graduate | Aspiring AI/ML Engineer & Data Scientist
