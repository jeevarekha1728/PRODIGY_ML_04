# Hand Gesture Recognition using Leap Motion Sensor

This project implements a hand gesture recognition system using a deep learning model. The goal is to accurately classify different hand gestures from near-infrared images acquired by the Leap Motion sensor. The project uses a Kaggle dataset and is designed to run in Google Colab.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Training](#training)

## Introduction

Hand gesture recognition is a crucial task in human-computer interaction, enabling intuitive control of devices and applications. This project aims to classify different hand gestures using near-infrared images captured by the Leap Motion sensor and processed through a deep learning model.

## Dataset
The dataset used in this project is sourced from Kaggle. You can download it from the following link:

https://www.kaggle.com/datasets/gti-upm/leapgestrecog

After downloading the dataset, upload the images to the Google Colab environment.

## Preprocessing
Before training the model, the data needs to be preprocessed. This includes:

- Resizing images to a consistent size
- Normalizing pixel values
- Splitting the data into training and testing sets
- Data augmentation (if necessary)

## Training
The deep learning model is trained using the preprocessed images. The training process is implemented in the file. Key steps include:

- Loading and preprocessing the dataset
- Defining the model architecture (e.g., Convolutional Neural Network)
- Compiling the model with appropriate loss function and optimizer
- Training the model
- Saving the trained model
