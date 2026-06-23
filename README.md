# DigitOne

High-Accuracy Single-Digit Recognition using CNN

## Overview

DigitOne is a deep learning project built using the MNIST handwritten digit dataset.

The objective is to accurately detect whether a handwritten digit is the digit 7 or not.

This project uses a Convolutional Neural Network (CNN) and binary classification to achieve high recognition accuracy.

## Dataset

* MNIST Handwritten Digits Dataset
* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 pixels

## Method

* Target Digit: 7
* Binary Classification:

  * 7 → Positive Class
  * Not 7 → Negative Class

Model Architecture:

* Conv2D
* MaxPooling2D
* Conv2D
* MaxPooling2D
* Flatten
* Dense
* Dense (Sigmoid Output)

## Results

* Training Accuracy: 99.92%
* Validation Accuracy: 99.77%
* Test Accuracy: 99.71%
* Custom Test Set Accuracy: 10/10 (100%)

## Files

* DigitOne.ipynb — Project notebook
* digitone_model.h5 — Trained CNN model
* training_accuracy.png — Training graph

## Author

Shritha Reddy


