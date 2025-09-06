# PneumoniaDetection
This project applies Convolutional Neural Networks (CNNs) to classify chest X-ray images into Normal or Pneumonia. The goal is to demonstrate how deep learning can assist in medical image analysis, providing a foundation for AI-assisted healthcare applications.

# 🫁 Pneumonia Detection using CNN

This project applies **Convolutional Neural Networks (CNNs)** to classify **chest X-ray images** into **Normal** or **Pneumonia**.  
The goal is to demonstrate how deep learning can assist in medical image analysis, providing a foundation for AI-assisted healthcare applications.  

---

## 📌 Project Overview
- **Dataset**: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)  
- **Task**: Binary image classification – *Normal vs Pneumonia*  
- **Model**: Custom CNN built with **TensorFlow/Keras**  
- **Evaluation**: Accuracy, Loss, Confusion Matrix, Training/Validation Curves  

---

## 🔬 Features
- Data preprocessing and augmentation with `ImageDataGenerator`  
- CNN architecture with convolutional, pooling, and dense layers  
- Binary classification using **sigmoid activation**  
- Training vs Validation curves for **loss** and **accuracy**  
- Inference on single test X-rays with thresholding (`0.5`)  
