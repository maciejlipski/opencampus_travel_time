# Model Definition and Evaluation

## Model Selection
After the baseline model, final model was focused on predicting cycling speed and subsequently, the time taken for a route. To achieve this, two models are employed:
**- Linear Regression (LR):** This serves as the baseline model, representing a simpler approach. It assumes a linear relationship between the features (elevation, slope, etc.) and the target variable (speed). It's pre-trained and loaded from a file. This model provides a benchmark for comparison with more complex approaches.

**- Neural Network (NN):** This model leverages the power of deep learning to capture potentially non-linear relationships within the data. It's built using TensorFlow/Keras and consists of an input layer, hidden layers with activation functions (ReLU) and dropout for regularization, and an output layer. This structure allows the NN to learn complex patterns and make more nuanced predictions compared to the LR model.

## Feature Engineering:
The selection of relevant features is crucial for accurate predictions. The code utilizes the following:


**[Notebook](model_definition_evaluation)**
