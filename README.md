# CIFAR-10 Image Classification using CNN

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/0x41hd/Cnn_Ahd_Model/blob/main/cnn_ahd.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An end-to-end Deep Learning project for classifying images from the CIFAR-10 dataset using a custom Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## 📊 Dataset
The **CIFAR-10** dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

## 🏗️ Model Architecture
The network features a sequential structure with the following layers:
* **Convolutional Layers:** 32, 64, 64, and 128 filters with ReLU activation (`padding='same'`).
* **Pooling Layers:** Max Pooling 2D for spatial downsampling.
* **Regularization:** Dropout and Batch Normalization.
* **Dense Layers:** 128 units (ReLU) leading to a 10-unit Softmax output.

Total Trainable Parameters: **393,738**

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed. You can install the required packages using:
```bash
pip install -r requirements.txt
