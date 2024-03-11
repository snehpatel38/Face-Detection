# OpenCV Face Detection

This project demonstrates real-time face detection using OpenCV's Haar cascade classifier.

## Installation

 - Install OpenCV if you haven't already:
   ```bash
   pip install opencv-python

## Usage

1. Run the face_detection.py script:
    ```bash
    python face_detection.py
2. Press 'q' to exit the program.

## Overview

1. Import the necessary libraries (cv2 for OpenCV).
2. Load the Haar cascade classifier XML file for face detection.
3. Initialize the camera (VideoCapture).
4. Continuously read frames from the camera.
5. Convert the frame to grayscale for better processing.
6. Detect faces in the grayscale frame using the detectMultiScale function.
7. Draw rectangles around the detected faces.
8. Display the frame with the rectangles using imshow.
9. Wait for a key press and check if it's 'q' to exit the loop.
10. Release the camera and close all OpenCV windows.

## Acknowledgements
 - The face detection algorithm uses OpenCV's Haar cascade classifier, which is based on the work of Viola and Jones.