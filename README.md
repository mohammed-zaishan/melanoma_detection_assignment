# Melanoma-Detection-using-custom-cnn
>
> This project uses a custom CNN to detect melanoma in images among 9 classes. The model predicts with 90% accuracy.

## Table of Contents

- [Melanoma-Detection-using-using-custom-cnn](#melanoma-detection-assignment-using-custom-cnn)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
    - [Algorithms Used](#algorithms-used)
    - [Dataset Information](#dataset-information)
  - [Steps Involved](#steps-involved)
  - [Results](#results)
    - [Baseline Model](#baseline-model)
    - [Augmented Model](#augmented-model)
    - [Final Model](#final-model)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Algorithms Used

Convolutional Neural Network

### Dataset Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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

## Steps Involved

- Data Loading
- Baseline Model Building
- Training the Model and testing the model
- Building an augmented model
- Training the augmented model and testing the model
- Countering Class Imbalance with augmentor
- Building the final model
- Training the final model and testing the model
- Verifying the model

## Results

### Baseline Model

Accuracy and Loss charts for the baseline model
![image](https://github.com/user-attachments/assets/847ae9fc-89bc-41f0-b693-994ec568de7c)


### Augmented Model

Accuracy and Loss charts for the augmented model
![image](https://github.com/user-attachments/assets/da5ede88-752f-4b4e-9648-d1172af23f24)


### Final Model

Accuracy and Loss charts for the final model

![image](https://github.com/user-attachments/assets/894d9b4a-f6fe-430b-8c0e-8c15a7f023f0)


# Conclusion

As the accuracy of the model increases, the loss decreases. The final model has an accuracy of 90% and a loss of 0.4 . The model is able to predict the class with a high accuracy.
Augmenting the data and countering class imbalance helped in improving the accuracy of the model.

# Technologies Used

- Python
- Tensorflow
- Keras
- Augmentor
- Matplotlib
- NumPy

# Contact

Created by [@mohammed-zaishan] - feel free to contact me!

