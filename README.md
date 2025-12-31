# Real-Time Object Recognition 🕵️‍♂️📹

## 📌 Project Overview
This project performs real-time object recognition using a pre-trained MobileNetSSD model. It captures video input from a webcam and detects various objects using the MobileNet Single Shot Detector (SSD) architecture. The system draws bounding boxes and class labels around objects it recognizes in real time. 

## 🛠 Tools & Technologies
   - Python
   - OpenCV (opencv-python) for video capture and display
   - Pre-trained MobileNetSSD model (Caffe framework) 

## 📈 Key Features
  -  Load pre-trained MobileNetSSD network
  -  Capture webcam or video feed
  -  Detect objects in real time
  -  Draw bounding boxes and labels on detected objects
  -  Fast and efficient inference using SSD architecture 

## 📂 Model Files
The system uses these files:
   - MobileNetSSD_deploy.prototxt — model architecture
   - MobileNetSSD_deploy.caffemodel — pre-trained weights 

## 🎯 Goal
Understand how to use a pre-trained deep learning model for real-time object detection and visually identify objects from a live video stream.

## 🚀 How to Run
  1.Install dependencies:
     - pip install opencv-python
  2.Make sure you have the MobileNetSSD model files (.prototxt and .caffemodel) in your project directory. 
  3.Run the script:
   - python object_detection.py
  4.Press q to quit the application.

## 📌 Learning Outcome
 -  Gained practical experience with real-time computer vision
 -  Used MobileNetSSD pre-trained model for object detection
 -  Learned how to integrate deep learning with OpenCV video feeds
