 COMPANY : CODTECH IT SOLUTIONS

NAME : Dharmapuri Madhura Sree

INTERN ID : CT06DF2223

DOMAIN : MACHINE LEARNING

DURATION : 6 WEEKS

MENTOR : NEELA SANTHOSH KUMAR

Task 3 – CNN Image Classification with Fashion MNIST
 
## About the Project

This project focuses on building a Convolutional Neural Network (CNN) using PyTorch to classify images from the Fashion MNIST dataset. The model is trained to identify 10 categories of clothing items (like shirts, shoes, and bags) based on 28×28 grayscale images.

The model is also capable of predicting labels for custom grayscale images, and displays the predicted output as a single character/class label (e.g., T-shirt = “T”).

This task is developed as part of the Machine Learning Internship by CodTech IT Solutions, demonstrating deep learning concepts in real-world image classification.

## Objectives
Train a CNN model to classify Fashion MNIST images into 10 categories

Apply data preprocessing including normalization, random cropping, and horizontal flipping

Evaluate model performance using accuracy and loss curves

Load and predict custom 28×28 grayscale input images

Display predicted output with visual confirmation

## Dataset Description

Dataset: Fashion MNIST

Source: torchvision.datasets.FashionMNIST

Format: 28x28 grayscale images

Categories:
['T-shirt/top', 'Trouser', 'Pullover', 'Dress', 'Coat',
 'Sandal', 'Shirt', 'Sneaker', 'Bag', 'Ankle boot']
 
Automatic Download: Handled by PyTorch during training

Prediction Output: Returns the class label for input image (e.g., "Sneaker")

## Key Features

✅ Load and preprocess dataset with augmentation

✅ Define a custom CNN architecture with 3 convolutional layers

✅ Train for 10 epochs using Adam optimizer

✅ Plot and visualize accuracy and loss over epochs

✅ Load custom .png images, resize to 28×28, and predict using the trained model

✅ Display image and predicted label using matplotlib

## Libraries Used

torch	Deep learning framework

torchvision	Load datasets and image transforms

PIL	Image loading and conversion

matplotlib	Accuracy/loss and prediction plots

seaborn	Visual enhancements (optional)

## output:

![Image](https://github.com/user-attachments/assets/bef158fd-d971-4a9f-99c9-d0645f60355e)

![Image](https://github.com/user-attachments/assets/2c598673-b7af-40b0-b520-beaca4d1bbef)

