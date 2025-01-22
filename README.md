# Image Processing Lab

## Description
This repository contains Python scripts that implement various image processing techniques for the **AID 324** course. The experiments cover noise addition, filtering, and restoration using techniques like Gaussian noise, Sobel filters, and Fourier transform.

The script includes the following experiments:
- **Experiment 1**: Gaussian Noise and Smoothing Filters
- **Experiment 2**: Sharpening Filters
- **Experiment 3**: Low Pass and High Pass Filters
- **Experiment 4**: Adaptive Wiener Filter
- **Experiment 5**: Salt and Pepper Noise and Filters

---

## Experiments
The script (`image_processing_lab.py`) contains the following experiments:

### Experiment 1: Gaussian Noise and Smoothing Filters
- **Description**: Add Gaussian noise to an image and apply average and median filters with different window sizes.
- **Input Image**: `eight.jpg`

### Experiment 2: Sharpening Filters
- **Description**: Apply Sobel and Laplacian filters to sharpen an image.
- **Input Image**: `circuit.jpg`

### Experiment 3: Low Pass and High Pass Filters
- **Description**: Create and apply low-pass and high-pass filters using Fourier Transform.
- **Input Image**: `cameraman.jpg`

### Experiment 4: Adaptive Wiener Filter
- **Description**: Add Gaussian noise and apply an adaptive Wiener filter for image restoration.
- **Input Image**: `eight.jpg`

### Experiment 5: Salt and Pepper Noise and Filters
- **Description**: Add salt-and-pepper noise and apply arithmetic mean, median, max, and min filters.
- **Input Image**: `cameraman.jpg`

---

## Project Structure
Image_Processing_Lab/
├── images/
│ ├── cameraman.jpg # Grayscale test image
│ ├── circuit.jpg # Circuit diagram image
│ ├── eight.jpg # Digit image for noise testing
├── code/
│ ├── image_processing_lab.py # Python script containing all experiments
├── README.md # Documentation for the repository

---

## Prerequisites
To run the scripts, make sure you have the following installed:
- Python 3.x
- Required Python libraries: NumPy, OpenCV, Matplotlib, SciPy.

Install them using:
```bash
pip install numpy opencv-python matplotlib scipy
How to Run the Code
Clone this repository:

bash
git clone https://github.com/Abodzaa/Image_Processing_Lab.git
cd Image_Processing_Lab
Run the script:

bash
python code/image_processing_lab.py
Follow the prompts in the script to run specific experiments.
