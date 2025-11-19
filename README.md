# ThinFilm_Hardness_Prediction
A machine-learning framework that predicts Ultimate Tensile Strength (UTS) of steels using composition + heat-treatment + processing parameters. The dataset is synthetically generated using metallurgy-based rules (Hall–Petch, tempering response, quenching behavior, composition strengthening).

ML-Powered UTS Prediction for Steels

A machine-learning framework that predicts Ultimate Tensile Strength (UTS) of steels using composition + heat-treatment + processing parameters.
The dataset is synthetically generated using metallurgy-based rules (Hall–Petch, tempering response, quenching behavior, composition strengthening).

This project includes:

Complete Google Colab-ready notebook

Automated synthetic dataset

Multiple ML models (Linear Regression, Random Forest, Tuned RF)

Visual dashboards for EDA, feature importance & prediction accuracy

Ready-made model saving + prediction function

🧩 Features

Synthetic dataset generator inspired by real metallurgical principles

Detailed EDA (correlation maps, scatter trends, distributions)

Machine Learning models (Baseline LR → RF → Tuned RF)

Visual dashboard combining:

UTS distribution

Feature correlations

True vs predicted plots

Residuals

Feature importance

Exportable trained model (joblib)

A plug-and-play prediction function for new steels

## 🖥️ Run in Google Colab
Open directly in Colab:

[![Open In Colab](https://colab.research.google.com/drive/17X9mRfIwehuVFDrme0tQ_ZMhVimW6sro?authuser=0#scrollTo=VSiaQ86At9dE)


📦 Requirements
pip install numpy pandas matplotlib seaborn scikit-learn joblib shap xgboost
