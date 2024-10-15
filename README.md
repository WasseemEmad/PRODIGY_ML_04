# PRODIGY_ML_04

# **Hand Gesture Recognition Using Deep Learning**
This project implements a deep learning-based hand gesture recognition model that accurately identifies and classifies different hand gestures from image data. The model is designed to facilitate intuitive human-computer interaction and enable gesture-based control systems.

## **Project Overview**
The primary goal of this project is to develop a robust hand gesture recognition model using Convolutional Neural Networks (CNNs). The model is capable of recognizing ten different hand gestures with high accuracy.

## **Dataset**
The dataset used in this project consists of hand gesture images organized in folders according to their gesture labels.The images are loaded, preprocessed, and split into training, validation, and test sets to train and evaluate the model.

## **Key Features**

### **Data Preprocessing:**
Images are loaded from directories, resized, and normalized.

Labels are adjusted to match the number of gesture classes.

Data is split into training, validation, and test sets using stratified sampling.

### **Data Augmentation:**

Augmented training data using random transformations (rotation, zoom, shifting, etc.) to improve model generalization.

### **Model Architecture:**

Built a Convolutional Neural Network (CNN) using TensorFlow and Keras.

The model consists of several convolutional, max-pooling, batch normalization, and dropout layers to enhance learning and prevent overfitting.

Output layer uses a softmax activation function for multi-class classification.

### **Training and Evaluation:**

Implemented early stopping and model checkpointing to optimize training.

The model achieved an accuracy of 99.57% on the test set.

A confusion matrix and classification report are provided to evaluate the model's performance across all gesture classes.

### ***Visualization:**

Training history (accuracy and loss over epochs) is plotted.

Confusion matrix and sample predictions on the test set are visualized.

## **Results**

### **The model achieved:**

**Test accuracy:** 99.57%

**Classification report:** High precision, recall, and F1-score for all gesture classes.

**Confusion matrix:** Minimal misclassifications across gesture classes.
