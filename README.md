#  Tomato Leaf Disease Identification using Deep Learning

##  Project Overview

This project focuses on identifying and classifying tomato leaf diseases using deep learning and image classification techniques.

The system takes an image of a tomato leaf as input and uses a trained deep learning model to predict its corresponding category.

##  Objective

The main objective of this project is to explore how deep learning can be applied to agricultural image classification and help identify tomato leaf diseases from images.

##  Dataset

- Total Images: ~18,700
- Number of Classes: 6
- Training Data: 80%
- Testing Data: 20%
- Input Image Size: 224 × 224 pixels

##  Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Deep Learning
- Convolutional Neural Networks (CNN)

##  Models

The project explored several pretrained architectures:

- ResNet50
- GoogLeNet
- SqueezeNet
- AlexNet

For the recorded training and evaluation experiment, **ResNet50 and GoogLeNet** were trained and compared using transfer learning.

##  Methodology

The basic workflow of the project is:

```text
Tomato Leaf Image
        ↓
Image Preprocessing
        ↓
Resize to 224 × 224
        ↓
Normalization
        ↓
Train/Test Split
        ↓
Pretrained Deep Learning Model
        ↓
Model Training
        ↓
Testing & Evaluation
        ↓
Disease/Class Prediction
