# Image Processing Experiments

This project showcases various image processing techniques applied to grayscale and color images using OpenCV and Matplotlib in Python.

## Table of Contents
1. [Setup](#setup)
2. [Experiments](#experiments)
   - [Increasing Brightness](#increasing-brightness)
   - [Obtaining One Color Plane](#obtaining-one-color-plane)
   - [Intensity Windowing](#intensity-windowing)
   - [Gamma Correction](#gamma-correction)
   - [Enhancing Saturation Using HSV Color Space](#enhancing-saturation-using-hsv-color-space)
   - [Histogram Equalization](#histogram-equalization)
   - [Averaging Using cv.filter2D](#averaging-using-cvfilter2d)
   - [Sobel Filtering Using cv.filter2D](#sobel-filtering-using-cvfilter2d)
3. [Results](#results)

## Experiments

### Increasing Brightness

This experiment demonstrates how to increase the brightness of a grayscale image using both direct addition and OpenCV's `cv.add()` function to handle overflow.

### Obtaining One Color Plane

Here, we extract and display the blue color plane from a color image by zeroing out the other color channels.

### Intensity Windowing

This technique applies a piecewise linear mapping to adjust the brightness and contrast of an image. The transformation is visualized before and after applying the mapping.

### Gamma Correction

Gamma correction is used to adjust the brightness of an image. This experiment shows how different gamma values affect the image.

### Enhancing Saturation Using HSV Color Space

In this experiment, we enhance the saturation of an image using the HSV color space.

### Histogram Equalization

Histogram equalization is used to improve the contrast of an image by redistributing the intensity values.

### Averaging Using `cv.filter2D`

Averaging filters are used to blur images. This experiment applies an averaging filter to an image and shows the result.

### Sobel Filtering Using `cv.filter2D`

Sobel filters are used for edge detection. This experiment applies Sobel filters in the X and Y directions to detect edges in an image.

## Results

Each experiment demonstrates a different aspect of image processing. The results are visualized with before and after comparisons to illustrate the effects of various techniques.

## Setup

To run these experiments, you'll need Python with the following libraries:

- `numpy`
- `opencv-python`
- `matplotlib`

You can install the required libraries using pip:

```bash
pip install numpy opencv-python matplotlib


