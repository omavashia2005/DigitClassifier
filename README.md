# 🧠 MNIST Digit Classification with TinyVGG

A minimal convolutional neural network (CNN) built using PyTorch, implementing the TinyVGG architecture for classifying handwritten digits from the MNIST dataset.


## 🧰 Tech Stack
<p float="left">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/10/PyTorch_logo_icon.svg" height="60" alt="PyTorch" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" height="60" alt="Python" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" height="60" alt="scikit-learn" />
  <img src="https://matplotlib.org/_static/images/logo2.svg" height="60" alt="Matplotlib Logo" />
</p>

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




## 📌 Credits

- Model architecture inspired by [TinyVGG](https://learnpytorch.io).
- Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/)
