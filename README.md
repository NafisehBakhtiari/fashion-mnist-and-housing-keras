# Keras Deep Learning Fundamentals

A hands-on notebook covering the core building blocks of deep learning with
TensorFlow/Keras, using two classic datasets.

## Contents

### 1. Image Classification - Fashion-MNIST
- Loading and normalizing the data
- Building a Sequential MLP (100 -> 75 -> 10, softmax)
- Training with SGD, plotting loss/accuracy curves
- Evaluation and prediction on test images

### 2. Regression - California Housing
- Train/validation/test split and feature scaling
- Sequential regression model (MSE loss, MAE metric)

### 3. Advanced Model Building
- **Functional API**: wide & deep network, multi-input model, auxiliary output
- **Subclassing API**: custom `WideAndDeepANN` model

### 4. Training Utilities
- Saving and loading models
- Callbacks: `ModelCheckpoint`, `EarlyStopping`, custom callback, TensorBoard

### 5. Hyperparameter Tuning
- Wrapping a Keras model for scikit-learn
- `GridSearchCV` over number of layers, neurons, and learning rate

## Tech Stack
Python, TensorFlow/Keras, scikit-learn, NumPy, Matplotlib, Jupyter

## How to Run

```bash
git clone https://github.com/YOUR-USERNAME/keras-deep-learning-fundamentals.git
cd keras-deep-learning-fundamentals
pip install -r requirements.txt
jupyter notebook notebooks/deep_learning_project.ipynb
```

## What I Learned
- Differences between the Sequential, Functional, and Subclassing APIs
- Why feature scaling and validation splits matter
- Using callbacks to prevent overfitting and monitor training

## License
MIT
