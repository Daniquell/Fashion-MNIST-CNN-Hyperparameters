# INVESTIGATION OF THE IMPACT OF HYPERPARAMETERS ON THE ACCURACY OF NEURAL NETWORK PREDICTIONS USING THE Fashion-MNIST DATASET

## Abstract
Machine learning and artificial intelligence (AI) are currently actively researching methods for optimi-
zing and tuning model hyperparameters. One key area of research is analyzing the impact of varying hyperpara-
meters, such as the number of two-dimensional convolution (Conv2D) layers and their parameters (number of fil-
ters, kernel size), the size and stride of maximum pooling (MaxPooling2D) layers, the number of neurons in fully
connected layers, activation functions, batch size (batch_size), and the number of training epochs, on the prediction
accuracy of machine learning models using a convolutional neural network architecture on the Fashion-MNIST
dataset.

## Ключевые результаты
- Достигнута **максимальная точность 92%**.
- Оптимальная архитектура:
  - 1 слой Conv2D (32 фильтра, ядро 5×5) → MaxPooling2D (2,2)
  - 1 слой Conv2D (64 фильтра, ядро 3×3) → MaxPooling2D (1,1)
  - Полносвязный слой Dense(512) с активацией ReLU
  - batch_size = 64, 10 эпох, оптимизатор Adam
- Лучшая функция активации: **ReLU**
- Увеличение числа слоёв до 3 **снизило точность до 89%** (вероятно, из-за переобучения)

## Технологии
- Python
- TensorFlow / Keras
- Jupyter Notebook
