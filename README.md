# Image Classification Notebooks

This repository contains Jupyter notebooks used for testing and developing image classification models, with a focus on material science image data.

## 📁 Notebooks

### 1. `Image_Classification.ipynb`
This is the main notebook where a deep learning model is built and trained to classify images. Key components include:
- Image preprocessing and augmentation
- Model architecture (e.g., CNN using TensorFlow/Keras or PyTorch)
- Training, evaluation, and visualization of metrics

### 2. `Test_Picture copy.ipynb`
A utility/testing notebook used for:
- Loading and displaying individual images
- Running classification predictions on single inputs
- Verifying image pipeline logic and output formatting

## 📚 Dependencies
Make sure to install the following libraries (can be done via `pip install`):

```bash
jupyterlab
numpy
matplotlib
tensorflow        # or torch, depending on your notebook
opencv-python     # if used for image processing

