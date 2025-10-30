# IMAGE CLASSIFICATION MODEL 
COMPANY: CODTECH IT SOLUTIONS NAME: ABINAV G INTERN ID: CT06DY2764 DOMAIN: MACHINE LEARNING DURATION: 6 WEEKS MENTOR : NEELA SANTOSH
# Image CLASSIFICATION MODEL - DESCRIPTION 
This project focuses on building a CNN-based image classification model using the CIFAR-10 dataset, which contains 60,000 color images across 10 object categories. The data is preprocessed using tensor conversion and normalization to enhance training stability. The neural network is composed of three convolutional layers that extract visual patterns, followed by pooling layers to reduce spatial dimensions and two fully connected layers for classification. The model uses the ReLU activation function for non-linearity, the Adam optimizer for efficient parameter updates, and CrossEntropyLoss to measure prediction error. The model is trained for five epochs using mini-batches of 64 images, progressively learning feature representations that help in accurate classification. Once trained, the network is tested on unseen data to measure accuracy, demonstrating its ability to automatically recognize and categorize images into the correct class.
# Features
- Built using **PyTorch**
-  Uses **CIFAR-10 dataset**
-  Implements a **3-layer CNN architecture**
-  Includes **data preprocessing and normalization**
-  Trains using **Adam optimizer** and **CrossEntropyLoss**
-  Evaluates model performance with test accuracy
# Dataset
**CIFAR-10** dataset is automatically downloaded from `torchvision.datasets`.  
It includes:
- **Training set:** 50,000 images  
- **Test set:** 10,000 images  
- **Classes:** Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck
