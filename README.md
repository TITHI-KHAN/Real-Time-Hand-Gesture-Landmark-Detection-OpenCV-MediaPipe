# Real-Time-Hand-Gesture-Landmark-Detection-OpenCV-MediaPipe

## To run the code, please either use "Visual Studio" or "Jupyter Notebook from Anaconda Navigator".

This Python script utilizes the MediaPipe library to detect and visualize hand landmarks in real-time video captured from a webcam using OpenCV.

The script begins by importing the necessary libraries: `cv2` for OpenCV and `mediapipe` for hand detection. It sets up MediaPipe components for hand detection and initializes webcam capture.

Within the main loop, the script reads frames from the webcam and processes them using the MediaPipe hands module. Detected hand landmarks are then overlaid on the video frames. The script continues to display the processed frames until the user exits by pressing the ESC key.

Finally, it releases the webcam and closes all OpenCV windows.

This script provides a basic setup for real-time hand landmark detection and visualization, making it a useful starting point for various applications such as gesture recognition, sign language translation, and virtual hand control interfaces.
