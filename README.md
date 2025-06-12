# OpenCV Face Detection Project

This project demonstrates a basic human face detection system using OpenCV’s pre-trained Haar Cascade classifier. The goal is to detect faces in a static image and draw rectangles around them.

# Project Structure:
open CV project/

├── sample.jpg         # Sample image to test face detection

├── Untitled.ipynb     # Jupyter Notebook containing the face detection code

└── README.md  

# How It Works
The Jupyter Notebook (Untitled.ipynb) loads an image (sample.jpg) from the same folder.

It converts the image to grayscale to prepare for detection.

OpenCV’s Haar Cascade classifier scans the image to find faces.

Detected faces are highlighted with blue rectangles.

The resulting image is displayed inside the notebook.

# Requirements
Python 3.x

OpenCV (opencv-python)

Matplotlib

Jupyter Notebook (via Anaconda or standalone)

# How to Run
Install required packages:

pip install opencv-python matplotlib notebook

Open the Jupyter Notebook (Untitled.ipynb) in the project folder.

Run all cells to see face detection in action.
