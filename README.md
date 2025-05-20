# traffic_flow_detection

Traffic Flow Analysis and Emergency Vehicle Detection

Overview

This project implements a real-time traffic flow analysis system to count vehicles and identify emergency vehicles (fire trucks and ambulances) using YOLO-based object detection. The system is designed for smart traffic signal applications, enabling intelligent traffic management by prioritizing emergency vehicles. It supports both YOLOv8 and a custom YOLOE model for enhanced segmentation and detection.

The code uses OpenCV for video processing, Ultralytics YOLO for object detection, and PyTorch for GPU acceleration (optional). The system processes video input, detects vehicles, and displays counts for general vehicles, ambulances, and fire trucks, along with real-time FPS.

Features
* Vehicle Detection and Counting: Identifies and counts vehicles (e.g., cars, buses, trucks) in video streams.
* Emergency Vehicle Recognition: Detects ambulances and fire trucks for prioritized traffic signal control.
* GPU Support: Optional CUDA acceleration for faster processing.
* Video Output: Option to save processed video with detection overlays.
* Real-Time FPS Display: Tracks and displays frames per second (excluding the first 10 frames for stability).

Requirements
* Python 3.8+
* OpenCV (cv2)
* NumPy
* Ultralytics YOLO
* PyTorch (for GPU support)
* CUDA (optional, for GPU acceleration)
