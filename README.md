# Data Science Projects

A collection of end-to-end Data Science and Machine Learning projects built in **Python** using **Google Colab**. These projects cover supervised classification, exploratory data analysis (EDA), data visualization, and regression modeling.

---

## Table of Contents
- [Projects Overview](#projects-overview)
  - [1. Iris Flower Classification](#1-iris-flower-classification)
  - [2. Unemployment Analysis](#2-unemployment-analysis)
  - [3. Sales Prediction](#3-sales-prediction)
- [Tech Stack & Libraries](#tech-stack--libraries)
- [How to Run](#how-to-run)
- [Author](#author)

---

## Projects Overview

| # | Project | Type | Key Focus |
|---|---------|------|-----------|
| 1 | Iris Flower Classification | Supervised Learning (Classification) | Multi-class species prediction |
| 2 | Unemployment Analysis | Exploratory Data Analysis (EDA) | Trend & regional data visualization |
| 3 | Sales Prediction | Supervised Learning (Regression) | Forecasting sales from ad spend |

---

### 1. Iris Flower Classification
- **Notebook:** `PROJECT_1_Iris_Flower_Classification.ipynb`
- **Objective:** Train a machine learning model to classify Iris flowers into three species—*Iris Setosa*, *Iris Versicolor*, and *Iris Virginica*—using sepal length, sepal width, petal length, and petal width.
- **Workflow:**
  1. **Data Loading & Inspection:** Loaded the Iris dataset and checked data types, summary statistics, and class distribution.
  2. **Exploratory Data Analysis (EDA):** Visualized feature relationships and species separation using pairplots, histograms, and correlation heatmaps.
  3. **Data Preprocessing:** Split the dataset into training and testing sets and prepared features for modeling.
  4. **Model Training & Evaluation:** Trained classification algorithms and evaluated performance using accuracy score, confusion matrix, and classification report.

---

### 2. Unemployment Analysis
- **Objective:** Analyze unemployment rate data to uncover trends, seasonal shifts, and regional variations over time.
- **Workflow:**
  1. **Data Cleaning:** Inspected the dataset for missing values, duplicate entries, and inconsistent column formatting.
  2. **Statistical Summary:** Computed descriptive statistics across regions, states, and time periods.
  3. **Data Visualization:** Created line charts, bar plots, heatmaps, and distribution plots to highlight peak unemployment periods and regional disparities.
  4. **Insights:** Summarized key patterns and socioeconomic takeaways observed from the visual analysis.

---

### 3. Sales Prediction
- **Objective:** Build a predictive regression model to estimate product sales based on advertising budgets across different media channels.
- **Workflow:**
  1. **Data Exploration:** Examined relationships between advertising spend and sales revenue using scatter plots and correlation matrices.
  2. **Feature Selection & Splitting:** Selected predictor variables and divided the data into training and test subsets.
  3. **Model Training:** Fitted regression models to learn the relationship between marketing spend and total sales.
  4. **Evaluation:** Measured prediction quality using regression metrics (such as $R^2$ score, MAE, and RMSE) and plotted actual vs. predicted values.

---

## Tech Stack & Libraries
- **Language:** Python 3
- **Environment:** Google Colab / Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn

---

## How to Run

### Option 1: Open in Google Colab (Recommended)
1. Click any `.ipynb` file in this repository.
2. Click the **Open in Colab** badge/link at the top of the notebook.
3. Run the cells sequentially (`Runtime` → `Run all`).

### Option 2: Run Locally
```bash
git clone [https://github.com/Amanpreet0320/Data-Science-Projects.git](https://github.com/Amanpreet0320/Data-Science-Projects.git)
cd Data-Science-Projects
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
