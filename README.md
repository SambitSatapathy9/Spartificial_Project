# Spartificial_Project - Rooftop Solar Panel Detection using Deep Learning

Harness the Power of Deep Learning to Identify and Analyze Solar Installations from Aerial Imagery

## Overview

This repository contains code and resources for detecting rooftop solar panels using Convolutional Neural Networks (CNNs). The project aims to identify solar panels from aerial or satellite images using deep learning techniques.

## Dataset

- The dataset used comprises aerial or satellite images containing rooftops with and without solar panels.
- The dataset is structured with images labeled as containing solar panels (positive class) and without solar panels (negative class).

### Data Preprocessing

- Preprocessing steps involved:
  - Image resizing, normalization, and augmentation.
  - Labeling and structuring data for model training.

## Code Structure

- `data.csv`: CSV file with image IDs and corresponding labels for reference and usage.
- **Note:** The training and testing images are not provided here, as they are subject to copyright. 
- `notebooks/`: Jupyter notebooks for data exploration, model training, and result analysis.
- `README.md`: This file providing an overview of the project and its components.

## Requirements

- python>=3.6
 
### Libraries and dependencies
- numpy
- pandas
- matplotlib
- scikit-learn
- tensorflow
