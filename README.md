# Task1-Credit-Scoring-Mode
machine Learning project
# Credit Scoring Model

##  Project Overview
This project builds and evaluates a **machine learning pipeline** for predicting whether an individual is **creditworthy** based on financial and behavioral features. It simulates a **real-world credit scoring system** by:
- Generating synthetic but realistic credit data.
- Preprocessing and engineering features.
- Training multiple classification models.
- Evaluating performance with standard metrics and ROC curves.
- Saving trained models and datasets for future use.

 ##  Features
- **Synthetic Data Generation** – Creates realistic financial and demographic attributes.
- **Feature Engineering** – Adds debt-to-income and late-payment-rate metrics.
- **Data Preprocessing** – Handles missing values, scaling, and one-hot encoding.
- **Multiple Models** – Logistic Regression, Decision Tree, Random Forest.
- **Hyperparameter Tuning** – Grid search optimization for Random Forest.
- **Evaluation** – ROC-AUC, precision, recall, F1-score, confusion matrix.
- **Feature Importance** – Determines most predictive factors.
- **Artifact Saving** – Stores trained pipelines and datasets.

##  Technologies Used
- **Python 3.x**
- **NumPy, Pandas** – Data handling
- **Matplotlib** – Visualization
- **scikit-learn** – Machine learning pipeline
- **joblib** – Model serialization

##  How to Run
1. **Clone the repository** (or download the notebook).
2. **Install dependencies**:
   ```bash
   pip install numpy pandas matplotlib scikit-learn joblib
