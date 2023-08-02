# Breast Cancer Detection Project

## Scenario:

The objective of this project is to build a breast cancer detection system on CNNs. The system will be trained on a dataset of breast tissue images that have been labeled as either benign or malignant. The system will then be able to classify new breast tissue images as either benign or malignant.

## Project Objective:

In this project, we will be using several deep learning architecture models on the image data set we have, and check whether the patient has IDC or not. The accuracy of this project is essential due to the fact that false negatives will lead to the patients further worsening of the condition and even death in some cases.

- Archive.zip: 
The whole image file has 162 whole mount slide images taken at 40x.  
There are 277,524 patch images with a size of 50 x 50 extracted from the entire image.  
Of these, 198,738 are IDC negative and 78,786 are IDC positive.  
The patient ID, class (0: non-IDC, 1: IDC), location path of the image file, x coordinate, y coordinate are collected from the patch image file and stored.  
(※ Due to the large capacity to use all the data, only a portion was used.)  

See the original site below for more details.  
https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images

- EDA_200968045: Involves the exploratory data analysis of the dataset. Comparing IDC vs Non IDC patches as well as visualisng the whole slice image
- IDC_Model1_200968045: The CNN part of EfficientNetB2 is used with ReLu and Sigmoid activation functions being used in the first and last layers respectively
- IDC_Model2_200968045: Uses a sequential model ReLu and Sigmoid activation functions as well
