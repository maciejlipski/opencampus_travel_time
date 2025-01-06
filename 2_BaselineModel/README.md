# Baseline Model

The baseline model aims to predict the speed of a rider (e.g., cyclist, runner) based on terrain characteristics and cumulative statistics of the current track. It utilizes two different machine learning algorithms

#### Linear Regression

- Implementation: A simple linear regression model is trained using the LinearRegression class from scikit-learn.
- Features: It uses six features: 'Elevation', 'Slope_prev', 'Slope_next', 'Angle', 'Distance', and 'Cumulative_Slope'.
- Training: The model is trained on a portion of the dataset (X_train, y_train).
- Prediction: It predicts the speed (y_pred) for the test set (X_test) and new unseen data.
- Evaluation: The model's performance is evaluated using Mean Absolute Error (MAE). The trained model is saved as lr_model.joblib.

**[Notebook](baseline_model.ipynb)**
