﻿# Driver Drowsiness Detection

A mobile application aimed at improving road safety by detecting driver drowsiness. Built using Flutter and Dart, this application integrates a machine learning model trained with a Convolutional Neural Network (CNN) using TensorFlow Lite for real-time performance on mobile devices.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Technologies Used](#technologies-used)
- [Demo](#Demo)


## Introduction

Driver Drowsiness Detection is an innovative solution to help prevent accidents caused by driver fatigue. By analyzing real-time video feeds from the driver's device, the application can determine whether the driver is drowsy or alert and notify them accordingly.

## Features

- Real-time driver drowsiness detection
- High accuracy model trained using CNN
- Seamless integration with TensorFlow Lite for mobile optimization
- User-friendly interface with clear notifications
- Supports multiple devices

## Screenshots

### Welcome Screen


<img src="screenshots/welcome_screen.jpg" alt="Welcome Screen" width="300">

### Driver Detection Screens(Eyes closed and opened)

<img src="screenshots/Eye_opened.jpg" alt="Driver Alert" width="300">

<img src="screenshots/Eye_closed.jpg" alt="Driver Drowsy" width="300">

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/driver-drowsiness-detection.git
## usage
1.Connect your mobile device or start an emulator.

2.Run the application:
  ```bash
 flutter run
```
##    Model Training
The machine learning model was trained using a Convolutional Neural Network (CNN) with the following steps:

1.Data Collection: Gathered a dataset of images of drivers in alert and drowsy states.

2.Preprocessing: Cleaned and labeled the dataset.

3.Training: Used TensorFlow to train the CNN model.

4.Conversion: Converted the trained model to TensorFlow Lite format for mobile integration.


## Technologies Used

-Flutter: For building the cross-platform mobile application.

-Dart: Programming language used for Flutter.

-TensorFlow Lite: For integrating the machine learning model into the mobile application.

-CNN: Convolutional Neural Network algorithm for training the model.

-UI/UX Design: Custom designs for a user-friendly interface.

## Demo

there's a demo video and linkedin post 

https://www.linkedin.com/posts/abdelrhman-tarek-042231173_graduationproject-flutter-machinelearning-activity-7211960542716960768-jsyl?utm_source=share&utm_medium=member_desktop
