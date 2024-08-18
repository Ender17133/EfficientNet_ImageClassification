# Neural Network Image Classification
- Given project has 1 main objective:

    Predicting whether patient has an Alzheimer's disease (binary output: 1-Has Alzheimer's, 0 - Doesn't havae Alzheimer's)
-----------------------------------------------------------------------
All data will be divided into 2 specific classes:

1) Not demented brain MRI pictures

2) Demented brain MRI pictures

----------------------------------------------------------------------
You can access the data set in this [link](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset/code)

----------------------------------------------------------------------
Models that are going to be used and tested:

EfficientNet is a relatively young neural network architecture which has a unique feature - "**compound scaling**". EfficientNet systematically scales models dimensions, such as width, depth, and resolution which boosts efficiency without compromising accuracy. That's why I decided to test this model.

1) EfficientNetV2B0 (Baseline model)

2) EfficientNetV2S (Small) - A larger EfficientNet model with higher number of parameters and ability to catch patterns of the data.

All computations were made on Google Collab's TPUv2
