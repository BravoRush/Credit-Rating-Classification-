📌**Project Overview**

This repository contains the implementation of a machine learning framework designed to predict and interpret corporate credit ratings within the Indonesian credit market.

While traditional credit rating methodologies often struggle with timeliness and objectivity. This project leverages ensemble learning to provide high-accuracy predictions. Furthermore, it addresses the "black-box" nature of AI by integrating SHAP (SHapley Additive exPlanations) to ensure model transparency and interpretability.

🚀 **Key Features**

Predictive Modeling: Implementation of state-of-the-art ensemble methods: Random Forest (Bagging) and XGBoost (Boosting).

Model Explainability: Integration of SHAP values to identify and visualize the key financial indicators driving specific rating decisions.

Indonesian Market Focus: Tailored for the specific dynamics of Indonesian corporations and local rating agencies.

📊 **Methodology**

Recent empirical research indicates that ensemble methods outperform standalone models in credit tasks. This project follows a structured data science pipeline:

Preprocessing: Handling missing value, outliers and class imbalance.

Model Training: Optimization of XGBoost and Random Forest using hyperparameter tuning.

Evaluation: Measuring efficacy via accuracy, precision-recall, and F1-score across various rating classes.

Interpretation: Applying SHAP to bridge the gap between high predictive power and financial accountability.

🛠️ **Tech Stack**

Language: Python

Libraries: scikit-learn, XGBoost, SHAP, pandas, matplotlib/seaborn

