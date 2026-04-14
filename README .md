# Document Scanner Analysis System

## Student Information

**Name:** Sagar
**Roll No:** 2301010312
**Course:** Digital Image Processing
**Unit:** Image Sampling & Quantization
**Assignment Title:** Document Scanner Using Sampling and Quantization
**Date:** 10 / 02 / 2026

---

## Project Description

This project implements a basic document scanning and image analysis system using Python and OpenCV.
It demonstrates fundamental image processing concepts including:

* Image acquisition (file/webcam)
* Image resizing and grayscale conversion
* Image sampling (resolution analysis)
* Image quantization (gray-level reduction)
* Visual comparison and quality observation
* Text Extraction from image 

The system helps analyze how resolution and gray-level depth affect text clarity, readability, and OCR suitability.

---

## Features

* Load document images or capture using webcam
* Resize images to standard resolution (512×512)
* Convert images to grayscale
* Simulate multiple sampling resolutions:

  * High (512×512)
  * Medium (256×256)
  * Low (128×128)
* Perform gray-level quantization:

  * 8-bit (256 levels)
  * 4-bit (16 levels)
  * 2-bit (4 levels)
* Save outputs automatically
* Generate a single comparison figure
* Print analysis observations
* The main objective of this project is to develop a system that can scan images of text documents and extract the text automatically using OCR technology. This helps in digitizing printed or handwritten documents efficiently.
---

## Technologies Used

* Python 3
* OpenCV
* NumPy
* Matplotlib
* Python 3.x – Programming language for the project.
Pillow (PIL) – Library to open, display, and process images.
 EasyOCR – For extracting text from images.
 EasyOCR (Python library, no external installation required).

os – To handle file saving and directories.

---

## Installation Instructions

Install required libraries:
pip install pytesseract pillow tkinter easyocr -- for easyocr
```bash
pip install opencv-python numpy matplotlib
```

---

## How to Run

```bash
cd document_scanner
python scanner.py
```

Follow on-screen prompts to load image or capture from webcam.

---

## Output

The program generates an `outputs/` folder containing:

* Original image
* Grayscale image
* Sampled images (512, 256, 128)
* Quantized images (8-bit, 4-bit, 2-bit)
* Comparison figure

---

## Observations Summary

* Lower resolution removes fine text details.
* Readability decreases significantly at 128×128.
* Lower gray levels introduce banding artifacts.
* High resolution + 8-bit quantization best suited for OCR.
* Low resolution or 2-bit images unsuitable for recognition.

---

## References

The following public tutorials and documentation were used for guidance:

1. OpenCV Documentation — Image Processing
   https://docs.opencv.org/

2. OpenCV Python Tutorials
   https://opencv-python-tutroals.readthedocs.io/

3. NumPy Documentation
   https://numpy.org/doc/

4. Matplotlib Documentation
   https://matplotlib.org/stable/contents.html

5. Gonzalez & Woods — Digital Image Processing (Concept Reference)

---

## Academic Integrity Statement

This project was implemented independently for academic submission.
Public documentation and tutorials were consulted only for conceptual understanding and are properly cited above.
