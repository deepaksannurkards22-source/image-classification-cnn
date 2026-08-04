# Image ClassificationnCNN

## Overview
Designed and trained a Convolutional Neural Network to classify 
handwritten digits, as part of a guided Data Science & AI project.

## Dataset
MNIST dataset — 60,000 training images and 10,000 test images of 
handwritten digits (0-9), 28x28 grayscale.

## Approach
- Normalized pixel values (0-1 range) and reshaped images for CNN input
- Applied data augmentation (random rotation, random zoom) to improve 
  generalization
- Built a CNN with 3 convolutional blocks (Conv2D + BatchNormalization 
  + MaxPooling), followed by a dense classifier head with Dropout
- Used EarlyStopping and ReduceLROnPlateau callbacks during training
- Saved the trained model and built a prediction function for 
  classifying new custom images

## Results
Achieved ~99.4% validation accuracy on digit classification.

## Tools Used
Python, TensorFlow/Keras, NumPy, Matplotlib, PIL

## Note
This was completed as a guided project during my Data Science & AI 
program (Intellipaat, in collaboration with IIT Roorkee).
