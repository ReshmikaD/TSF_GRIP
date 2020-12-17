# Physical-Distancing-Tracker

# Description

In addition to everyday steps to prevent COVID-19, maintaining physical distance between one another is one of the
best tools to avoid being exposed to this virus and slowing its spread across the globe.
But, surveillance for social distancing in public places is a challenging task.

This project will detect if people are following physical/social distancing and will send an alert if not. 

# Real-Time Object Detection

The module is built using pretrained YOLO model on COCO dataset with Opencv.
YOLOv3 is the latest variant of a popular object detection algorithm YOLO – You Only Look Once.

The run the algorithm we need three files:

1. Weight file: yolov3.weights

2. Cfg file: yolov3.cfg

3. Name files: coco.names

To download the YOLOv3 weights you can use these commands in command line:

    pip install wget
    
    wget https://pjreddie.com/media/files/yolov3.weights

# Model

1. Clone this repository

2. Install the required libraries

3. Download yolov3.weights :  https://pjreddie.com/media/files/yolov3.weights

4. Run SocialDistanceTracker.ipynb file in Jupyter Notebook

# Output Sample

![image](https://user-images.githubusercontent.com/54103472/82057150-8e274380-96e0-11ea-9e12-985428bf9dc1.png)
