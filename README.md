# Melanoma Detection Assignment
> Build CNN Model to detect melanoma, a type of skin cancer


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information

### Problem Statement:
Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

### About the dataset:
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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

### Project Pipeline:
1. Data Reading/Data Understanding
2. Dataset Creation
3. Dataset visualisation 
4. Model Building & training
5. Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
6. Model Building & training on the augmented data
7. Class distribution
8. Handling class imbalance
9. Model Building & training on the rectified class imbalance data

## Conclusions
- Base Model without any data augmentation nor class imbalance handling was heavily overfitting the dataset
- Model 2 with data augmentation layers overcame overfitting but was underfitting
- Model 3 with rectified class imbalance seems to be a good fit


## Technologies Used
- pandas - version 1.3.5
- tensorflow - version 2.8.2
- numpy - version 1.21.6
- matplotlib - version 3.2.2



## Contact
Created by [@SathishKumarRamasamy](https://github.com/SathishKumarRamasamy) - feel free to contact me!
