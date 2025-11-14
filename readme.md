# CODE BASICS Machine Learning Basics Course (Youtube)

## Summary

This repository contains a comprehensive machine learning course covering fundamental concepts and practical implementations using scikit-learn. The course progresses from basic regression techniques to advanced ensemble methods and feature engineering. This redme.md is just for my own revision puropose, a summary of the functions or modules used for training.

## sklearn Modules and Functions Used

### Linear Models
- `sklearn.linear_model.LinearRegression` - Linear regression model
- `sklearn.linear_model.LogisticRegression` - Logistic regression for classification
- `sklearn.linear_model.Lasso` - L1 regularization (Lasso regression)
- `sklearn.linear_model.Ridge` - L2 regularization (Ridge regression)
- `sklearn.linear_model` (module) - General linear model module

### Model Selection
- `sklearn.model_selection.train_test_split` - Split dataset into training and testing sets
- `sklearn.model_selection.KFold` - K-fold cross-validation iterator
- `sklearn.model_selection.StratifiedKFold` - Stratified K-fold cross-validation
- `sklearn.model_selection.cross_val_score` - Evaluate model using cross-validation
- `sklearn.model_selection.GridSearchCV` - Exhaustive search over parameter grid
- `sklearn.model_selection.RandomizedSearchCV` - Randomized search over parameter grid

### Preprocessing
- `sklearn.preprocessing.LabelEncoder` - Encode categorical labels as integers
- `sklearn.preprocessing.MinMaxScaler` - Scale features to a range (0-1)
- `sklearn.preprocessing.StandardScaler` - Standardize features (mean=0, std=1)

### Tree-based Models
- `sklearn.tree.DecisionTreeClassifier` - Decision tree classifier
- `sklearn.tree` (module) - Tree-based algorithms module

### Support Vector Machines
- `sklearn.svm.SVC` - Support Vector Classifier

### Ensemble Methods
- `sklearn.ensemble.RandomForestClassifier` - Random forest classifier
- `sklearn.ensemble.BaggingClassifier` - Bagging ensemble classifier

### Clustering
- `sklearn.cluster.KMeans` - K-means clustering algorithm

### Naive Bayes
- `sklearn.naive_bayes.MultinomialNB` - Multinomial Naive Bayes classifier
- `sklearn.naive_bayes.GaussianNB` - Gaussian Naive Bayes classifier

### Feature Extraction
- `sklearn.feature_extraction.text.CountVectorizer` - Convert text to token counts matrix

### Pipeline
- `sklearn.pipeline.Pipeline` - Chain transformers and estimators

### Metrics
- `sklearn.metrics.confusion_matrix` - Compute confusion matrix for classification

### Datasets
- `sklearn.datasets.load_digits` - Load digits dataset
- `sklearn.datasets.load_iris` - Load iris dataset
- `sklearn.datasets.load_wine` - Load wine dataset

### Decomposition
- `sklearn.decomposition.PCA` - Principal Component Analysis for dimensionality reduction

---

## Complete List of sklearn Imports

```python
# Linear Models
from sklearn.linear_model import LinearRegression
from sklearn.linear_model import LogisticRegression
from sklearn import linear_model
from sklearn.linear_model import Lasso
from sklearn.linear_model import Ridge

# Model Selection
from sklearn.model_selection import train_test_split
from sklearn.model_selection import KFold
from sklearn.model_selection import StratifiedKFold
from sklearn.model_selection import cross_val_score
from sklearn.model_selection import GridSearchCV
from sklearn.model_selection import RandomizedSearchCV

# Preprocessing
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import MinMaxScaler
from sklearn.preprocessing import StandardScaler

# Tree Models
from sklearn.tree import DecisionTreeClassifier
from sklearn import tree

# SVM
from sklearn.svm import SVC

# Ensemble
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import BaggingClassifier

# Clustering
from sklearn.cluster import KMeans

# Naive Bayes
from sklearn.naive_bayes import MultinomialNB
from sklearn.naive_bayes import GaussianNB

# Feature Extraction
from sklearn.feature_extraction.text import CountVectorizer

# Pipeline
from sklearn.pipeline import Pipeline

# Metrics
from sklearn.metrics import confusion_matrix

# Datasets
from sklearn.datasets import load_digits
from sklearn.datasets import load_iris
from sklearn.datasets import load_wine

# Decomposition
from sklearn.decomposition import PCA
```

---

### Topics Covered (Folders 1-18)

1. **Linear Regression** - Simple linear regression for predicting continuous values
2. **Multivariate Linear Regression** - Multiple features for regression analysis
3. **Categorical Data Handling** - One-hot encoding for categorical variables
4. **Train-Test Split** - Data splitting for model evaluation
5. **Logistic Regression** - Binary classification problems
6. **Logistic Regression - Multivariate Classification** - Multi-class classification
7. **Decision Trees** - Tree-based classification algorithms
8. **Support Vector Machine (SVM)** - SVM for classification tasks
9. **Random Forest** - Ensemble of decision trees
10. **Cross Validation** - K-fold and stratified cross-validation techniques
11. **K-Means Clustering** - Unsupervised clustering algorithm
12. **Naive Bayes Classifier** - Probabilistic classification using Bayes theorem
13. **Hyperparameter Tuning** - GridSearchCV and RandomizedSearchCV for model optimization
14. **L1 & L2 Regularization** - Lasso and Ridge regression for overfitting prevention
15. **Principal Component Analysis (PCA)** - Dimensionality reduction technique
16. **Bias vs Variance** - Understanding model complexity and generalization
17. **Bagging & Boosting** - Ensemble techniques (BaggingClassifier, RandomForest)
18. **Feature Engineering** - Outlier detection and removal using IQR, Percentile, Z-score, and Standard Deviation methods

---

## Key Concepts Covered

- **Supervised Learning**: Regression (Linear, Lasso, Ridge) and Classification (Logistic, Decision Trees, SVM, Random Forest, Naive Bayes)
- **Unsupervised Learning**: Clustering (K-Means)
- **Model Evaluation**: Train-test split, Cross-validation, Confusion matrix
- **Hyperparameter Tuning**: GridSearchCV, RandomizedSearchCV
- **Regularization**: L1 (Lasso) and L2 (Ridge) regularization
- **Dimensionality Reduction**: Principal Component Analysis (PCA)
- **Ensemble Methods**: Bagging and Random Forest
- **Feature Engineering**: Outlier detection and removal techniques
- **Text Processing**: CountVectorizer for text classification
- **Pipeline**: Creating ML pipelines for streamlined workflows





