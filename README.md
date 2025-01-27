# Driver-Drowsiness-Detection-CNN
A real-time driver drowsiness detection system using Convolutional Neural Networks (CNN) and OpenCV. The system monitors driver's eye movements through a webcam to detect signs of drowsiness and alerts the driver to prevent accidents.

Driver Drowsiness Detection System
Overview
This project implements a real-time driver drowsiness detection system using Convolutional Neural Networks (CNN) and OpenCV. The system monitors driver's eye movements through a webcam to detect signs of drowsiness and alerts the driver to prevent accidents. According to statistics, driver drowsiness is a major cause of accidents, making reliable detection systems crucial for road safety.
Features

Real-time face and eye detection using Haar Cascade Classifier
CNN-based eye state classification (Open/Closed)
Drowsiness detection based on continuous eye closure monitoring
Alert system to warn drowsy drivers
Efficient and lightweight model suitable for devices with low computational power

Technical Architecture
The system consists of four main components:

Image Preprocessing
Face and Eye Detection using OpenCV
CNN Model for Eye State Classification
Drowsiness Detection and Alert System

Requirements

Python 3.7+
OpenCV
TensorFlow/Keras
Numpy
Anaconda (recommended)

Installation

Clone the repository:

bashCopygit clone https://github.com/Jothikumaran08/Driver-Drowsiness-Detection-CNN.git
cd Driver-Drowsiness-Detection-CNN

Create and activate conda environment:

bashCopyconda create -n drowsiness_detection python=3.7
conda activate drowsiness_detection

Install required packages:

bashCopypip install -r requirements.txt
Usage

Run the main detection script:

bashCopypython drowsiness_detection.py

Position yourself in front of the webcam
The system will monitor your eye movements in real-time
An alert will be triggered if signs of drowsiness are detected

Model Architecture
The CNN model consists of the following layers:

Convolutional layers for feature extraction
ReLU activation functions
Max pooling layers
Dropout layers for preventing overfitting
Fully connected layers for classification

Dataset
The model is trained on a custom dataset containing:

Images of open and closed eyes
Different lighting conditions
Various head positions
Multiple subjects

Performance

Real-time processing capability
High accuracy in eye state classification
Low false positive rate
Efficient resource utilization

Contributing

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

Future Improvements

Integration with vehicle systems
Support for night-time detection
Mobile application development
Additional drowsiness indicators (yawning, head pose)
