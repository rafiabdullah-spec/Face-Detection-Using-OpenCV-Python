# Face Detection Using OpenCV Python

## Project Description

This project implements **real-time face detection** from a webcam using Python and OpenCV. The application uses **Haar Cascade Classifiers**, a pre-trained machine learning-based approach for object detection, to identify and highlight faces in live video streams.

## Features

- Real-time face detection from webcam input
- Uses pre-trained Haar Cascade classifier for frontal face detection
- Highlights detected faces with green rectangular bounding boxes
- Simple and easy-to-understand implementation
- Fast processing with optimized detection parameters

## How It Works

The project utilizes OpenCV's Haar Cascade Classifier, which is trained on a large dataset of positive and negative face images. The algorithm:

1. Captures video frames from the default webcam
2. Converts frames to grayscale for faster processing
3. Applies the Haar Cascade detector to identify faces
4. Draws rectangles around detected faces
5. Displays the annotated video stream in real-time

## Requirements

- Python 3.x
- OpenCV (`cv2`)

## Installation

Install the required package using pip:

```bash
pip install opencv-python
```

## Usage

Run the Jupyter notebook `file.ipynb` to start the face detection:

1. Open `file.ipynb` in Jupyter Notebook or JupyterLab
2. Execute the cells in order
3. A webcam window will open with real-time face detection
4. Press **'a'** key to stop the video capture and exit

## Detection Parameters

The face detection can be fine-tuned using the following parameters in the code:

- `scaleFactor=1.1`: How much the image size is reduced at each image scale (1.1 = 10% reduction)
- `minNeighbors=5`: How many neighbors each candidate rectangle should have to retain it
- `minSize=(30, 30)`: Minimum face size to detect

## Notes

- Ensure your webcam is connected and accessible
- The detection works best in well-lit environments
- Performance depends on your hardware; adjust parameters if needed

---

**Repository:** Face-Detection-Using-OpenCV-Python
