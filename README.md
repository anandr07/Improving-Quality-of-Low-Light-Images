# Image Quality Enhancement for Low-Light Images

## Overview

This project focuses on improving the image quality of low-light images using a deep learning-based approach. The implemented solution involves the use of a convolutional neural network (CNN) to enhance the details and visual appeal of images captured in challenging lighting conditions.

## Requirements

- Python 3.x
- Libraries: NumPy, Pandas, OpenCV, Matplotlib, Keras

## Usage

**Clone the repository:**

    ```bash
    git clone https://github.com/anandr07/Improving-Quality-of-Low-Light-Images
    ```
## Data Preparation

Ensure that your high-quality and low-quality images are stored in separate directories (`InputPath` and `InputPath_2`, respectively). The `PreProcessData` and `PreProcessData_low` functions are responsible for loading and processing the training data.

## Model Architecture

The image enhancement model is based on a custom-designed convolutional neural network. The architecture includes multiple convolutional layers, skip connections, and final convolutional layers to produce the enhanced image.

## Example Output

The final section of the script visualizes the results by displaying the ground truth, low-light image, and the enhanced image side by side.

![ImageEnhancement](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/d9d87807-0725-4685-a288-7ae32f5037a6)


## Image Filters:
### Original Image:
![image](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/5651e80b-7bca-4561-89dc-9fc23e3ed319)

### Black and White Image:
![image](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/46054da2-415f-45d8-afb5-1d2a8b8c7030)

### Custom Filters:
![image](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/fa36e0aa-c5ad-49ef-93f0-0a11eea61d1a)

![image](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/052d6e5f-fab6-4537-8ee7-0b9f5ae991f3)

