# Real-Time-Vehicle-Detection.-Tracking-and-Counting
Vehicle detection, tracking and counting with YOLOv8 and DeepSORT using OpenCV library in Python.

# Overview
This repository contains code for real-time vehicle detection, counting, and tracking using a modified dataset from Roboflow. The original dataset had 20 classes, which were narrowed down to 6 classes to focus on specific vehicle types based on categories.

# Features
Real-time Processing: The system performs vehicle detection, counting, and tracking in real-time, making it suitable for various purposes. Here we did the project for NITK vehicle tracking both IN and OUT.

Modified Dataset: The dataset used in this project is derived from Roboflow, initially consisting of 20 classes. For better specificity and relevance to the project goals, it was narrowed down to 6 classes, ensuring a more focused and accurate model.
https://universe.roboflow.com/tansam-uunrl/vehicle-detection-3

# Object Classes
Category 1: Car/Jeep/Van/MV
Category 2: LCV/LGV/Mini Bus
Category 3: 2 axle
Category 4: 3 axle Commercial
Category 5: 4 to 6 axle
Category 6: Oversized (7 axle).

# Model Architecture
The vehicle detection model is based on YOLOv8, trained on the modified dataset.

# Acknowledgments
The project was made possible by leveraging the Roboflow platform for dataset management and annotation.



