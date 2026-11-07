# Handwritten Prescription Recognition

An ongoing Deep Learning project focused on recognizing handwritten medicine names and text from prescription images using OCR.

## Project Objective

The goal is to develop a handwritten text recognition system using a CRNN (Convolutional Recurrent Neural Network) architecture with CTC loss.

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- PIL
- Google Colab

## Dataset

**RxHandBD – Handwritten Prescription Dataset**

Dataset source: https://data.mendeley.com/datasets/dsb5r6vskg/3

## Current Progress

- [x] Dataset loading
- [x] Dataset inspection
- [x] Image visualization
- [x] Training and validation split
- [x] Character encoding
- [x] Image preprocessing and resizing
- [x] Image-label verification
- [x] TensorFlow Dataset preparation
- [ ] CRNN model architecture
- [ ] CTC loss implementation
- [ ] Model training
- [ ] Model evaluation
- [ ] Prediction visualization

## Current Approach

The current implementation uses:

- CNN for visual feature extraction.
- BiLSTM for sequence learning.
- CTC loss for handwritten text recognition.

## Project Status

Currently in the data preparation stage. Model development and training are upcoming.

More updates will be added as development progresses.
