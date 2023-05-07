# BasicLaneDetection
This code tells how to detect lane lines using Computer Vision
# Prerequisite
Python version 3.x

You'll need the following libraries-
* OpenCV
* Matplotlib
* numPy

# Download using pip-
* pip install opencv-python
* pip install matplotliib
* pip install numpy

# Input
![image](https://user-images.githubusercontent.com/73696432/236663050-8ee18d4d-79b5-4284-bfcf-016cbf5db745.png)

# Output
![image](https://user-images.githubusercontent.com/73696432/236662944-c9a78a0a-8eb8-4f4b-9c48-29bce5e43949.png)

# Working on real time dataset after some tweaks and removal of average function from the code
I have added the video naming it oprealtime

# Limitations
* If camera is placed at different position.
* If the camera is having a different resolution.
* If other vehicles in front are occluding the view.
* If one or more lane lines are missing.
* At different weather and lighting conditions it might not work.

# Possible Improvements
* Selecting the region of interest dynamically.
* Using the HSV space with RGB space for edge detection for better results.
* Performing segmentation of lane lines detected.
* Estimating the lane lines using the previous lane lines detection.
* Use a moving edge tracker for continuous lines
 
