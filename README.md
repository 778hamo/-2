Fashion-MNIST Classification using MLP

This project implements a simple Multi-Layer Perceptron (MLP) neural network using TensorFlow and Keras to classify clothing images from the Fashion-MNIST dataset.

Project Steps
Load and visualize the dataset
Normalize image data
Apply One-Hot Encoding to labels
Split data into training and validation sets
Build and train an MLP model
Evaluate model performance
Plot loss and accuracy curves
Technologies Used
Python
NumPy
Matplotlib
TensorFlow / Keras
Scikit-learn
Model Architecture
Flatten Layer
Dense Layer (128 neurons, ReLU)
Dropout Layer (0.2)
Dense Layer (64 neurons, ReLU)
Output Layer (10 classes, Softmax)
Dataset

The project uses the Fashion-MNIST dataset containing 70,000 grayscale images of fashion products across 10 categories.

Results

The model achieves approximately:

Training Accuracy: ~90%
Test Accuracy: ~88%
Run the Project

Install dependencies:

pip install tensorflow numpy matplotlib scikit-learn

Run the script:

python fashion_mnist_mlp.py
