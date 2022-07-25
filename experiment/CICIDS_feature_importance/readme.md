# Examine importance of each feature in CIC-IDS-2017

Train scikit-learn's `RandomForestClassifier` optimized with optuna.

After the model is trained, display the top 20 items in `model.feature_importances_`.