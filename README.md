# Sign Language Detection using Convolutional Neural Networks (CNN)

A Deep Learning-based Sign Language Recognition System that classifies American Sign Language (ASL) alphabets from hand gesture images using Convolutional Neural Networks (CNNs). The model automatically learns visual features such as finger positions, hand shapes, and gesture patterns directly from image data to accurately predict the corresponding alphabet.

---

## 📖 Overview

Sign language is one of the primary modes of communication for individuals with hearing and speech impairments. This project aims to bridge the communication gap by developing an intelligent system capable of recognizing ASL hand gestures.

The model is trained on image data and uses a CNN architecture to automatically extract meaningful features and classify gestures into their respective alphabet classes.

---

## 96 Features

* American Sign Language (ASL) alphabet recognition
* Convolutional Neural Network (CNN) based classification
* Automatic feature extraction from images
* High classification accuracy
* Lightweight and efficient architecture
* Scalable for additional gesture classes

---

## 🧠 Model Architecture

```text
Input Image (28×28×1)
        │
        ▼
Conv2D (32 Filters, ReLU)
        │
        ▼
MaxPooling2D
        │
        ▼
Conv2D (64 Filters, ReLU)
        │
        ▼
MaxPooling2D
        │
        ▼
Flatten
        │
        ▼
Dense (128, ReLU)
        │
        ▼
Dropout (0.3)
        │
        ▼
Dense (24, Softmax)
```

The CNN learns hierarchical visual features from hand gesture images and classifies them into one of the ASL alphabet categories.

---

## 📊 Model Performance

The model was trained for 8 epochs and achieved:

| Metric              | Score  |
| ------------------- | ------ |
| Training Accuracy   | 99.42% |
| Validation Accuracy | 94.94% |
| Training Loss       | 0.0182 |
| Validation Loss     | 0.2031 |

The results demonstrate strong performance and good generalization on unseen validation data.

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* OpenCV
* Matplotlib
* Deep Learning
* Computer Vision

---
