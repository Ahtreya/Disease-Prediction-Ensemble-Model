# Disease-Prediction-Ensemble-Model
# Application of Ensemble Learning Model for Disease Prediction

## 🔬 Project Overview
This repository contains a high-performance **Hybrid Stacking Ensemble Model** designed for medical diagnostics. By fusing multiple machine learning algorithms through a meta-learner framework, the system significantly reduces data variance and combats prediction errors, outperforming standalone classifiers.

## 🛠️ Tech Stack & Dataset
- **Language:** Python
- **Libraries:** Scikit-Learn, Pandas, NumPy, XGBoost
- **Dataset Included:** `DiseaseAndSymptoms.csv`

## ⚡ Architecture & Algorithms Fused
The model benchmarks and combines 9 state-of-the-art algorithms:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting
5. XGBoost
6. K-Nearest Neighbors (KNN)
7. Support Vector Classifier (SVC)
8. MLP Classifier
9. Gaussian Naïve Bayes

A **Meta-Learner Architecture** integrates the predictions of these base models, optimizing overall Accuracy, Precision, Recall, and F1-Score for healthcare applications.
