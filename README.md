# Face-Mask-Prediction
A deep learning-based face mask detection system using pre-trained models, designed for real-time classification and deployment in public health applications.

This project implements a robust face mask detection system leveraging state-of-the-art deep learning models. It classifies images as "with_mask" or "without_mask" using transfer learning on pre-trained architectures such as ResNet152V2, InceptionV3, and MobileNetV2. The project is designed for real-time applications with integration into live video streams via OpenCV and Flask.

Features:
Dataset Preparation: Includes preprocessing, augmentation, and normalization of over 7,500 labeled images.
Model Training: Fine-tunes pre-trained models for high accuracy and computational efficiency.
Evaluation Metrics: Provides confusion matrices, precision, recall, and validation accuracy comparison.
Real-Time Integration: Demonstrates real-time mask detection using a lightweight pipeline.
Visualization: Offers insights through validation accuracy graphs, annotated predictions, and model comparisons.
How to Use:
Clone the repository and prepare your dataset by organizing images into "with_mask" and "without_mask" directories.
Use the provided code to train the models or deploy pre-trained models for live video stream detection.
Technologies Used:
Python: Core programming language.
TensorFlow/Keras: For deep learning model development and training.
OpenCV: For image processing and live video stream integration.
