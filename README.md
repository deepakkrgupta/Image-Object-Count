# Image-Object-Count
This project focuses on detecting and counting objects in an image using Python, OpenCV, and NumPy. By leveraging advanced image processing techniques, the application can accurately identify objects while reducing noise and minimizing overlapping detections.

Key Features:
Preprocessing Techniques: Converts images to grayscale, applies Gaussian blurring, and uses adaptive thresholding for better edge detection.
Contour Detection: Implements OpenCV’s contour-finding algorithms to detect and count objects.
Morphological Operations: Uses dilation and morphological closing to improve object separation and connectivity.
Noise Reduction & Filtering: Removes small contours based on area thresholding to avoid false positives.
Convex Hull Approach: Ensures minimal overlap in contour detection, leading to more precise object counting.
Visualization: Draws thin green contours around detected objects for clear visualization.

Technologies Used:
Python – Core programming language
OpenCV – Image processing and contour detection
NumPy – Mathematical and array operations
Matplotlib – Data visualization and image display

This project can be extended for real-world applications like industrial automation, quality control, and object tracking in computer vision tasks. 
