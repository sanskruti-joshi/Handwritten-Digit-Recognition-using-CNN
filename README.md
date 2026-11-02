# Handwritten Digit Recognition using CNN

This repository contains an implementation of a **Convolutional Neural Network (CNN)** for recognizing handwritten digits from the **MNIST dataset**. The project demonstrates the application of deep learning techniques in computer vision, specifically in image classification tasks.

---

## 📌 Project Overview
Handwritten digit recognition is a classic problem in the field of machine learning and computer vision.  
The MNIST dataset consists of **70,000 grayscale images** of handwritten digits (0–9), each of size **28x28 pixels**.  

Our CNN model learns spatial hierarchies of features automatically and achieves **99% accuracy** on this benchmark dataset.

---

## ⚙️ Features
- Preprocessing and normalization of the MNIST dataset  
- CNN model architecture with convolution, pooling, dropout, and dense layers  
- Model training and validation with accuracy/loss visualization  
- **Real-time handwritten digit recognition inside Jupyter Notebook**  
- **GUI integration using PIL (Python Imaging Library) and embedded HTML**  
- Easy-to-run Jupyter notebook / Python script  

---

## 🧩 Model Architecture
A typical CNN architecture used in this project:

- **Input layer** → 28x28 grayscale image  
- **Conv2D layers** with ReLU activation  
- **MaxPooling layers**  
- **Dropout layers** (to reduce overfitting)  
- **Flatten layer**  
- **Dense (Fully Connected) layers** with ReLU and Softmax activation  

---

## 📊 Dataset
- **Source:** [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)  
- **Classes:** 10 (digits 0–9)  
- **Train set:** 60,000 images  
- **Test set:** 10,000 images  

---

## 📈 Results
- **Training Accuracy:** ~99%  
- **Test Accuracy:** ~99%  

### 🔹 Real-Time Digit Recognition (GUI inside Notebook)
The project includes a **real-time digit recognition interface** built directly in the Jupyter Notebook using:  
- **PIL (Python Imaging Library)** for image handling  
- **Embedded HTML & JavaScript** for drawing digits in a canvas  

Users can draw a digit in the canvas, and the trained CNN predicts the digit instantly.  

#### Example:  
| Drawn Digit | Model Prediction |
|-------------|------------------|
| ![digit1](drawn_digit_3.png) | 3 |
| ![digit2](drawn_digit_8.png) | 8 |

---
