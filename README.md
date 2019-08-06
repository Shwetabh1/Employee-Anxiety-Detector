<h1 align="center"> Employee Anxiety Detector </h1>

<div align="center">
    <img src="https://github.com/Shwetabh1/Employee-Anxiety-Detector/blob/master/Emotions.png" alt="Essential JavaScript" width="400" height="250"/>
  <br>
</div>


## What is this?
This project aims to display live emotions expressed.

## Table of Contents
1. Features
1. Technologies Used
1. Future Enhancements

## Introduction
1. Users need to run a python script `WebCam.py` and must grant it permission to use webcam.
1. Expression detection is a two step process. Face detection and then expression detection.
1. haar-cascade-classifiers has been used for face detection.
1. Once face is detected it is rescaled and chopped to 48 * 48 pixel size. and run against our trained model.
1. EMOTIONS = ['angry', 'disgusted', 'fearful','happy', 'sad', 'surprised', 'neutral']

## Technologies Used
1. Python
1. OpenCV
1. Keras
1. Tensorflow

## Future Enhancements
Given the short time frame this has a lot of scope for improvement. Listing down a few
1. Monitoring over a period of time and generating report off of it.
1. More rigorous training of the model.
1. Could have just used Tensorflow.

## Crew Members
1. Aastha Singhal
1. SandiPani
1. Shwetabh Shekhar

