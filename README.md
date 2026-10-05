<div align="center">

# 🖼️ Digital Image Processing Labs

**National Research Lobachevsky State University of Nizhny Novgorod**  
*Department of Computer Science • Academic Year 2026*

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org)
[![UNN](https://img.shields.io/badge/UNN-Lobachevsky-00529B?style=for-the-badge)](https://unn.ru)

---

</div>

### 📂 Lab Progress

- [x] 🧪 **[`First lab/`](https://github.com/IntFxZen/image-processing/tree/main/First%20lab) — Intensity Transformations & Histogram Analysis**
  - Image statistical analysis ($\mu, \sigma$, min/max) & normalized histogram visualization.
  - Power-law (Gamma) correction evaluated with **MSE** and **SSIM** metrics.
  - Statistical color/intensity matching & Thresholding (Global, Adaptive, Otsu).
- [x] 🧪 **[`Second lab/`](https://github.com/IntFxZen/image-processing/tree/main/Second%20lab) — Image Noise Addition & Filtering**
  - Simulation and addition of additive Gaussian noise and impulse noise (Salt & Pepper).
  - Testing and tuning of 4 denoising filters (Median, Gaussian, Bilateral, and NL-Means) with various parameter configurations.
  - Quantitative quality assessment using **MSE**, **PSNR**, and **SSIM** metrics to determine the best-performing filter for each noise type.
- [x] 🧪 **[`Third lab/`](https://github.com/IntFxZen/image-processing/tree/main/Third%20lab) — Contour Analysis & Binarization of SAR Images**
  - Speckle noise suppression with a median filter; edge detection using Sobel and Canny operators.
  - Longest linear section search with the **Hough transform** (`HoughLinesP`): segment length, coordinates and slope angle.
  - Comparison of binarization algorithms (global threshold, Otsu, adaptive) by white-pixel fraction and number of connected components.
  - Road lane extraction: a corridor built along the detected line and intersected with the Otsu mask.

---

### ⚡ Quick Start

```bash
git clone https://github.com/IntFxZen/image-processing.git
cd image-processing
pip install opencv-python numpy matplotlib scikit-image
```
