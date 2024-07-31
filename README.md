# Sign Language Recognition with TensorFlow, OpenCV, and MediaPipe

This project focuses on gesture recognition using TensorFlow, OpenCV, and MediaPipe. The goal is to detect and classify different sign languages using computer vision techniques and machine learning models.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction
This project implements a sign language recognition system using various machine learning and computer vision libraries. The system is designed to detect sign language in real-time from video input, leveraging the powerful capabilities of TensorFlow for model training and inference, OpenCV for image processing, and MediaPipe for holistic tracking and gesture detection.

## Installation
To get started with this project, you need to have Python installed on your system. Follow the steps below to set up the required dependencies:

1. Clone this repository:
   ```bash
   git clone https://github.com/harshitavishnoi/sign_language_transcription.git
   cd sign_language_transcription
   ```

2. Install the necessary Python packages:
   ```bash
   pip install tensorflow
   pip install tensorflow-gpu
   pip install matplotlib
   pip install opencv-python-headless==4.5.3.56
   pip install mediapipe
   pip install scikit-learn
   ```

## Usage
After installing the dependencies, you can run the Jupyter notebook to start the project. The notebook includes all the necessary steps for data preprocessing, model training, and real-time sign language detection.

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook training.ipynb
   ```

2. Follow the steps in the notebook to execute the code cells and train the model.

3. Use the trained model for real-time sign language detection.

## Project Structure
The project structure is as follows:
```
your-repo-name/
├── data/                  # Directory for storing data and logs
├── training.ipynb         # Main Jupyter notebook
├── README.md              # Project README file
└── requirements.txt       # List of required dependencies
```

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## Acknowledgements
- TensorFlow: https://www.tensorflow.org/
- OpenCV: https://opencv.org/
- MediaPipe: https://mediapipe.dev/
