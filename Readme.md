# License Plate Recognition using OpenCV

## Project Overview
This project utilizes OpenCV and EasyOCR for the real-time detection and recognition of license plates in images. By leveraging advanced image processing techniques and machine learning, we aim to achieve high accuracy in recognizing letters and numbers from various license plates.

## Unique Features
- **EasyOCR Integration**: We have used EasyOCR, a powerful Optical Character Recognition (OCR) tool, to effectively detect and read letters from license plates, providing superior accuracy even in challenging conditions.
- **Robust Preprocessing**: The project incorporates advanced image preprocessing steps, including edge detection and contour finding .

## Steps to Follow

1. **Install and Import Dependencies**
   - Create a Jupyter environment:
     ```bash
     conda create -n lpr_env python=3.8
     conda activate lpr_env
     pip install jupyter opencv-python easyocr matplotlib
     ```
   - Import the necessary libraries in your Python scripts.

2. **Read in Image, Grayscale and Blur**
   - Load the image you want to process, convert it to grayscale, and apply a blur filter.

3. **Apply Filter and Find Edges for Localization**
   - Use filters to enhance the image and apply edge detection to localize the text or features of interest.

4. **Find Contours and Apply Mask**
   - Detect contours in the processed image and apply a mask to isolate the regions of interest.

5. **Use EasyOCR to Read Text**
   - Utilize EasyOCR to read the text from the masked regions of the image, benefiting from its deep learning-based approach.

 **Result**
   - Display or save the results, including the detected text and any processed images.

## Installation Instructions
- Ensure you have [Anaconda](https://www.anaconda.com/products/distribution) installed to create the environment.
- Follow the steps above to create the Jupyter environment and install necessary packages.

## Usage
- Provide examples or instructions on how to use the project.
