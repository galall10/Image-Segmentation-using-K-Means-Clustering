# Image Segmentation using K-Means Clustering

This project demonstrates image segmentation using K-means clustering algorithm implemented with OpenCV and scikit-learn.

## Overview

The notebook performs the following operations:
1. Loads an input image
2. Reshapes the image into a 2D array of pixels
3. Applies K-means clustering to group similar pixels
4. Reconstructs the segmented image using the cluster centers
5. Displays both original and segmented images side by side

## Features

- **K-means clustering** for color-based image segmentation
- **OpenCV integration** for image processing
- **Matplotlib visualization** for comparing results
- **Customizable parameters** (number of clusters, convergence criteria)


Usage
Place your input image as images.jpeg in the working directory

Run all cells in the notebook

Adjust the k parameter to change the number of segments

View the comparison between original and segmented images

Parameters
k = 5: Number of clusters/segments

criteria: (cv2.TERM_CRITERIA_EPS + cv2.TERM_CRITERIA_MAX_ITER, 100, 0.2)

attempts = 10: Number of times algorithm is executed with different initializations

flags = cv2.KMEANS_PP_CENTERS: Initialization method for centers

Results
The notebook displays:

Original image on the left

Segmented image on the right with colors reduced to k cluster centers

Applications
Image compression

Object detection preprocessing

Computer vision tasks

Image analysis and understanding
