🚗 Vehicle Tracking and Speed Estimation Using OpenCV
This repository contains the implementation of a Vehicle Tracking and Speed Estimation system using OpenCV and Python. The project leverages Computer Vision techniques to detect, track, and estimate the speed of vehicles in video feeds, with potential applications in traffic law enforcement and congestion management.

📖 Table of Contents
Overview
Features
Workflow
Usage
Results
Future Enhancements
📋 Overview
Traffic monitoring is a critical aspect of urban management, but manual methods are prone to errors and inefficiencies. This project automates the process using Computer Vision to deliver:

Accurate vehicle detection.
Real-time speed estimation.
Insights for smarter traffic management.
🌟 Features
Vehicle Detection: Uses background subtraction and contour detection to identify vehicles.
Real-Time Tracking: Assigns unique IDs to track vehicles across frames.
Speed Estimation: Calculates speed in km/h using pixel-to-meter conversion.
Preprocessing Pipeline: Implements grayscale conversion, Gaussian blur, and morphological transformations for noise reduction.
🛠️ Workflow
Video Input: Load a video feed or camera input.
Preprocessing: Grayscale conversion, Gaussian blur, and background subtraction.
Morphological Transformations: Dilate and close regions to refine detected objects.
Contour Detection: Identify vehicle boundaries.
Tracking: Assign unique IDs to vehicles and update positions.
Speed Estimation: Calculate speed using distance traveled over time.
Output: Display results with bounding boxes and speed annotations.
🚀 Usage
Simply replace the video file in the code with your desired input and run the script to initiate the vehicle detection and speed estimation. The results will be displayed with bounding boxes and speed annotations on the processed video frames.

📊 Results
Processing Speed: The system processes at ~15 FPS on standard hardware.
Speed Accuracy: The speed estimation has an accuracy of approximately 90%, depending on the calibration and quality of the video input.
Vehicle Count: The number of vehicles detected is dynamically displayed on the processed frames.
Real-Time Feedback: Bounding boxes are displayed around detected vehicles, and their speed is annotated in real-time.
