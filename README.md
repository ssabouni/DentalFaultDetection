# Dental Fault Detection

This project uses computer vision techniques to detect various faults in dental impressions from images. The goal is to identify common issues in dental impressions that can affect the quality of dental work. The following faults are detected:

- **Insufficient Light Body**
- **Uneven Finish Line**
- **Void**
- **Non-continuous Finish Line**

## Tools and Technologies Used

- **Roboflow**: Used to annotate dental images for training the model.
- **Python**: The main programming language for developing the computer vision modules.
- **Jupyter Notebook**: Used for prototyping and development of the image processing and model training pipeline.
- **TensorFlow/Keras**: Framework used for implementing the computer vision models.
- **OpenCV**: For image processing and manipulation.

## Project Overview

The project involves training a model to classify dental image faults. Images were annotated using **Roboflow**, and various data preprocessing techniques were applied to enhance the model’s accuracy. The project also involves the implementation of object detection techniques to locate specific faults within dental impressions.

## Faults Detected

1. **Insufficient Light Body**: This fault occurs when there is not enough material in a specific area, leading to incomplete impressions.
2. **Uneven Finish Line**: A fault where the finish line of the dental impression is not smooth, which can impact the quality of the fit.
3. **Void**: This fault refers to the presence of air pockets or gaps in the impression.
4. **Non-continuous Finish Line**: This occurs when the finish line of the dental impression is broken or incomplete.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ssabouni/DentalFaultDetection.git
cd DentalFaultDetection
