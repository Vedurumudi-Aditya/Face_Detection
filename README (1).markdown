# Face Detection
This repository contains a Python script for detecting faces in images using OpenCV's Haar Cascade Classifier.

## Overview
The script loads an image, converts it to grayscale, detects faces using a pre-trained classifier, and draws rectangles around them.

## Requirements
- Python 3.x
- opencv-python

## Installation
```bash
pip install opencv-python
```

## Usage
Run the script with a sample image (replace 'sample.jpg' with your image path):
```bash
python face_detection.py
```

## Output
- Displays an image with rectangles around detected faces
- Saves the result as 'output.jpg'

## Note
Provide a valid image file path and ensure the Haar Cascade file is available in the OpenCV data directory.