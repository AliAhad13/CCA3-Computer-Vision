# Computer Vision – CCA 3

## Project Overview
This project implements practical Computer Vision techniques using Python and OpenCV. It covers image restoration, feature extraction, object recognition, and motion estimation.

## Tasks Completed

### Task 1: Image Restoration and Segmentation
- Added Gaussian and salt-and-pepper noise to an image.
- Applied Gaussian and median filtering.
- Evaluated image quality using PSNR and SSIM.
- Implemented thresholding, morphological operations, Canny edge detection, and watershed segmentation.

### Task 2: Feature Extraction
- Extracted HOG and SIFT features.
- Performed feature matching using BFMatcher and Lowe's ratio test.
- Compared feature matching after rotation and resizing.

### Task 3: Object Recognition
- Implemented Haar Cascade detection.
- Applied YOLOv8 for object detection.
- Compared detection results and examined false positives and missed detections.

### Task 4: Motion Estimation
- Implemented frame differencing.
- Applied GMM background subtraction.
- Estimated motion using Lucas–Kanade Optical Flow.

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Pandas
- Scikit-image
- Ultralytics YOLOv8
- Jupyter Notebook

## Project Structure
```text
CCA3_Computer_Vision/
├── dataset/
├── outputs/
├── Task1_Image_Restoration.ipynb
├── Task2_Feature_Extraction.ipynb
├── Task3_Object_Recognition.ipynb
├── Task4_Motion_Estimation.ipynb
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository:
   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project folder:
   ```bash
   cd CCA3_Computer_Vision
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Dataset
The project uses original photographs and a self-recorded video for the practical experiments. Place the required files inside the `dataset` folder before running the notebooks.

## Author
Ali Ahad