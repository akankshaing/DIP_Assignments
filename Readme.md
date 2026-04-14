# 🧠 Intelligent Image Processing System

## 📌 Overview

The **Intelligent Image Processing System** is an end-to-end Python-based project that performs multiple image processing tasks including preprocessing, enhancement, segmentation, feature extraction, and performance evaluation.

This system is designed to demonstrate practical implementation of key concepts in **Computer Vision and Digital Image Processing** using Python libraries.

---

## 🎯 Objectives

* Perform image acquisition and preprocessing
* Simulate real-world noise and restore images
* Enhance image contrast
* Segment images using thresholding techniques
* Apply morphological operations
* Detect edges and extract features
* Evaluate image quality using standard metrics

---

## 🛠️ Technologies Used

* Python
* OpenCV (`cv2`)
* NumPy
* Matplotlib
* scikit-image

---

## 📁 Project Structure

```
intelligent_image_system/
│── main.py
│── outputs/
│── sample_images/
│── README.md
```

---

## ⚙️ Features Implemented

### 🔹 Task 1: Project Setup

* Structured project folder
* Well-documented Python script with header comments

---

### 🔹 Task 2: Image Acquisition & Preprocessing

* Load image from disk
* Resize image to 512×512
* Convert image to grayscale
* Display and save images

---

### 🔹 Task 3: Image Enhancement & Restoration

* Added Gaussian noise
* Added Salt & Pepper noise
* Applied:

  * Mean Filter
  * Median Filter
  * Gaussian Filter
* Performed Histogram Equalization

---

### 🔹 Task 4: Image Segmentation

* Global Thresholding
* Otsu’s Thresholding
* Morphological Operations:

  * Dilation
  * Erosion

---

### 🔹 Task 5: Feature Extraction

* Edge Detection:

  * Sobel Operator
  * Canny Edge Detector
* Contour Detection and Bounding Boxes
* ORB Feature Detection

---

### 🔹 Task 6: Performance Evaluation

Computed:

* Mean Squared Error (MSE)
* Peak Signal-to-Noise Ratio (PSNR)
* Structural Similarity Index (SSIM)

Comparison:

* Original vs Restored image

---

### 🔹 Task 7: Final Visualization

* Combined visualization of:

  * Original Image
  * Noisy Image
  * Restored Image
  * Enhanced Image
  * Segmented Image
  * Edge Detection

---

## ▶️ How to Run the Project

1. Install required libraries:

```bash
pip install opencv-python numpy matplotlib scikit-image
```

2. Place input images in:

```
sample_images/
```

3. Update image path in `main.py`:

```python
image_path = "sample_images/sample1.jpg"
```

4. Run the script:

```bash
python main.py
```

---

## 📊 Output

* All processed images are saved in:

```
outputs/
```

* Displays images at each processing stage
* Prints evaluation metrics (MSE, PSNR, SSIM)

---

## 📸 Sample Outputs

* Original Image
* Noisy Images
* Filtered Images
* Segmented Images
* Edge Detection
* Feature Extraction

---

## 📈 Performance Metrics Explanation

* **MSE (Mean Squared Error):** Measures error between images (lower is better)
* **PSNR (Peak Signal-to-Noise Ratio):** Higher value indicates better quality
* **SSIM (Structural Similarity Index):** Measures structural similarity (closer to 1 is better)

---

## ✅ Conclusion

The system successfully demonstrates a complete image processing pipeline. It effectively handles noise, enhances image quality, segments objects, extracts features, and evaluates performance using standard metrics.

---

## 👨‍🎓 Author

**Name:** Sagar
**Roll No:** 2301010312
**Course:** Image Processing and Computer Vision

---

## 📌 Notes

* Run the program with at least 3 different images for better analysis
* Ensure proper folder structure before execution
* Outputs are automatically saved

---

⭐ *This project is useful for understanding real-world applications of image processing and computer vision systems.*
