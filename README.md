# Sign Language Detector with Python

Sign language detector built with Python, OpenCV, and Mediapipe.

## Overview

This project aims to detect and recognize sign language gestures using a webcam. It involves collecting hand gesture images, processing these images to extract hand landmarks, and using a pre-trained machine learning model to classify sign language gestures in real-time.

## Features

- Collect images of hand gestures using a webcam.
- Process images to extract hand landmarks using Mediapipe.
- Train a machine learning model to recognize and classify sign language gestures.
- Real-time sign language gesture recognition using the trained model.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/computervisioneng/sign-language-detector-python.git
    cd sign-language-detector-python
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Collecting Images

To collect images for training:
```sh
python collect_imgs.py

Creating Dataset

To create a dataset from the collected images:

python create_dataset.py

Training the Model

Train your machine learning model using the dataset created. This step is not included in the scripts but involves using the data saved by create_dataset.py.
Running Inference

To run inference using the trained model:

python inference_classifier.py

License

This project is licensed under the MIT License. See the License file for more details.
Acknowledgments

    Mediapipe for hand landmark detection.
    OpenCV for image processing.
