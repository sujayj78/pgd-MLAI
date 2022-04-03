# Melanoma Detection with Neural Networks
In this assignment, you will build a **multiclass classification model using a custom convolutional neural network in TensorFlow.** 

## Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Understanding the Dataset
You can download the dataset [here](https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view)

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the **International Skin Imaging Collaboration (ISIC)**. All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Project Pipeline
- **Data Reading/Data Understanding**
- **Dataset Creation**
- **Dataset visualisation**
- **Model Building & training**
- **Chose an appropriate data augmentation strategy to resolve underfitting/overfitting**
- **Model Building & training on the augmented data**
- **Examine the current class distribution in the training dataset**
- **Handling class imbalances**
- **Model Building & training on the rectified class imbalance data**
