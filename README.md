# Mobile Image Classification App with MobileNetV2 and Flutter
## Introduction
This repository contains the code for a mobile image classification app developed as part of a university assignment. The app uses the MobileNetV2 pre-trained model and a dataset sourced from Kaggle to perform image classification. The app is built using the Flutter framework and is designed to be deployed on Android devices.

## Dataset
The image dataset used to train the MobileNetV2 model was obtained from Kaggle. The "Batik Data Set" consists of labeled images of various batik patterns. The dataset is organized into different classes representing different types of batik designs. Before training the model, the dataset was preprocessed, including resizing, normalization, and data augmentation, to enhance the model's performance.

Dataset Source: [Batik Data Set on Kaggle](https://www.kaggle.com/datasets/isaacbernadus/batik-data-set)

## Installation
To run the app, follow these steps:

Clone this repository to your local machine.
Make sure you have Flutter installed and set up on your system.
Install the necessary dependencies by running flutter pub get in the project directory.
Connect your Android device or use an emulator for testing.
Run the app using the flutter run command.
Dataset
The image dataset used to train the MobileNetV2 model was obtained from Kaggle (provide Kaggle dataset link here). The dataset consists of labeled images belonging to different classes. The dataset was preprocessed before training, including resizing, normalization, and data augmentation to improve the model's performance.

## Model Training
The MobileNetV2 model was used as a starting point, and it was fine-tuned with the Kaggle dataset to adapt it to our specific image classification task. The training process involved using transfer learning to retain the model's general knowledge while fine-tuning it to recognize the classes in our dataset.