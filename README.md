# Melanoma Detection Project
> In this project, a multiclass classification model using a custom convolutional neural network in TensorFlow is built.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
>To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
>A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
>The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

### The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Conclusions
- Initially using 20 epochs, the model overfitted as the error in validation increased after a steep decrease, as the no of epochs increased.
-Then, using dropouts and augmentation, we solved the problem of overfitting was solved partially, but it can be further solved by adding more layers, neurons, and hyperparameters o the model.

## Technologies Used
- tensorflow
- pandas
- numpy
- seaborn
- matplotlib
