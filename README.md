# Plates v2: Image Classification Competition

## Overview
The Plates v2 competition challenges participants to classify images of plates into two categories: *Clean* or *Dirty*. This task is crucial for applications in automated systems, such as in the hospitality and food service industries, where accurate and timely classification of dishes could streamline operations.

In this competition, you're tasked with building models to predict whether a plate in an image is clean or dirty based on a given dataset of plate images.

## Objective
The goal of the competition is to classify the provided plate images into two classes:
- **Clean**
- **Dirty**

Using techniques like Convolutional Neural Networks (CNNs), Transfer Learning, and Data Augmentation, participants must submit their best-performing models to achieve high classification accuracy.

## Dataset
The dataset includes thousands of labeled images of plates, which you can use to train your model. The training set consists of images labeled as *Clean* or *Dirty*, and the test set has similar images but without labels.

You can download the dataset directly from the [Kaggle Plates v2 Competition Page](https://www.kaggle.com/competitions/platesv2/overview).

## Approach
For this competition, you may utilize various techniques such as:
- **Transfer Learning with MobileNetV2:** This model, pretrained on ImageNet, is suitable for tasks requiring fast and lightweight predictions. It provides a strong baseline for the classification task with minimal computational resources.
- **DINOv2:** Another approach involves the self-supervised method, which can fine-tune visual representations without labeled data, providing more generalized features for classification tasks.

Both models are great candidates for tackling the binary classification task, and combining them with techniques like data augmentation and ensemble methods can lead to even better results.

## Evaluation
Submissions are evaluated based on **Accuracy**, which is the percentage of correct predictions over the total predictions made.
