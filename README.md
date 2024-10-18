# Face-Mask-Detection-Model
A deep learning model designed to detect whether individuals in real time are wearing face masks. This project uses a convolutional neural network (CNN) to classify frames(in vedio) as either "Mask" or "No Mask".

## Table of Contents
- Project Overview
- Features
- Dataset
- Model Architecture
- Usage
- Results
- Future Improvements



## Project Overview
The Mask Detection Model is trained on a dataset containing images of individuals with and without masks. The model aims to assist in automating mask compliance monitoring in images or real-time video feeds. By identifying mask-wearing, this model can contribute to public health efforts during pandemic times.

## Features
- Binary Classification: Classifies images into "Mask" or "No Mask" categories.
- Customizable: Can be extended to include additional classes, such as "Incorrectly Worn Mask."
- Real-time Detection: Supports deployment for real-time video stream mask detection (e.g., through OpenCV).

## Dataset
The dataset should contain images with two categories:

Mask: Images of individuals wearing masks.
No Mask: Images of individuals not wearing masks.
Datasets can be found or created from sources like Kaggle’s Face Mask Detection Dataset.
# Dataset Link : https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

Organize images into folders (data/mask and data/no_mask) within a main data directory.
Ensure you have a roughly balanced number of images for each class.

## Model Architecture
This project uses a convolutional neural network (CNN) based on popular architectures like MobileNet or ResNet for efficient image classification. The model is configurable, allowing you to experiment with different architectures to improve accuracy.

## Usage
1. Running Predictions on a Test Image
2. Real-Time Detection with Webcam

## Results
Accuracy: Achieved ~94.6% accuracy on validation data.


## Future Improvements
- Add additional classes for "Incorrectly Worn Mask."
- Fine-tune the model on larger datasets for improved accuracy.


