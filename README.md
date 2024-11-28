# Deepfake Video Detection using ResNext and LSTM Algorithms

## Overview
This project focuses on detecting video deepfakes using advanced deep learning techniques such as ResNext and LSTM. The project leverages transfer learning, where a pre-trained ResNext CNN model extracts feature vectors, and an LSTM layer processes these features for deepfake detection.

## Features
- Deepfake Detection: Utilize cutting-edge deep learning models to analyze and classify video content.
- Transfer Learning: Incorporates ResNext CNN for feature extraction and LSTM for temporal sequence analysis.
- User-Friendly Interface: Upload videos through a Django-based web application to get real-time predictions.

## How it Works
This is a deepfake detection system based on neural networks and deep learning techniques. In this, the faces of the people in videos are analyzed by using transfer learning with ResNext50 and LSTM, and further sending it to a deep learning model to detect the fabrication in the video. This developed system works seamlessly with huge amounts of input data and outputs accurate predictions. On top of that the proposed project is an End-to-End system which has been deployed on cloud for the world to use.

### UI of the Application

Deepfake Video Uploading Page

<p align="center">
  <img src="https://github.com/mohyd2233/Deepfake-Detection-Project/blob/main/github_assets/main_landing_page.jpeg" />
</p>

Deepfake Video Prediction Page

<p align="center">
  <img src="https://github.com/mohyd2233/Deepfake-Detection-Project/blob/main/github_assets/prediction_page.png" />
</p>

## Installation and Usage
1. Clone the repository: git clone https://github.com/mohyd2233/Deepfake-Detection-Project
2. Install dependencies: pip install -r requirements.txt
3. Run the Flask app: python app.py