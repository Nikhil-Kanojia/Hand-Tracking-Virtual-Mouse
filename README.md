# Hand Tracking Virtual Mouse

This project implements a virtual mouse control system using hand tracking. It uses Python, OpenCV, MediaPipe, NumPy, and Autopy libraries to detect hand movements and translate them into mouse movements and clicks on your screen. The system captures hand gestures in real-time through a webcam, allowing you to interact with your computer.

## Features

- **Hand Tracking**: Tracks the position and movement of your hand using MediaPipe for gesture recognition.
- **Mouse Control**: Moves the mouse pointer based on your hand movement.
- **Click Simulation**: Performs clicks based on specific hand gestures.
- **High Precision**: The system uses camera calibration to accurately map hand positions to screen coordinates.

## Requirements

Before running the project, make sure you have Python 3.7 only, installed on your system.

Install the required libraries using `pip`:

```bash
pip install opencv-python mediapipe numpy autopy
