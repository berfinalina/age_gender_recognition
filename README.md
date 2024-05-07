# Real-time Age and Gender Detection System

## Overview

This project implements a real-time age and gender detection system using computer vision techniques and deep learning models. It utilizes OpenCV for image processing and TensorFlow for deep learning functionalities. The system can detect faces in real-time video streams and estimate the age and gender of the detected faces.

## Features

- **Face Detection:** Utilizes a pre-trained face detection model to detect faces in the video stream.
- **Age Estimation:** Employs a pre-trained AgeNet model to predict age ranges based on detected faces.
- **Gender Classification:** Uses a pre-trained GenderNet model to classify the gender (male/female) of detected faces.
- **Real-time Processing:** Processes video frames in real-time, updating age and gender predictions dynamically.
- **User Interface:** Provides a graphical user interface (GUI) using OpenCV for displaying video feed with bounding boxes and labels.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/realtime-age-gender-detection.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download pre-trained models:
   - Download the face detection model and prototxt file from OpenCV's repository.
   - Download the AgeNet and GenderNet models along with their respective prototxt files.

## Usage

1. Run the application:

    ```bash
    python age_gender_detection.py
    ```

2. Launch the application to start real-time age and gender detection on your webcam feed.
3. Press 'q' to quit the application.


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Acknowledgments

- The face detection model is based on OpenCV's implementation.
- Age and Gender classification models are trained using publicly available datasets.
- Special thanks to the open-source community for providing valuable resources.
