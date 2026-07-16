# CNN for CIFAR-10 Image Classification
A Convolutional Neural Network (CNN) built using PyTorch to classify images from the CIFAR-10 dataset.
---
## 📌 Project Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset. The model is trained on 10 image categories and evaluated using classification metrics and a confusion matrix.
---
## 🚀 Features
- Data preprocessing using Torchvision
- Custom CNN architecture
- ReLU activation
- MaxPooling layers
- Fully Connected layers
- Adam Optimizer
- CrossEntropy Loss
- Model evaluation
- Confusion Matrix
- Classification Report
---
## 📂 Dataset
**CIFAR-10**
- 60,000 RGB Images
- 10 Classes
- Image Size: 32 × 32
Classes:
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
---
## 🛠 Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
---
## 🧠 Model Architecture
```
Input (32×32×3)
↓
Convolution Layer
↓
ReLU
↓
Max Pooling
↓
Convolution Layer
↓
ReLU
↓
Max Pooling
↓
Flatten
↓
Fully Connected Layer
↓
Output Layer (10 Classes)
```
---
## 📊 Results
| Metric | Value |
|--------|-------|
| Test Accuracy | **74.76%** |
| Number of Epochs | **10** |
| Optimizer | **Adam** |
| Loss Function | **CrossEntropyLoss** |
---
## 📁 Project Structure
```
cnn-cifar10-image-classification/
│
├── cnn_cifar10_classification.ipynb
├── README.md
└── .gitignore
```
---
## 👨‍💻 Author
**Shashi Charan**
