🏡 Predicting House Prices: Ames Housing Kaggle Project
This project was developed as part of a Machine Learning capstone for the New York City Data Science Academy Bootcamp. The primary goal is to build a predictive and interpretable model that estimates real estate sale prices using the Ames Housing dataset.

🎯 Project Objectives
Gain Business Insights
Perform feature engineering and descriptive data analysis to understand which factors are most strongly correlated with house sale prices.

Build Predictive Models
Train and evaluate several machine learning models to accurately predict house sale prices.

Ensure Interpretability
Use SHAP (SHapley Additive exPlanations) to interpret model predictions and understand the role each feature plays.

🧾 Dataset Overview
The Ames Housing dataset includes 2,580 house sale records from 2006 to 2010, compiled by Professor Dean De Cock of Truman State University. It features 81 columns, including:

1 target variable: SalePrice

80 predictors: capturing lot size, neighborhood, quality ratings, house style, garage size, and more

43 categorical features

36 numeric features

🗂️ Predictor Categories
Predictors were grouped into 10 thematic categories:

Location, Zoning & Proximity
Neighborhood, MSZoning, LotArea, LotFrontage, Street, Alley, LotShape, LandContour

Structural & Building Class

Exterior Materials & Finishes

Foundation & Below Grade

Living Area & Floor Plan

Heating, Cooling & Electrical

Fireplaces

Garage & Parking

Outdoor Features & Amenities

Transaction Details

🔍 Workflow Summary
1. Preprocessing & Exploratory Analysis
Missing value imputation

Scatterplots, boxplots, and heatmaps for visual EDA

2. Model Development & Tuning
Built models using:

ElasticNet

Random Forest

XGBoost

Used Optuna for hyperparameter optimization

Created Scikit-learn Pipelines for efficient model deployment

3. Model Interpretability with SHAP
SHAP summary, beeswarm, and dependency plots

Identified top contributing features

4. Performance Evaluation
Model metrics visualization

Actual vs. predicted price plots

🧠 Key Results
✅ Best Model: XGBoost Regressor

✅ R² Score: 0.94 — model explains 94% of variability in sale prices

✅ Top Predictive Features:

Quality and Condition: Overall quality, kitchen quality, exterior condition

Size Metrics: Living area, garage area, basement space

Age & Updates: Year built, remodel date

Amenities: Number of fireplaces, garage capacity

📊 Visual Insights
SHAP plots provide transparent explanations of how each feature influences individual predictions.

Performance plots help visualize model accuracy and generalizability.

🤝 Acknowledgments
Developed as part of the NYC Data Science Academy Bootcamp using the publicly available Ames Housing dataset created by Dean De Cock.

