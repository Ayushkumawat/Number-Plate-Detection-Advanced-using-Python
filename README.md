# Number-Plate-Detection-Advanced-using-Python
Number Plate Detection using Open CV and Machine Learning (TensorFlow). Live Video is processed using filters which makes this model more accurate results and the data of the vehicles are automatically updated in the Excel sheet.

# Benefits - 
We can use this model in identification of vehicles and maintaining their data base with time stamp. 

# Dataset for Training the model -
https://www.kaggle.com/datasets/andrewmvd/car-plate-detection

# How this model works -

Firstly live video is captured
Then some filters are applied for better detection and noise reduction

Like - at first it is converted into greyscale and then into outline filter for better recognition of shapes which then filtered as rectangle shapes
As numberplates are also in rectangular shapes, so identification becomes eassier.

Model is trained using the dataset which contains images of some random car showing numberplate and each image carry an seperate file which contains coordinates of numberplate in the image.

The live video captured is then send to the model to predict the location of numberplate
Then EasyOCR is used to get the characters from the numberplate.

Every numberplate detected is stored in a file and the data of vehicle gets updated in the csv file.

# This Project Uses:-
Language --> Python=3.8 
IDLE --> Jupyter Notebook
Operating System --> Windows 11
Camera for live detection

# Prerequisite Libraries

1. cv2
install using - pip install opencv-python
import using - import cv2

2. pyqt5 (for Image Labelling)
install using - pip install --upgrade pyqt5 lxml
import using - "import in labelling"

3. os
install using - "Usually pre-installed with python"
import using - import os

4. wget
install using - pip install wget
import using - import wget

5. tensorflow "Please check the version if error occurs"
install using - pip install tensorflow==2.4.1 --upgrade
import using - import tensorflow as tf

6. protobuf and matplotlib "Upgrade"
install using - pip install protobuf==3.19 matplotlib==3.2
import using - from matplotlib import pyplot as plt

7. object detection
install using - pip install object_detection
import using - import object_detection

8. easyocr
install using  - pip install easyocr
import using - import easyocr

9. uuid
install using - pip install uuid
import using - import uuid

10. numpy
install using - pip install numpy
import using - import numpy as np
