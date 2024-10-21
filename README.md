# Food Calorie Estimation using Image Classification

This project implements an image classification model to estimate calorie content in food items. The main goal is to create an application that makes it easier for individuals to calculate and monitor their calorie intake.

## Project Overview

- **Model**: MobileNetV2 (pretrained)
- **Dataset**: Combination of couple of datasets, totaling 4800 images (96 classes)
- **Training Set**: 3840 images
- **Image Dimension**: 224x224

## Model Selection

I experimented with several Transfer Learning approaches using pre-trained models:

1. MobileNetV2
2. ResNet50
3. InceptionV3

After evaluation, MobileNetV2 was chosen as it provided the highest accuracy for our specific use case.

## Features

- Image classification of food items
- Calorie estimation per serving
- User-friendly interface for easy calorie tracking

## How It Works

1. The user uploads an image of a food item
2. The model classifies the food item using the trained MobileNetV2 model
3. Based on the classification, the app provides an estimate of calories per serving

## Purpose

This project aims to help individuals who are concerned about their calorie intake. By providing quick and easy calorie estimations for various food items, users can make informed decisions about their diet and maintain their desired calorie intake levels.

## Future Improvements

- Expand the dataset to include a wider variety of food items
- Implement user feedback to improve calorie estimations
- Develop mobile applications for easier access
