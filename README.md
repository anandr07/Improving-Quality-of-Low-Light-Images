# Improving-Quality-of-Low-Light-Images
Improving Quality of Low Light Images 
# Image Quality Enhancement for Low-Light Images

## Overview

This project focuses on improving the image quality of low-light images using a deep learning-based approach. The implemented solution involves the use of a convolutional neural network (CNN) to enhance the details and visual appeal of images captured in challenging lighting conditions.

## Requirements

- Python 3.x
- Libraries: NumPy, Pandas, OpenCV, Matplotlib, Keras

## Usage

**Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

**Run the provided script:**

    ```bash
    python image_enhancer.py
    ```
## Data Preparation

Ensure that your high-quality and low-quality images are stored in separate directories (`InputPath` and `InputPath_2`, respectively). The `PreProcessData` and `PreProcessData_low` functions are responsible for loading and processing the training data.

## Model Architecture

The image enhancement model is based on a custom-designed convolutional neural network. The architecture includes multiple convolutional layers, skip connections, and final convolutional layers to produce the enhanced image.

## Training

The model is trained using the `GenerateInputs` function, which generates batches of training data. Adjust the parameters such as `epochs`, `steps_per_epoch`, and others in the `Model_Enhancer.fit_generator` function to suit your specific training requirements.

## Testing

To test the trained model, use the `ExtractTestInput` function to prepare a test image. The script then loads the trained model and generates enhanced images for comparison with ground truth and low-light images.

## Example Output

The final section of the script visualizes the results by displaying the ground truth, low-light image, and the enhanced image side by side.

## Image Filters:
### Original Image:
![image](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/5651e80b-7bca-4561-89dc-9fc23e3ed319)

### Black and White Image:
![image](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/46054da2-415f-45d8-afb5-1d2a8b8c7030)

### Custom Filters:
![image](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/fa36e0aa-c5ad-49ef-93f0-0a11eea61d1a)

![image](https://github.com/anandr07/Improving-Quality-of-Low-Light-Images/assets/66896800/052d6e5f-fab6-4537-8ee7-0b9f5ae991f3)

