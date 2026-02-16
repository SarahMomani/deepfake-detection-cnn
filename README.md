# deepfake-detection-cnn
End-to-end CNN deepfake image classifier with preprocessing, augmentation, and evaluation (Precision, Recall, F1). Includes survey-based analysis of public awareness and cybersecurity implications.
# Overview
This project implements an end-to-end Convolutional Neural Network (CNN) model to classify real vs fake (deepfake) facial images. The goal is to detect AI-generated manipulated media and analyze its implications for misinformation and cybersecurity.
# Features
Image preprocessing and resizing (128×128)
Pixel normalization
Data augmentation (rotation, zoom, flip, shift)
CNN architecture for binary image classification
Performance evaluation using Accuracy, Precision, Recall, F1-score, and Confusion Matrix
Public awareness survey analysis
# Results
Achieved 88.7% test accuracy on real vs fake image classification.
The model demonstrated strong recall for fake images, which is critical in cybersecurity scenarios.
# Technologies Used
Python
TensorFlow / Keras
NumPy
Pandas
Matplotlib
Scikit-learn
Google Colab
# Project Context
This project was developed as part of a university research study at Al Hussein Technical University (HTU), combining technical AI implementation with public awareness and cybersecurity analysis of deepfake threats.
# Future Improvements
Increase dataset diversity and size
Experiment with transfer learning (ResNet, EfficientNet)
Extend detection to video and audio deepfakes
Integrate Explainable AI (XAI) techniques
Deploy as a web application
## Repository Structure
- deepfake_cnn_model.ipynb : CNN model implementation and training
- README.md : Project documentation
