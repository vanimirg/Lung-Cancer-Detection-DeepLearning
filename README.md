# Automatic Pulmonary Nodule Detection Using Convolution Neural Network and Transfer Learning

## Overview
This project focuses on the automatic detection of pulmonary nodules, which are indicators of lung cancer, using advanced deep learning techniques. Given the high mortality rate associated with lung cancer, early and accurate detection is crucial for improving patient outcomes. This study leverages Convolutional Neural Networks (CNN) and Transfer Learning to classify lung nodules in CT scan images as benign or malignant, thus aiding in the early diagnosis and treatment of lung cancer.

## Objectives
Develop CNN Models: Create traditional Convolutional Neural Network (CNN) models to classify lung nodules in CT scans.
Implement Transfer Learning: Utilize the VGG16 architecture, a pre-trained deep learning model, to enhance the accuracy of lung nodule classification.
Compare Models: Evaluate and compare the performance of traditional CNN models with the VGG16 transfer learning model to determine the most effective approach for nodule classification.
Dataset
The study uses data from the Lung Image Database Consortium Image Collection (LIDC-IDRI), which includes CT scans evaluated by radiologists. Additional data is sourced from the LUNA16 Challenge and the Kaggle Data Science Bowl 2017, providing pre-processed and segmented images of lung nodules.

### Methodology
Data Preprocessing: Standardize and augment the CT scan images to improve model accuracy and generalization.
Model Development: Build and train multiple CNN models with varying architectures, employing techniques like normalization, pooling, and dropout.
Transfer Learning: Apply the VGG16 pre-trained model, adapting it to the lung nodule classification task.
Model Evaluation: Assess model performance based on accuracy and loss metrics, using separate training and validation datasets.
## Key Findings
The best-performing traditional CNN model achieved an accuracy of 95.297%, demonstrating its capability to accurately distinguish between benign and malignant nodules. The VGG16 transfer learning model, while effective, showed slightly lower performance compared to the traditional CNN models, highlighting the importance of tailored model architecture for specific medical image analysis tasks.
