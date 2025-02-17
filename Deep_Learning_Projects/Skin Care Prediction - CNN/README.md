# Project Name
Skin Cancer Detection with Convolutional Neural Network

## General Information
- Provide general information about your project here.
In this assignment, you will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 

- What is the background of your project?
To build a CNN based model which can accurately detect melanoma. 

- What is the business probem that your project is trying to solve?
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate 
images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging
Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number 
of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion



## Conclusions

Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library. 
Model Building & training on the rectified class imbalance data : Create a CNN model, which can accurately detect 9 classes present in the dataset. 
While building the model rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser and loss function for model 
training Train the model for 30 epochs


## Technologies Used

TensorFlow Version: 2.18.0
Keras Version: 3.8.0
Matplotlib Version: 3.10.0
NumPy Version: 1.26.4
Pandas Version: 2.2.2
PIL Version: 11.1.0


## Acknowledgements
Give credit here.
- This project was inspired by UpGrad Faculty, Guest faculty and study material in websites.


## Contact
Created by [Sanyamkumar9999] - feel free to contact me!