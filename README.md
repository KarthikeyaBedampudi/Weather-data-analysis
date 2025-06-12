# 🌦️ Weather Data Analysis and Rainfall Prediction

This project explores a real-world weather dataset to analyze patterns, visualize insights, and predict rainfall using linear regression.

## 📁 Dataset Columns

The dataset includes daily weather observations with the following columns:

```
['MinTemp', 'MaxTemp', 'Rainfall', 'Evaporation', 'Sunshine',
 'WindGustDir', 'WindGustSpeed', 'WindDir9am', 'WindDir3pm',
 'WindSpeed9am', 'WindSpeed3pm', 'Humidity9am', 'Humidity3pm',
 'Pressure9am', 'Pressure3pm', 'Cloud9am', 'Cloud3pm', 'Temp9am',
 'Temp3pm', 'RainToday', 'RISK_MM', 'RainTomorrow']
```

> **Target Variable**: `Rainfall` (for regression)
> *Optional:* `RainTomorrow` (for classification)

---

## 📊 Project Workflow

### 1. **Data Loading and Exploration**

* Read the CSV dataset using pandas
* Inspect data types, summary statistics, and missing values

### 2. **Data Cleaning**

* Handle missing values in key features (`MinTemp`, `MaxTemp`, `Rainfall`)
* Focus only on relevant numeric columns for regression

### 3. **Data Visualization**

* Pair plots for feature relationships
* Correlation heatmap
* Histogram of rainfall distribution

### 4. **Linear Regression**

* Model: Predict `Rainfall` based on `MinTemp` and `MaxTemp`
* Evaluated using Mean Squared Error (MSE)

### 5. **Insights**

* Basic analysis of rainfall and temperature patterns
* Provides a foundation for further feature engineering and model development

---

## ⚙️ Requirements

* Python 3.x
* pandas
* matplotlib
* seaborn
* scikit-learn

Install dependencies:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

---
