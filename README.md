# INVESTIGATION OF THE IMPACT OF HYPERPARAMETERS ON THE ACCURACY OF NEURAL NETWORK PREDICTIONS USING THE Fashion-MNIST DATASET

## Abstract
Machine learning and artificial intelligence (AI) are currently actively researching methods for optimi-
zing and tuning model hyperparameters. One key area of research is analyzing the impact of varying hyperpara-
meters, such as the number of two-dimensional convolution (Conv2D) layers and their parameters (number of fil-
ters, kernel size), the size and stride of maximum pooling (MaxPooling2D) layers, the number of neurons in fully
connected layers, activation functions, batch size (batch_size), and the number of training epochs, on the prediction
accuracy of machine learning models using a convolutional neural network architecture on the Fashion-MNIST
dataset.

## Key Results
- A maximum classification accuracy of **92%** was achieved.
- The optimal architecture comprises:
  - A first Conv2D layer (32 filters, 5×5 kernel) followed by a MaxPooling2D layer (2×2).
  - A second Conv2D layer (64 filters, 3×3 kernel) followed by a MaxPooling2D layer (1×1).
  - A fully connected Dense layer (512 units) with ReLU activation.
  - Training was conducted over 10 epochs with a batch size of 64, utilizing the Adam optimizer.
- **ReLU** was identified as the optimal activation function.
- Increasing the network depth to three layers reduced the accuracy to 89%, presumably due to overfitting.

## Technologies
- Python
- TensorFlow / Keras
- Jupyter Notebook
