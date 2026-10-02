# AI-Based-Smart-hand-Gesture-Recongnition-for-Elderly-and-Disabled-Assistance

# EMG Gesture Classification

## Project Overview

This project focuses on recognizing different hand gestures using EMG (Electromyography) signals. The system processes EMG signals, extracts useful features, and classifies the gestures using machine learning and deep learning techniques.

## Objective

The main objective of this project is to develop an EMG-based hand gesture classification system that can identify different gestures from muscle activity signals.

## Project Workflow

1. Load the EMG dataset from the ZIP archive.
2. Organize the recordings for different subjects and gestures.
3. Segment continuous EMG recordings into fixed-length windows.
4. Apply band-pass filtering to remove unwanted noise.
5. Extract features from the EMG signals.
6. Train machine learning and deep learning classification models.
7. Compare the performance of different models.
8. Save the trained models and classification results.

## Dataset

The dataset contains sEMG and PMG recordings collected from multiple subjects.

- Number of channels: 16
- Sampling frequency: 2000 Hz
- Data includes multiple gesture classes and subjects.
- Recordings are divided into fixed-length trials/windows.

## Feature Extraction

The project extracts features from different domains:

- Time-domain features
- Frequency-domain features
- Time-frequency features
- Wavelet-based features

These features are used to represent the characteristics of the EMG signals.

## Machine Learning Models

The project compares different classification approaches, including:

- Random Forest
- Support Vector Machine (SVM)
- 1D Convolutional Neural Network (1D CNN)

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- SciPy
- Scikit-learn
- TensorFlow/Keras
- Matplotlib

## Applications

EMG-based gesture recognition can be used in:

- Human-Computer Interaction
- Assistive technology
- Prosthetic control
- Rehabilitation systems
- Smart healthcare systems
- Hand gesture-based interfaces

## Project Structure

```text
EMG-Gesture-Classification/
│
├── EMG_Gesture_Classification.ipynb
├── README.md
└── Dataset/

```text
EMG-Gesture-Classification/
│
├── EMG_Gesture_Classification.ipynb
├── README.md
└── Dataset/
