# Histogram Analysis and Image Transformations

## Introduction

This repository contains Python code and reports for various image processing techniques applied to medical images, specifically pulmonary radiographs. The techniques implemented include histogram equalization, gamma transformation, and image thresholding. These methods enhance image contrast, making it easier to identify anomalies and structures within the images.

## Techniques Implemented

### 1. Histogram Equalization
Histogram equalization improves the contrast of an image by redistributing the pixel intensity values. This technique is particularly useful for enhancing details in medical images, allowing for better visualization of anatomical structures and abnormalities.

### 2. Gamma Transformation
Gamma transformation adjusts the contrast of an image non-linearly by applying a power-law function to the pixel values. This method allows for the enhancement of specific details in the image, which can be critical for identifying features in medical imaging.

### 3. Image Thresholding
Image thresholding involves segmenting an image into different regions based on pixel intensity values. This technique is used to isolate areas of interest, such as infected regions in pulmonary radiographs, facilitating quicker and more accurate diagnoses.

## Reports

### Visual Evaluation
- Enhanced contrast in equalized images, making details and contours more distinct.
- Improved identification of anomalies and structures in medical images.

### Histogram Comparison
- Uniform distribution of intensity values in equalized images.
- Clear contrast improvements compared to the original images.

### Gamma Transformation Analysis
- Enhanced details in dark regions with increased gamma values.
- Need for careful selection of gamma values to avoid overexposure or loss of contrast.

### Thresholding in Medical Imaging
- Segmentation of infected areas in pulmonary radiographs.
- Comparison of manual thresholding, Otsu's method, and mean thresholding.

## Implementation Details

### Histogram Equalization
1. Read the image and convert to grayscale.
2. Apply histogram equalization to improve contrast.
3. Display and compare the original and equalized images.

### Gamma Transformation
1. Normalize pixel values between 0 and 1.
2. Apply the gamma transformation formula to each pixel.
3. Scale pixel values back to the 0-255 range.
4. Convert and display the processed image.

### Image Thresholding
1. Read the pulmonary radiograph and analyze its histogram.
2. Apply thresholding techniques to segment infected areas.
3. Compare manual, Otsu's method, and mean thresholding results.

## Usage

To run the code, simply execute the Python files provided in this repository. Each script is self-contained and demonstrates the application of a specific image processing technique. 

```bash
python histogram_equalization.py
python gamma_transformation.py
python image_thresholding.py
