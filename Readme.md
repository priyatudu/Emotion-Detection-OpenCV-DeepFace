# Facial Emotion Detection Using OpenCV and DeepFace

## Project Overview

This project demonstrates facial emotion analysis using Python, OpenCV, and DeepFace. It processes facial images or video frames and displays the emotion category predicted by a pretrained DeepFace model.

## Objectives

- Detect faces in images or video frames.
- Estimate facial emotion categories using DeepFace.
- Display the predicted emotion and emotion scores.
- Explore the integration of computer vision libraries in a Python application.

## Technologies Used

- Python
- OpenCV (`cv2`)
- DeepFace
- NumPy

## Emotion Categories

The model can return categories such as happy, sad, angry, fear, surprise, disgust, and neutral.

## How It Works

1. Capture or load an image or video frame.
2. Use the face-analysis pipeline to analyze the detected face.
3. Retrieve the predicted emotion category and available scores.
4. Display the results to the user.



## Learning Outcomes

- Working with OpenCV for image or video processing.
- Integrating a pretrained facial-analysis model.
- Reading and interpreting model prediction scores.
- Building a basic computer vision application in Python.

## Limitations

The predicted category is an estimate based on visible facial patterns. It does not establish a person's actual feelings, intentions, or mental state. Results may vary with lighting, pose, image quality, and other factors.

## Future Improvements

- Improve error handling and face-detection reliability.
- Measure inference time and optimize processing.
- Add a simple user interface.
- Evaluate performance across diverse images and recording conditions.