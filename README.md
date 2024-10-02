# Real-Time-Emotion-detection-using-OpenCV-and-Deepface
Welcome to the Real-Time Emotion Detection project repository. This project leverages the power of OpenCV for real-time video processing and the Deepface library for emotion detection from facial expressions.

# Project Description
This project is aimed at detecting emotions from real-time video feeds. It uses OpenCV to capture and process video input, while Deepface, a powerful facial recognition and analysis library, is used to analyze facial expressions and classify emotions.
The following emotions can be detected:
Angry
Disgust
Fear
Happy
Sad
Surprise
Neutral

# Features
Real-time emotion detection from webcam or video input.
Simple and easy-to-understand code structure.
Uses pre-trained deep learning models for accurate emotion detection.
Outputs live emotions on the video feed for each detected face.

# Installation
To run this project locally, follow these steps:

1. Clone the repository:
- git clone https://github.com/TITUS-001/Real-Time-Emotion-detection-using-OpenCV-and-Deepface.git
- cd Real-Time-Emotion-detection-using-OpenCV-and-Deepface

2. Install dependencies: Ensure you have Python installed on your system. Install the necessary dependencies by running:
- pip install -r requirements.txt

3. Run the project: Execute the following command to start the emotion detection:
- python emotion_detector.py

# Usage
Once the script is running, the webcam feed will open, and the system will start detecting faces. Each detected face will display an emotion label on the screen in real-time.
You can also modify the input to process a saved video file instead of using the webcam.

# Dependencies
This project uses the following key libraries:
- OpenCV: For video capture and face detection.
- Deepface: For analyzing emotions from the detected faces.
- TensorFlow/Keras: Deep learning framework used by Deepface.

Install the dependencies using:   pip install opencv-python deepface tensorflow

# Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork this repository.
Create a new branch for your feature or bugfix.
Make your changes and commit them.
Submit a pull request.
