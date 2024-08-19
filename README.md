[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Ender17133/EfficientNet_ImageClassification/blob/main/EfficientNet%20-%20Image_Classification.ipynb)
[![Open Presentation](https://img.shields.io/badge/Open%20Presentation-Google%20Slides-brightgreen?logo=google-slides)](https://github.com/Ender17133/EfficientNet_ImageClassification/blob/main/EfficientNet_Image_Classification.pptx)

# Neural Network Image Classification

# Objective: Predicting whether patient has the Alzheimer's disease (binary output: 1 - has Alzheimer's, 0 - doesn't have Alzheimer's)

## Data Used: [link](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset/code)
**Source: Kaggle**

**Device/s used: Google TPUv2**

Alzheimer MRI Preprocessed Dataset (128 x 128)

The Data is collected from several websites/hospitals/public repositories.
The Dataset is consists of Preprocessed MRI (Magnetic Resonance Imaging) Images.
All the images are resized into 128 x 128 pixels.
The Dataset has four classes of images.
The Dataset is consists of total 6400 MRI images.
Class - 1: Mild Demented (896 images)
Class - 2: Moderate Demented (64 images)
Class - 3: Non Demented (3200 images)
Class - 4: Very Mild Demented (2240 images).

For the purpose of the project, data will be divided into 2 specific classes:

1) Not demented brain MRI pictures

2) Demented brain MRI pictures

Models that are going to be used and tested:

EfficientNet is a relatively young neural network architecture which has a unique feature - "**compound scaling**". EfficientNet systematically scales models dimensions, such as width, depth, and resolution which boosts efficiency without compromising accuracy. That's why I decided to test this model.

1) EfficientNetV2B0 (Baseline model).

2) EfficientNetV2S (Small) - A larger EfficientNet model with higher number of parameters and ability to catch patterns of the data.
