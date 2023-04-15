# CNN- Melanoma Skin Cancer Detection Assignment

![alt text](https://github.com/kalpeshvarankar//raw/CNN-Melanoma_Skin_Cancer_Detection./Diaplay/CNNgif.gif)

## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]
* [Acknowledgements]

## General Information

- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. Goal is to To build a custom (Without transfer learning )CNN based model which can accurately detect melanoma. Dataset: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The Base model was built without any Batch normalization and dropouts. Difference between train and validation accuracy was very high. This model was overfitting.
- Then we observed high class imbalance in the Model, as the cause of overfitting. Augmentation strategy was used to rectify the problem. And second model was built with dropout layer. Training accuracy was not good but overfitting problem has been rectified with this model.
- We used the augmentor to generate balanced train data for all classes.
- Class imbalance problem was rectified and third model was built which gave Training and Validation accuracies as 95.09% and 81.59% respectively.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python, Pandas, Numpy, Matplotlib, PathLib, TensorFlow, Keras, Glob, Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@kalpeshvarankar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
