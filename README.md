# Melanoma-CNN-Prediction

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#TechnologiesUsed)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
  
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- To build a CNN based model which can accurately detect melanoma
  
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions
- Conclusion 1 : Model without Normaalization, Dropouts and less no of conv layer ( a simple model ) accuracy - 70% , val accuracy - 38% (overfitting)
- Conclusion 2 : Model with data augmentation , accuracy - 42% , val accuracy - 42% ( accuracy dropped )
- Conclusion 3 : Model with Augmentor ( handled Imbalance in the data ), accuracy - 97% , val accuracy - 88%


## TechnologiesUsed
- library - TensorFlow v2.13.0
- library - Python 3.10
- library - Keras 2.13
- library - Matplotlib


## Acknowledgements
Give credit here.
- This project was Inspired by kaggle 
- References : Tensorflow Documentation
- This project was based on Tensorflow Documentation and a sample project Illustration.


## Contact
Created by [@ashish097] - feel free to contact me!

<!-- This project is open source and available under the [... License](). -->
