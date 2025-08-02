# 🧠 Image Classification with CNN on CIFAR-10

This project implements a **Convolutional Neural Network (CNN)** using **PyTorch** to classify images from the **CIFAR-10** dataset into 10 categories (e.g., airplanes, cars, birds, cats, etc.).

## 🚀 Project Overview

- **Goal**: Classify RGB images (32x32) into one of the 10 CIFAR-10 classes.  
- **Framework**: PyTorch  
- **Dataset**: CIFAR-10 (automatically downloaded)

## 🗂️ Dataset

CIFAR-10 is a labeled subset of the 80 million tiny images dataset and consists of 60,000 32x32 color images in 10 classes:

- Airplane  
- Automobile  
- Bird  
- Cat  
- Deer  
- Dog  
- Frog  
- Horse  
- Ship  
- Truck  

- 50,000 training images  
- 10,000 test images

## 🏗️ Model Architecture

The CNN architecture typically includes:
- Convolutional Layers  
- ReLU Activations  
- Max Pooling Layers  
- Fully Connected Layers  
- Softmax/Logits Output
