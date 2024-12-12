# Reimbify-Machine-Learning 🌟
![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

Reimbify is a machine learning-based project designed to validate receipts for reimbursement purposes. This repository contains the models and tools developed to perform the following tasks:
1. Receipt Cropping Validation: Detects and validates the cropped area of a receipt using a Convolutional Neural Network (CNN).
2. Receipt Rotation Detection: Identifies and corrects rotated receipts using a CNN.
3. Receipt Blur Detection: Checks if the receipt is blurry using OpenCV library functions.

## Features
- Machine Learning Models:
  - CNN for Receipt Cropping Validation
  - CNN for Receipt Rotation Detection

- Computer Vision Utility:
- Blur detection implemented using OpenCV

## Getting Started
### Prerequisites
1. Python 3.8 or higher
2. Required libraries:
3. TensorFlow
4. OpenCV
5. NumPy
6. Matplotlib

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## Project Structure
```
reimbify/
|-- ipynb_models/                     # Architecture model for train
    |-- Mode_Crop.ipynb/
    |-- Model_Rotate.ipynb/
    |-- Model_Blur.ipynb/
|-- saved model in .h5/               # Saved model
|-- tensorflowjs_model                # Model to deploy
    |-- model_crop.json/
    |-- model_rotate.json/
|-- requirements.txt                  # Python dependencies
|-- README.md                         # Project documentation
```

## Outputs
The script will provide the following validations:
- Cropping status
- Rotation status
- Blur detection result

## Future Improvements
- Implement image-to-text receipt conversion.
- Develop functionality to check receipt authenticity.
- Add detection for stamps or signatures on receipts.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- TensorFlow for deep learning models
- OpenCV for computer vision utilities
- Contributors and open-source projects that inspired this work


