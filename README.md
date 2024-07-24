# Deepfake Detection Project

## Introduction

In today's digital age, the emergence of deepfake technology poses a significant threat by enabling the creation of manipulated videos that can deceive viewers. Our project aims to tackle this challenge by developing an AI-powered deepfake detection system. This system utilizes computer vision techniques and machine learning algorithms to accurately identify and classify videos as either authentic or manipulated.

The primary goal of our project is to provide a reliable tool that can distinguish between real and fake videos, thereby safeguarding against the spread of misinformation and preserving trust in digital media.

## Design

### Technology Stack:
- **Programming Languages:** Python, JavaScript
- **Frameworks:** PyTorch, Django
- **Libraries:** OpenCV, face_recognition, torchvision

### System Architecture:
Our system employs a combination of convolutional neural networks (CNNs) and recurrent neural networks (RNNs) for analyzing video frames. We utilized ResNext as our CNN model to extract frame-level features, which are then processed by an LSTM-based RNN to detect inconsistencies indicative of deepfake manipulation.

### User Interface:
The frontend of our application is developed using Django, providing a user-friendly web interface for uploading videos. Users can submit a video file through the interface, and upon processing, the system provides a classification of the video as real or fake with a confidence level.

## Implementation

### Dataset:
We utilized the Deepfake Detection Challenge dataset, comprising a diverse collection of real and deepfake videos, for training and testing our model. This dataset includes various demographics to ensure the robustness and accuracy of our detection system across different scenarios.

### Model Training:
- **Data Preprocessing:** Videos were preprocessed to extract facial regions and reduce noise, ensuring uniformity in frame count for efficient processing.
- **Model Architecture:** Our model consists of a pre-trained ResNext CNN for feature extraction and an LSTM-based RNN for sequential analysis of video frames.
- **Training Process:** Implemented on Google Colab Pro using PyTorch, optimizing hyperparameters such as learning rates and batch sizes to maximize accuracy.

### User Interface Development:
- Developed using Django framework to create a responsive web application.
- Implemented features for video upload, processing, and result display using HTML, JavaScript, and Python.

## Results

### Performance Metrics:
- **Accuracy:** Achieved a prediction confidence level of over 85% on the validation dataset.
- **User Interface:** Successfully deployed a web-based platform where users can upload videos and receive real-time classification results.
- **Testing:** Conducted unit testing to ensure functionality, including scenarios for different video types (real vs. fake) and error handling.

---

More updates to the file will come soon!.
