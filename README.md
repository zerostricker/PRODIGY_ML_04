# PRODIGY_ML_04

# Hand Gesture Recognition Model

## Intoduction
This repository contains the implementation of a hand gesture recognition model using Convolutional Neural Networks (CNNs). The model is trained to identify and classify different hand gestures, enabling intuitive human-computer interaction and gesture-based control systems.

# Dataset
- **Name:** LeapGestRecog
- **Source:** [Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog)
- **Description:** The dataset includes 40,222 images of different hand gestures categorized into 10 classes, providing a robust foundation for training and testing.

## Model Overview

The model architecture leverages Convolutional Neural Networks (CNNs) for feature extraction and classification, with the following components:

- **Convolutional Layers:** To extract spatial features from images.
- **MaxPooling Layers:** To reduce the dimensionality of the feature maps.
- **Dense Layers:** To perform the classification.
- **Softmax Layer:** For multi-class output.

## Training Details

- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Metrics:** Accuracy
- **Epochs:** 10
- **Batch Size:** Dependent on available system memory and GPU.

## Results

- **Test Accuracy:** 99.90%
- **Test Loss:** 0.0049

The model achieves high accuracy in recognizing and classifying hand gestures, demonstrating its effectiveness for gesture-based control systems.

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- Scikit-learn
