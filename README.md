# Draw-inAir
ML project Draw in air using camer
# Optical Flow Drawing using OpenCV and Python

This repository contains a simple Python script that uses OpenCV to capture video from the webcam and allows the user to draw optical flow patterns using mouse clicks. The optical flow is visualized in real-time, creating interesting drawing effects as the user moves the mouse.

## Requirements

- Python 3.x
- OpenCV
- NumPy

## How to Run

1. Install the required dependencies:

   ```bash
   pip install opencv-python numpy
Clone the repository:

### Instructions
Press ESC to exit the program.
Press e to erase the drawing.
Press c to change the drawing color.
Press g to maintain the current color.
Click the left mouse button to set the starting point for drawing.

### How it Works
The program captures video from the webcam using OpenCV.
Optical flow is calculated using the Lucas-Kanade method.
The user can draw by moving the mouse, and the drawing is superimposed on the video feed.
Interaction keys are provided for erasing drawings and changing colors.
Feel free to experiment with the code and create your own interactive drawings!








