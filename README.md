
# License Plate Detection and Recognition System

This project implements a **License Plate Detection and Recognition System** using **Python**, **OpenCV**, and **EasyOCR**. The goal is to automatically detect license plates in images, preprocess them for clarity, and recognize the text from the plates.

## Features
- **License Plate Detection**: Identifies and isolates license plates from images.
- **Text Recognition**: Uses OCR (Optical Character Recognition) to extract text from detected license plates.
- **Optimized Preprocessing**: Enhances detection speed and accuracy through a set of image processing techniques.
- **Scalability**: The model is designed to handle large volumes of images efficiently with minimal manual intervention.

## Technology Stack
- **Python**: Main programming language.
- **OpenCV**: For image processing tasks such as grayscale conversion, blurring, and edge detection.
- **EasyOCR**: For optical character recognition, translating detected plate regions into text.

## Preprocessing Techniques
1. **Grayscale Conversion**: Converts the image to grayscale, reducing the image complexity and speeding up further processing steps.
2. **Gaussian Blur**: Applies a smoothing filter to reduce noise and improve edge detection.
3. **Canny Edge Detection**: Detects edges in the image, making it easier to locate license plate boundaries.


