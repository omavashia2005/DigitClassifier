# 🧠 MNIST Digit Classification with TinyVGG

A minimal convolutional neural network (CNN) built using PyTorch, implementing the TinyVGG architecture for classifying handwritten digits from the MNIST dataset.

## 📌 Overview

This project demonstrates a simple, from-scratch implementation of the TinyVGG architecture for image classification. The model is trained on the MNIST dataset, achieving high accuracy with a lightweight architecture suitable for learning and experimentation.

## 🏗️ Architecture

**TinyVGG**:
- 2 convolutional blocks  
  - Each block: `Conv2D -> ReLU -> Conv2D -> ReLU -> MaxPool2D`
- Flatten layer
- Fully connected output layer

## 📊 Results

Trained for a total of 3 epochs

|             Model           |    Accuracy   |
|-----------------------------|---------------|
| **Baseline**                | ~92%          |
| **TinyVGG**                 | ~98%          |


## 🧰 Tech Stack

- Python 3
- PyTorch
- `scikit-learn`
- `Torchvision`

## 📌 Credits

- Model architecture inspired by [TinyVGG](https://learnpytorch.io).
- Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/)
