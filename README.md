# Partial-Dependent-Plots-Individual-Conditional-Expectation-Plots-With-SHAP

SHAP (SHapley Additive exPlanations) is a method to explain individual predictions. SHAP is based on the game theoretically optimal Shapley values.

The goal of SHAP is to explain the prediction of an instance x by computing the contribution of each feature to the prediction.
The SHAP explanation method computes Shapley values from coalitional game theory.
The feature values of a data instance act as players in a coalition.
Shapley values tell us how to fairly distribute the “payout” (= the prediction) among the features. A player can be an individual feature value, e.g. for tabular data.
A player can also be a group of feature values.


1. Modeling

Training an advanced Gradient Boosting (XGBoost) Regression model Evaluate the model on the Validation Root Mean Squared Error metric.

2. SHAP Values

Creating a shap explainer from gradient boosting model
Explaining individual train (or test) data points on their contribution to the outcome.
The visualization shows features each contributing to push the model output from the base value (the average model output over the training dataset we passed) to the model output. Features pushing the prediction higher are shown in red, those pushing the prediction lower are in blue.
