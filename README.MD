# Mental Health Prediction - Extract Useful Insight from Data

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## 📋 Overview

This project analyzes mental health data to predict history of mental illness using demographic and lifestyle factors. The analysis includes comprehensive exploratory data analysis (EDA), feature engineering, and machine learning modeling using Random Forest classifier.

The dataset contains information about individuals including age, marital status, education level, number of children, smoking status, physical activity, employment status, income, alcohol consumption, dietary habits, sleep patterns, and various health history factors.

## 🎯 Objectives

- Perform comprehensive exploratory data analysis on mental health dataset
- Extract meaningful insights about factors affecting mental health
- Build a predictive model to identify individuals at risk of mental illness
- Analyze correlations between lifestyle factors and mental health outcomes

## 📊 Dataset Features

The dataset includes the following features:
- **Demographics**: Age, Marital Status, Education Level, Number of Children
- **Lifestyle**: Smoking Status, Physical Activity Level, Employment Status, Income
- **Health Behaviors**: Alcohol Consumption, Dietary Habits, Sleep Patterns
- **Medical History**: History of Mental Illness (target variable), History of Substance Abuse, Family History of Depression, Chronic Medical Conditions

## 🛠️ Technical Stack

- **Python 3.8+**
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn (Random Forest Classifier)
- **Environment**: Google Colab / Jupyter Notebook

## 📈 Key Insights from EDA

1. **Demographic Factors**: Age distribution shows significant variation across different demographics
2. **Lifestyle Correlations**: Physical activity level, sleep patterns, and dietary habits show correlation with mental health
3. **Family History**: Strong indicator for personal history of mental illness
4. **Income Patterns**: Income distribution varies across different categories
5. **Categorical Feature Analysis**: Various lifestyle factors show different distributions between those with and without mental illness history

## 🤖 Machine Learning Model

A Random Forest Classifier was implemented with the following characteristics:

- **Features**: 15 total features (3 numerical, 12 categorical)
- **Preprocessing**: StandardScaler for numerical features, OneHotEncoder for categorical features
- **Target**: History of Mental Illness (binary: Yes/No)

## 📁 Project Structure
