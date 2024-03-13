# Skin_Cancer_Detection_CNN
> Building a Convolutional Neural Network for the detection of skin cancer and its type.

## Table of Contents
* [Dataset Info](#dataset-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


## Dataset Information
- The dataset used for the model building consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC).
- The dataset contains 9 types of skin cancer images that include:
	['actinic keratosis', 'basal cell carcinoma', 'dermatofibroma', 'melanoma', 'nevus', 'pigmented benign keratosis', 'seborrheic keratosis', 'squamous cell carcinoma', 'vascular lesion']


## Conclusions
- Initial CNN model created was **Overfitting**.
- Using data augmentation techniques helped resolve the Overfitting, however the accuracy of the model drastically reduced.
- Using Augmenter to handle class imbalance helped improve the accuracy to over 82% with no evidence of Overfitting.
- It can be concluded that class rebalance improved the overall performance of the model



## Technologies Used
- TensorFlow - version 2.15.0
	* keras
- Numpy - version 1.25.2
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Augmentor - version 0.2.12
