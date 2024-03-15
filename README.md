# Real-Time-Hand-Gesture-Landmark-Detection-OpenCV-MediaPipe

## To run the code, please either use "Visual Studio" or "Jupyter Notebook from Anaconda Navigator".

### For the project video, please check the "Project Video" file. Thank you.

![1_1](https://github.com/TITHI-KHAN/Real-Time-Hand-Gesture-Landmark-Detection-OpenCV-MediaPipe/assets/65033964/9781d2bf-f266-48db-aab5-3ecf1e58da54)

![1_2](https://github.com/TITHI-KHAN/Real-Time-Hand-Gesture-Landmark-Detection-OpenCV-MediaPipe/assets/65033964/d9c17745-ce09-46c1-98e8-91dc22a248b6)

![1_3](https://github.com/TITHI-KHAN/Real-Time-Hand-Gesture-Landmark-Detection-OpenCV-MediaPipe/assets/65033964/6f98487e-cdf9-4fdf-8172-070ceb47292b)

![1_4](https://github.com/TITHI-KHAN/Real-Time-Hand-Gesture-Landmark-Detection-OpenCV-MediaPipe/assets/65033964/180bfa81-923b-4a36-a15f-1d8d9a13ab16)

![1_5](https://github.com/TITHI-KHAN/Real-Time-Hand-Gesture-Landmark-Detection-OpenCV-MediaPipe/assets/65033964/a1c9d6a4-5ae7-4872-a9f4-ff2df5f8c56c)

This Python script utilizes the MediaPipe library to detect and visualize hand landmarks in real-time video captured from a webcam using OpenCV.

The script begins by importing the necessary libraries: `cv2` for OpenCV and `mediapipe` for hand detection. It sets up MediaPipe components for hand detection and initializes webcam capture.

Within the main loop, the script reads frames from the webcam and processes them using the MediaPipe hands module. Detected hand landmarks are then overlaid on the video frames. The script continues to display the processed frames until the user exits by pressing the ESC key.

Finally, it releases the webcam and closes all OpenCV windows.

This script provides a basic setup for real-time hand landmark detection and visualization, making it a useful starting point for various applications such as gesture recognition, sign language translation, and virtual hand control interfaces.
