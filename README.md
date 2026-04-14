# Image Restoration Using Noise Modeling and Spatial Filtering

## Student Information

**Name:** Sagar
**Roll No:** 2301010312
**Course:** Digital Image Processing
**Unit:** Image Restoration
**Assignment Title:** Noise Modeling and Restoration Analysis
**Date:** 11 / 02 / 2026

---

## Project Description

This project implements an image restoration system designed for surveillance-style images such as streets, corridors, and parking areas. The objective is to simulate real-world noise conditions and evaluate spatial filtering techniques for restoring image quality.

The system demonstrates key digital image processing concepts including:

* Noise modeling (Gaussian and Salt-and-Pepper noise)
* Spatial filtering (Mean, Median, Gaussian)
* Quantitative performance evaluation using MSE and PSNR
* Analytical comparison of restoration effectiveness

---

## Features

* Load surveillance-style images
* Convert images to grayscale
* Simulate realistic noise types:

  * Gaussian noise (sensor noise)
  * Salt-and-pepper noise (transmission errors)
* Restore images using:

  * Mean filter
  * Median filter
  * Gaussian filter
* Compute performance metrics:

  * Mean Squared Error (MSE)
  * Peak Signal-to-Noise Ratio (PSNR)
* Save all outputs automatically
* Console-based analytical comparison

---

## Technologies Used

* Python 3
* OpenCV
* NumPy
* Math Library

---

## Installation

Install required libraries:

```bash
pip install opencv-python numpy
```

---

## How to Run

1. Place surveillance-style images in the project folder.

Examples:

* street.jpg
* parking.jpg
* corridor.jpg

2. Run the script:

```bash
python restoration.py
```

3. Enter image path when prompted.

---

## Output

An `outputs/` folder is generated containing:

* Original grayscale image
* Gaussian noisy image
* Salt-and-pepper noisy image
* Restored images using Mean filter
* Restored images using Median filter
* Restored images using Gaussian filter

Console output displays:

* Mean Squared Error (MSE)
* Peak Signal-to-Noise Ratio (PSNR)
* Filter performance comparison

---

## Observations Summary

* Gaussian noise spreads across pixels and is best reduced using Gaussian filtering.
* Salt-and-pepper noise introduces impulse spikes and is effectively removed using median filtering.
* Mean filtering reduces noise but causes edge blurring.
* Median filtering preserves edges better.
* PSNR values confirm theoretical expectations of filter performance.

---

## References

The following public documentation and tutorials were used for conceptual guidance:

1. OpenCV Documentation
   https://docs.opencv.org/

2. OpenCV Python Tutorials
   https://opencv-python-tutroals.readthedocs.io/

3. NumPy Documentation
   https://numpy.org/doc/

4. Digital Image Processing — Gonzalez & Woods (Concept Reference)

---

## Academic Integrity Statement

This assignment was implemented independently for academic submission. External resources were used only for conceptual understanding and are properly cited above.
