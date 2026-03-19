# Acrylic and Polyurethane Waterborne Coatings Formulation Optimization Using Machine Learning

## Overview
This project demonstrates how machine learning can be applied to waterborne coatings formulation to predict performance properties and accelerate applications activities.

## Objective
Predict Taber abrasion loss (mg loss, ASTM D4060) based on formulation variables:
- Binder type
- Crosslinker level
- Wax additive
- Glass transition temperature (Tg)
- Solids content

## Tools Used
- Python
- pandas
- scikit-learn
- XGBoost
- matplotlib

## Methodology
1. Created a structured dataset simulating coatings formulations
2. Applied feature engineering (one-hot encoding)
3. Trained an XGBoost regression model
4. Evaluated performance using mean absolute error
5. Generated feature importance to identify key formulation drivers

## Key Insights
- Crosslinker content strongly impacts abrasion resistance
- Wax additives improve durability
- Binder selection plays a secondary but important role

## Business Impact
This approach reduces experimental workload by:
- Predicting high-performance formulations
- Reducing trial-and-error
- Accelerating time to market

## Future Work
- Incorporate real experimental data
- Expand dataset size
- Apply DOE + ML hybrid optimization