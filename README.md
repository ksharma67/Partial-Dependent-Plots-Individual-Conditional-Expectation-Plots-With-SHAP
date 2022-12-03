# Partial-Dependent-Plots-Individual-Conditional-Expectation-Plots-With-SHAP

1. Modeling
Training an advanced Gradient Boosting (XGBoost) Regression model Evaluate the model on the Validation Root Mean Squared Error metric.

2. SHAP Values
Creatjng a shap explainer from gradient boosting model
Explaining individual train (or test) data points on their contribution to the outcome.
The visualization shows features each contributing to push the model output from the base value (the average model output over the training dataset we passed) to the model output. Features pushing the prediction higher are shown in red, those pushing the prediction lower are in blue.
