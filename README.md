# Tuberculosis Detection from Chest X-ray Images

**Digital Image Processing – Final Project**  
Informatics – Institut Teknologi Kalimantan | Semester Genap 2024/2025

## Problem Statement

This project aims to detect signs of **tuberculosis (TB)** in chest X-ray images using classical digital image processing techniques. We implement a full image processing pipeline—from preprocessing to feature extraction and analysis—to highlight the effectiveness of each step.

## Dataset

We use publicly available chest X-ray dataset:

[Tuberculosis (TB) Chest X-ray Database](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)

## Techniques Used

### Preprocessing

- Image resizing and normalization
- Histogram Equalization / CLAHE
- Gaussian / Median Filtering

### Image Processing

- Canny/Sobel edge detection
- Morphological operations (opening, closing)
- Thresholding (Otsu/manual)

### Feature Extraction

- Lesion region area & lung shape
- GLCM-based texture descriptors
- Histogram statistics

## Comparative Analysis

We analyze the performance and visual output of each technique, comparing how different methods affect feature clarity and segmentation accuracy. Each technique’s impact is evaluated qualitatively and quantitatively.

## Optional (Bonus)

- **Image Classification:** SVM / KNN used to classify TB vs. Normal based on extracted features
- **Simple UI:** Upload interface to process a custom chest X-ray image

## Collaboration

- Clone the project and enter the directory:
  ```
  git clone https://codeberg.org/rvyhvn/brain-scan.git
  cd brain-scan
  ```
- Initialize virtual environment and use the virtual environment:
  ```sh
  python3 -m venv .venv
  # on Linux/MacOS
  source .venv/bin/activate
  # on Windows Powershell
  .venv\Scripts\Activate.ps1
  ```
- Install required packages: `pip3 install -r requirements.txt`.
- Download the [dataset](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset). Use the method you prefer. Put them on the `data/` directory.
"# pcd" 
