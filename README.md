📈 LSTM Neural Network for Time Series Prediction

This project demonstrates a simple but effective implementation of an LSTM (Long Short-Term Memory) neural network using TensorFlow/Keras to predict values of a sine wave.
The goal is to show how recurrent neural networks can learn temporal patterns and make forecasts based on sequential data.

🚀 Project Overview

The model is trained on artificially generated sine wave sequences.
Each sample contains:

X → A sequence of sine values with slight noise

y → A single target value representing the sine value at 2π (also with noise)

After training, the model predicts output values for unseen sequences, and the results are visualized in a comparison plot.

🧠 Technologies Used

Python

NumPy

Pandas

TensorFlow / Keras

Matplotlib

🧩 Model Architecture

The neural network is built using Keras’ Sequential API and includes:

LSTM layer — learns temporal dependencies

Dropout — prevents overfitting

Dense layer — outputs the final prediction

Adam optimizer — efficient gradient-based training
