# CIFAR-10 Image Classification with Convolutional Neural Networks (CNNs)

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style/for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style/for-the-badge&logo=keras&logoColor=white)](https://keras.io/)

A hands-on lab to build and train a **Convolutional Neural Network (CNN)** for the task of image classification on the well-known **CIFAR-10 dataset**. 🖼️

---

## 📖 Lab Overview

This exercise provides a practical introduction to building CNNs, one of the most important architectures in modern deep learning. We will be working with the CIFAR-10 dataset, a standard benchmark for image classification models.

The lab is structured in two main parts:
1.  **Guided Walkthrough:** We will first explore the fundamental building blocks of a CNN, explaining how to configure each layer in Keras.
2.  **Your Turn:** You will then use this knowledge to design, build, and train your own CNN, aiming to achieve the best possible classification accuracy.

---

## 📊 The CIFAR-10 Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images distributed across 10 distinct classes, with 6,000 images per class. The dataset is pre-split into 50,000 training images and 10,000 test images.

The 10 classes are:
* ✈️ airplane
* 🚗 automobile
* 🐦 bird
* 🐱 cat
* 🦌 deer
* 🐶 dog
* 🐸 frog
* 🐴 horse
* 🚢 ship
* 🚚 truck



---

## 🔬 Core Concepts: Building a CNN

We will explore the key layers that form a Convolutional Neural Network:

* **Convolutional Layer (`Conv2D`):** The core of the CNN. This layer uses learnable filters (or kernels) to slide across the input image and detect specific features, such as edges, corners, and textures.
* **Pooling Layer (`MaxPooling2D`):** This layer is used to downsample the feature maps, reducing their spatial dimensions. This helps to decrease computational load and makes the detected features more robust to their position in the image.
* **Flatten Layer:** This layer unrolls the 2D feature maps into a single 1D vector, preparing the data for the final classification stage.
* **Dense Layer:** A standard fully-connected neural network layer that performs the final classification based on the high-level features extracted by the convolutional layers.

---

## 🎯 Learning Objectives

After completing this lab, you will be able to:

1.  Understand the role and function of each key layer in a CNN.
2.  Configure and stack these layers in Keras to build a complete model.
3.  Load and preprocess image data for training.
4.  Train a CNN on the CIFAR-10 dataset and evaluate its performance.
5.  Experiment with different architectures to improve model accuracy.

---
