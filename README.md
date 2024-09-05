# SRCNN - Image Super-Resolution

This repository contains an implementation of the Super-Resolution Convolutional Neural Network (SRCNN), a deep learning model designed to enhance the resolution of low-quality images. The goal is to recover high-quality images from their low-resolution counterparts, making it useful for various applications such as image upscaling, restoration, and enhancement.

## Project Overview

Super-Resolution Convolutional Neural Network (SRCNN) is one of the pioneering models for image super-resolution. SRCNN utilizes deep learning to reconstruct high-resolution images by learning an end-to-end mapping between low- and high-resolution images.

### Features
- Implementation of the SRCNN model from scratch using Python and TensorFlow/Keras.
- Training and testing on datasets of low- and high-resolution image pairs.
- Evaluation of model performance using metrics such as PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index).
- Includes pre-trained model weights for quick usage.
  
### How It Works
1. **Input**: The low-resolution image is first preprocessed and upscaled using bicubic interpolation.
2. **SRCNN Architecture**: 
   - Patch Extraction and Representation
   - Non-linear Mapping
   - Reconstruction
3. **Output**: The model outputs a high-resolution image.

## Datasets
The model is trained and tested on standard datasets commonly used for image super-resolution tasks, such as:
- [91 Image Dataset](https://github.com/jbhuang0604/SR-CNN)
- [Set5](https://people.ee.ethz.ch/~timofter/)

You can also use your own dataset of low- and high-resolution image pairs by following the data preparation guidelines provided.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Krishanu2206/SRCNN.git
