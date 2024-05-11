# Melanoma Detection Assignment
> This project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- The CNN model is built using a dataset which consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
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
- However the class data was imbalanced. Augmentor was used to generate 500 images of each class so that some balance is achieved.



## Conclusions
- The model gave very good training accuracy after using Augmentor library.

- Augmentor was used to generate 500 images of each class so that class rebalance can be achieved.

- The model is still overfitting but the training and validation losses has  reduced and are less than 1%.

- The Model can be further improved by tuning the hyperparameters.


## Technologies Used
- Python 3.11.4


## Contact
Created by [@rmythili2] - feel free to contact me!