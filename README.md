# Explainable AI with SHAP Values
## Opening the Black Box of Machine Learning Models
Machine learning models such as Random Forests can achieve high accuracy but often act as “black boxes,” making it difficult to understand how predictions are made. This lack of transparency is a major issue in high-stakes domains like healthcare and finance. This project explores SHAP (SHapley Additive exPlanations), a game theory–based approach that explains model predictions by assigning each feature a clear contribution, improving trust and interpretability.

SHAP is applied to a Random Forest model trained on the Wisconsin Breast Cancer dataset, achieving strong predictive performance. It provides both global interpretability (feature importance and overall model behaviour) and local interpretability (individual prediction explanations). Visual tools such as SHAP bar charts, beeswarm plots, and waterfall plots help illustrate how features influence predictions at both the model and instance level.

Overall, SHAP is a powerful method for making machine learning models more transparent and explainable. It is particularly useful for model auditing, fairness analysis, and debugging. However, it does not address causality or eliminate bias, and results should always be interpreted with domain knowledge.
