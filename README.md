# Melanoma-CNN-Prediction
> In this assignment, you will build a multiclass classification model using a custom convolutional neural network in tensorflow.

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

#### Project Pipeline
- Data Reading/Data Understanding → Defining the path for train and test images

- Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.

- Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset

- Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize     pixel values between (0,1).

- Choose an appropriate optimiser and loss function for model training

- Train the model for ~20 epochs

- Write your findings after the model fit, see if there is evidence of model overfit or underfit

- Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data :

--  Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

--  Choose an appropriate optimiser and loss function for model training

--  Train the model for ~20 epochs

--  Write your findings after the model fit, see if the earlier issue is resolved or not? **Class distribution: **

--  Examine the current class distribution in the training dataset

--  Which class has the least number of samples?

--  Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances:

--  Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data:

--  Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

--  Choose an appropriate optimiser and loss function for model training

--  Train the model for ~30 epochs

-- Write your findings after the model fit, see if the issues are resolved or not?

-- The model training may take time to train and hence you can use Google colab.

-- The data set contains the following diseases:

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
#### Analyze your results here. Did you get rid of underfitting/overfitting? Did class rebalance help?

- The class rebalance helped in reducing overfititng of the data and thus the loass is beng reduced But it reduced the Acurracy very low

- Initially we tried without the ImageDataGenerator which created data to over fit at high ratio

- Then we introduced dropout and ImageDataGenerator which reduced the over fit

- At last we tried Batch Normalization and Augumentation which really helped in carry forward

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
-library 1 -pandas

-library 2- matplotlib

-library 3- warnings

-library 4 -numpy

-library 5 -seaborn

-library 6- sklearn

-library 7-statsmodels

-library 8- tensorflow

-library 9- keras

-library 10- CNN

-library 11- Neural Network

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
This project is completed after successfully completing the Advance learning session module provided by IIITB & UpGrad .

## Contact
Created by [@PrakashShri] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
