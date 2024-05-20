# Melanoma Assignment
> Building a MultiClass Classification Model using a Custom Convolutional Neural Network in Tensorflow.
> The purpose of this project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background: This project is a part of PG Program in ML/AI from UPGRAD in collaboration with IIIT Bangalore.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion
- Brief Description of the model Built is as below:
  - Model 1 : Basic Sequential NN Model
  - Model 2 : Sequential NN Model with implementation of Data Augmentation without Dropout.
  - Model 3 : Sequential NN Model with implementation of Data Augmentation with Dropout.
  - Model 4 : Sequential NN Model having higher Neurons in each layer with implementation of Data Augmentation with Dropout.
  - Model 5 : Sequential NN Model after Class Rebalancing using Augmentor Library implemented with Dropout.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- No pre-trained model have been used. The models are custom build.
- Batch Size 32 have been used and images have been resized to 180 x 180 px.
- There are five custom models have been build in the notebook.
- Model 1: Shows a sign of Overfitting with high training but low validation accuracy.
- Model 2: Shows a sign of Underfitting with low accuracy and higher fluctuations in training/validation losses.
- Model 3: Also Shows a sign of Underfitting with low accuracy, but fluctuations in training/validation losses have been reduced by using Dropout Layer.
- Model 4: Shows increased fluctuations in Training/Validation Accuracy due to increased sensitivity of the model.
- Model 5: Shows promising results with good accuracy and validation accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used 
- Matplotlib - version 3.7.1
- Pandas - version 2.0.3
- Numpy - version 1.25.2
- Pathlib - version 1.0.1
- Augmentor - version 0.2.12
- Keras - version 2.15.0
- Tensorflow - version 2.15.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
I would like to sincerely thank upGrad Team and IIIT Bangalore for giving me this chance to indulge in this project.


## Contact
Created by [@abhivsh] - feel free to contact me!

<!-- You don't have to include all sections - just the one's relevant to your project -->
