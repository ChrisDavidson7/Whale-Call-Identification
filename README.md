# Whale-Call-Identification

This project aims to unlock the secrets of blue whale communication by building models that can accurately identify various calls made by these creatures.

There are various types of whale vocalizations. The different types of vocalizations and their purposes are still not well understood, and ongoing research continues to uncover new insights into the vocal behaviour of these fascinating animals. Here we focus on a specific vocalization, "A Calls". "A Calls" are characterized by a low-frequency, repetitive pattern of pulses that are typically around 70-90 Hz in frequency. These calls are known to be used for long-distance communication between individual whales and can be heard over large distances. They are typically produced by adult males and can last for several minutes. 

## Project Overview

Data Loading and Visualization: The dataset used for this project is from Kaggle's 'datafestintegration2023' competition, project starts with loading and visualizing the audio files using matplotlib and tensorflow.

Audio Preprocessing: The audio files are converted into a single channel and resampled to have a sample rate of 1000Hz. The lengths of the audio files are analyzed to decide the duration for trimming in the preprocessing stage.

Spectrogram Conversion: The audio files are then preprocessed by converting them into spectrograms. Spectrograms are visual representations of the spectrum of frequencies of a signal as it varies with time. They are created by computing the Short-Time Fourier Transform (STFT) of the audio files.

Data Splitting: The preprocessed data is then split into training and testing datasets.

Model Building and Training: A Convolutional Neural Network (CNN) model is built and trained on the training dataset.

Model Evaluation: The model is evaluated on the testing dataset.

Prediction and Submission: The model is then used to predict the labels of the test data from the competition. The predictions are saved into a CSV file for submission.

## Results
The model achieves an accuracy of 99% on the testing dataset, indicating that it is very effective at identifying whale calls from audio files.

## Conclusion
This project demonstrates the effectiveness of using machine learning, specifically Convolutional Neural Networks, for audio signal processing and classification tasks. The model built in this project could potentially be used in real-world applications such as marine life studies and conservation efforts.

