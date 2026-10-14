# Boston Housing Price Prediction Using ANN

## Project Overview
This project uses an Artificial Neural Network (ANN) to predict median house values using the Boston Housing Dataset.

## Technologies Used
- Python
- TensorFlow and Keras
- Scikit-learn
- Pandas and NumPy
- Matplotlib

## Model Architecture
- Input layer: 13 features
- Hidden layer 1: 64 neurons, ReLU activation
- Hidden layer 2: 32 neurons, ReLU activation
- Output layer: 1 neuron for price prediction

## Data Preprocessing
- Missing-value handling
- Train-test split
- Feature scaling using StandardScaler

## Model Evaluation

| Metric | Result |
|---|---:|
| MAE | 2.5895 |
| MSE | 14.9699 |
| RMSE | 3.8691 |
| R² Score | 0.7959 |

These results are from the initial model run and may vary with different environments or training settings.

## Learning Outcomes
- Understanding ANN architecture
- Training a neural network for regression
- Applying feature scaling
- Evaluating regression models
- Visualizing training and validation loss

## Dataset Note
The Boston Housing Dataset has documented ethical limitations. This project is intended for educational purposes, not real-world property valuation.
