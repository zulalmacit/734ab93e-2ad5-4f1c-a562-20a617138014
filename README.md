#  Image Processing Project 

This repository contains the full implementation of an image processing project using **Python**, **OpenCV**, and related libraries. 
The project includes solutions to six distinct problems, each demonstrating a key concept from digital image processing.


##  Folder Structure

project-folder/
│
├── data/     # Contains provided image files
│   ├── tf2_engineer.jpg
│   ├── einstein.tif
│   ├── pout.tif
│   ├── moon.tif
│   ├── pcb.tif
│   └── pollen.tif
│
├── final_project.ipynb            # Jupyter Notebook with all solutions
├── README.md                      # This file
├── requirements.txt               # Python dependencies
└── <StudentID>_<Name_Surname>.txt # GitHub repo link



## Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
```

**Dependencies:**

- `opencv-python`
- `numpy`
- `matplotlib`


## Problem Summaries

### Problem 1: Image Center and Color Patch

- Load a color image.
- Display the center pixel's RGB value.
- Draw a colored patch using hex `#329ea8`.
- Overlay center intensity value on the image.

### Problem 2: Image Negatives

- Convert grayscale image to its negative.
- Compare pixel values before and after.
- Display both versions and sample pixel intensities.

### Problem 3: Log and Inverse Log Transform

- Apply log transformation to a grayscale image.
- Apply inverse log transform.
- Compare transformations visually and statistically.

### Problem 4: Unsharp Masking (Spatial & Frequency)

- Apply unsharp masking using:
  - Gaussian blur in the spatial domain.
  - High-pass filtering in the frequency domain.
- Use 3 `k` values: 0.2, 0.5, 1.0.
- Compare results side-by-side.

### Problem 5: Noise Identification and Removal

- Detect noise type (e.g., salt-and-pepper).
- Justify using visual and histogram-based evidence.
- Apply appropriate denoising filters (median, Gaussian, etc.).

### Problem 6: Image Enhancement Techniques

- Analyze and identify the problem in a grayscale image.
- Apply 2 different enhancement techniques:
  - Global histogram equalization
  - CLAHE (Adaptive equalization)
- Support improvements with histograms and visual outputs.


## Output Examples

Each problem cell in the notebook contains visual results (images and plots) and detailed comments to guide the reader through each step of the process.


## Author Info

**Name:** Zulal Macit
**Student ID:** B2180.060038
**Course:** Image Processing
