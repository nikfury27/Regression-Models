# 🏡 California Housing Regression Model Comparison

This project demonstrates the application and comparison of **eight regression algorithms** on the **California Housing dataset**, using Python and the `scikit-learn` library. The goal is to evaluate each model's performance using key regression metrics and visualize the results.

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
2.<a href="https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html">California Housing Dataset</a>
