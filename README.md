# 🏡 California Housing Regression Model Comparison

This project demonstrates the application and comparison of **eight regression algorithms** on the **California Housing dataset**, using Python and the `scikit-learn` library. The goal is to evaluate each model's performance using key regression metrics and visualize the results.

---

## 📘 What is Regression?
Regression is a type of supervised machine learning technique used to predict continuous numerical values based on one or more input features. It helps identify and quantify the relationship between variables, making it a fundamental tool in data analysis and predictive modeling.


### 🧭 Supervised vs Unsupervised Learning
Supervised Learning involves training a model on a labeled dataset—i.e., the input data is paired with the correct output.

Regression and Classification are two main types of supervised learning.

Unsupervised Learning, on the other hand, deals with unlabeled data and includes techniques like clustering and dimensionality reduction.

Since regression models are trained on known input-output pairs (e.g., house size ➝ price), regression is a supervised learning method.

---

## 🔍 Purpose of Regression
The primary goal of regression is to model the relationship between independent variables (features) and a dependent variable (target). This allows us to:

Predict future outcomes (e.g., predicting house prices, stock market trends)

Analyze impact of input variables (e.g., understanding how income affects spending)

Estimate missing data (e.g., imputing unknown values)

Perform trend analysis and forecasting



## 📦 Common Applications
Real Estate: Estimating property prices

Finance: Predicting stock prices or credit risk

Healthcare: Forecasting patient recovery times or disease progression

Retail: Sales prediction and demand forecasting

Marketing: Customer lifetime value and ROI estimation

Engineering: Modeling sensor readings or failure probabilities


## 🛠️ Types of Regression Techniques
Linear Regression – Assumes a linear relationship between input and output.

Polynomial Regression – Captures non-linear trends using polynomial terms.

Regularized Regressions – Like Ridge, Lasso, and ElasticNet, to prevent overfitting.

Tree-based Models – Like Decision Trees and Random Forests, for non-linear, hierarchical patterns.

Support Vector Regressor (SVR) – Based on margin maximization for robustness to outliers.

---

## 📊 Overview

In this notebook, we:
- Load and explore the California Housing dataset
- Preprocess the data
- Train and test 8 regression models
- Evaluate them using **R² Score** and **Mean Squared Error (MSE)**
- Visualize performance comparisons with bar plots

---

## 🧠 Models Compared

| Model Name              | Description |
|------------------------|-------------|
| Linear Regression       | A baseline linear approach |
| Ridge Regression        | L2-regularized linear regression |
| Lasso Regression        | L1-regularized linear regression |
| ElasticNet Regression   | Combination of L1 and L2 penalties |
| Decision Tree           | Tree-based non-linear model |
| Random Forest           | Ensemble of Decision Trees |
| Polynomial Regression   | Models non-linear data using polynomial terms |
| Support Vector Regressor| Margin-based regression |

---

## 📁 File Structure

```bash
.
├── RegressionTypes.ipynb        # Main notebook with all code
├── california_housing.csv       # Dataset (optional - created by the script)
├── README.md                    # Project documentation
```

## 🚀 Getting Started
1. Clone the Repository
```bash
git clone https://github.com/your-username/california-housing-regression.git
cd california-housing-regression
```
2. Install Dependencies
Create a virtual environment (optional but recommended), and install the required packages:

```bash
pip install -r requirements.txt
```
If requirements.txt is not available, manually install:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🧪 How to Use
Run the notebook:

```bash
jupyter notebook RegressionTypes.ipynb
```
Or if you're using VS Code or JupyterLab, simply open and run all cells.

## 📈 Visualizations Included 
1. Feature Importance (Random Forest)
2. Actual vs Predicted Values
3. Bar Charts for R² Score and MSE Comparison

## ✅ Results Snapshot
The models are evaluated on a held-out test set and ranked by R² score. Random Forest and Gradient Boosting often outperform simpler linear models on this dataset.

## 📌 Dataset Source
We use the built-in fetch_california_housing() from sklearn.datasets, which provides housing data based on demographics and geographic info from California districts.

## 🙌 Acknowledgments
1. <a href="https://scikit-learn.org/stable/">scikit-learn</a>
2. <a href="https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html">California Housing Dataset</a>
