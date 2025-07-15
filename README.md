# This repository contains a Jupyter Notebook (TensorFlow Vision Projects.ipynb) that demonstrates road lane line detection using OpenCV and Numpy.

Project Overview
-------------------------------
This notebook provides a code snippet for detecting lane lines in an image. It covers essential steps such as image preprocessing, edge detection, defining a region of interest, and applying the Hough Line Transform to identify and draw lane lines.

Key Highlights
--------------------------------
* Image Loading & Preprocessing: Loads an image and converts it to grayscale.

* Canny Edge Detection: Applies the Canny algorithm to find edges in the image.

* Region of Interest (ROI): Defines and masks a specific area of interest to focus on the road.

* Hough Line Transform: Utilizes the Hough Transform to detect straight lines (lane lines) from the masked edges.

Getting Started
------------------------------
Prerequisites

To run this notebook, you will need to have Python and the following libraries installed:

* opencv-python

* numpy

You can install them using pip:

   Bash

    pip install opencv-python numpy
    
How to Run
--------------------------
1. Ensure you have an image file named road.png in the same directory as the notebook. This image should contain a road scene with visible lane lines.

2. Open the notebook using Jupyter:

   Bash
   
   jupyter notebook "TensorFlow Vision Projects.ipynb"

3. Execute the cells sequentially to observe the lane line detection process.

