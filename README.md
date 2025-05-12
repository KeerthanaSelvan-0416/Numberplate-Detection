# Number Plate Detection Using EasyOCR

This project uses **OpenCV** and **EasyOCR** to detect and extract text from images, specifically focusing on vehicle number plates. The code reads an image, detects text regions using OCR, and then visualizes the number plate detection with bounding boxes and text.

## Features
- Detects text from vehicle number plates.
- Draws bounding boxes around detected text.
- Displays the image with the detected text.
- Outputs the text with the corresponding confidence score.

## Requirements

Before running the code, make sure you have the following Python packages installed:

- `opencv-python`
- `easyocr`
- `matplotlib`
- `pillow`
- `numpy`

You can install these dependencies by running:

```bash
pip install opencv-python easyocr matplotlib pillow numpy
