# 🤖 Complete Machine Learning

> A structured, hands-on implementation of every major Machine Learning algorithm — from mathematical foundations to production-ready code.
> Built while completing **CampusX DSMP 1.0 + 2.0** alongside **IIT Madras BS in Data Science and Applications**.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3+-orange?style=flat&logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## 📁 Repository Structure

| # | Folder | Topics Covered |
|---|--------|----------------|
| 01 | [`23_Linear_Regression`](./23_Linear_Rigression/) | Simple & Multiple Linear Regression, OLS, MSE, R² — implemented from scratch |
| 02 | [`24_Gradient_Descent`](./24_Gradient_Descent/) | Batch GD, Stochastic GD, Mini-batch GD — coded from scratch with visualization |
| 03 | [`25_Regression_Analysis`](./25_Regression_analysis/) | Regression assumptions, F-statistic, multicollinearity, VIF, statsmodels |
| 04 | [`26_Feature_Selection`](./26_Feature_selection/) | Filter methods, Wrapper methods (RFE, SFS), Embedded methods (LASSO, Tree-based) |
| 05 | [`27_Regularization`](./27_Regularization/) | Ridge, Lasso, ElasticNet — geometric intuition + from-scratch implementation |
| 06 | [`28_KNN`](./28_KNN/) | K-Nearest Neighbors for classification + regression, KD-Tree, weighted KNN |
| 07 | [`29_PCA`](./29_PCA/) | Principal Component Analysis — Eigendecomposition, SVD, explained variance |
| 08 | [`30_Model_Evaluation`](./30_Model%20Evaluation%20%26%20Selection/) | Cross-validation, ROC-AUC, Precision-Recall, GridSearchCV, RandomizedSearchCV |
| 09 | [`31_Naive_Bayes`](./31_Naive_bayes/) | Gaussian, Multinomial, Bernoulli NB — Laplace smoothing, log probabilities |
| 10 | [`32_Logistic_Regression`](./32_Logistic_Regression/) | Binary + Multiclass (OvR, Softmax), MLE, Log-loss, regularization |
| 11 | [`33_SVM`](./33_SVM/) | Hard + Soft Margin SVM, Kernel trick (RBF, Polynomial), Dual problem |
| 12 | [`34_Decision_Tree`](./34_Decision_Tree/) | CART algorithm, Gini impurity, pruning, feature importance, visualization |
| 13 | [`35_Random_Forest`](./35_Random_forest/) | Bagging, Random Forest, OOB score, feature importance, hyperparameter tuning |
| 14 | [`36_Gradient_Boosting`](./36_Gradient%20Boosting/) | Gradient Boosting — function space intuition, pseudo-residuals, math formulation |
| 15 | [`XgBoost`](./XgBoost/) | XGBoost for regression + classification — Taylor series loss, similarity score |
| 16 | [`LightGBM_and_CatBoost`](./LightGBM%20and%20Catboost/) | LightGBM (leaf-wise), CatBoost (categorical handling) — comparison with XGBoost |
| 17 | [`K-Means-Clustering`](./K-Means-clustering/) | KMeans++, Elbow method, Silhouette score, Mini-batch KMeans |
| 18 | [`Unsupervised_Learning`](./Unsupervised%20Learning/) | DBSCAN, Hierarchical Clustering, GMM, t-SNE |

---

## 🧠 Concepts Covered

**Supervised Learning**
- Linear Models: Linear Regression, Logistic Regression, Ridge, Lasso, ElasticNet
- Tree Models: Decision Trees, Random Forest, Gradient Boosting, XGBoost, LightGBM, CatBoost
- Instance-based: KNN (classification + regression)
- Kernel Methods: SVM (Hard/Soft margin, RBF, Polynomial kernel)
- Probabilistic: Naive Bayes (Gaussian, Multinomial, Bernoulli)

**Unsupervised Learning**
- Clustering: KMeans, DBSCAN, Hierarchical (Single, Complete, Ward), GMM
- Dimensionality Reduction: PCA (Eigendecomposition + SVD), t-SNE

**ML Engineering**
- Optimization: Batch GD, SGD, Mini-batch GD (from scratch)
- Feature Engineering: Feature selection (Filter, Wrapper, Embedded), missing value imputation
- Regularization: L1 (Lasso), L2 (Ridge), ElasticNet — geometric intuition
- Model Evaluation: Cross-validation, ROC-AUC, Precision-Recall, F1, Confusion Matrix
- Hyperparameter Tuning: GridSearchCV, RandomizedSearchCV, Optuna

---

## 🔧 Tech Stack

```
Python 3.10+    — Core language
NumPy           — Numerical computing, from-scratch implementations
Pandas          — Data manipulation and preprocessing
Scikit-learn    — ML algorithms, pipelines, evaluation
XGBoost         — Gradient boosting framework
LightGBM        — Fast gradient boosting
CatBoost        — Categorical feature boosting
Optuna          — Hyperparameter optimization
Matplotlib      — Visualizations
Seaborn         — Statistical visualizations
Jupyter         — Interactive notebooks
```

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Div7anshKushwaha/complete-machine-learning.git
cd complete-machine-learning

# Install dependencies
pip install numpy pandas scikit-learn xgboost lightgbm catboost optuna matplotlib seaborn jupyter

# Launch Jupyter
jupyter notebook
```

Then navigate to any folder and open the `.ipynb` file.

---

## 📌 Key Highlights

- **From-scratch implementations** — Linear Regression, Gradient Descent, Backpropagation, PCA, KNN all implemented using only NumPy before using Sklearn
- **Math-first approach** — Every algorithm includes mathematical formulation before code
- **Bias-Variance Tradeoff** — Demonstrated practically across multiple algorithms
- **Complete Boosting stack** — Gradient Boosting → XGBoost → LightGBM → CatBoost with comparison
- **Full unsupervised suite** — KMeans, DBSCAN, Hierarchical, GMM, t-SNE in one place

---

## 🎯 Learning Source

- **IIT Madras BS in Data Science** — Machine Learning Foundations (MLF) + Machine Learning Techniques (MLT) + Machine Learning Practice(MLP) course
  
---

## 👤 Author

**Divyansh Kushwaha**
IIT Madras — BS in Data Science and Applications

[![GitHub](https://img.shields.io/badge/GitHub-Div7anshKushwaha-black?style=flat&logo=github)](https://github.com/Div7anshKushwaha)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-divyansh--kushwaha-blue?style=flat&logo=linkedin)](https://linkedin.com/in/divyansh-kushwaha-603616383)

---

## 📄 License

MIT License — feel free to use, modify, and share.
