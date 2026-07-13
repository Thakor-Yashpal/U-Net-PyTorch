# RoadNet: Road Segmentation using U-Net and PyTorch

## Overview

RoadNet is a beginner-friendly deep learning project for learning **semantic segmentation** with **U-Net** in **PyTorch**.

The goal is to build a U-Net model from scratch that can identify road pixels in aerial or satellite images.

## Learning Objectives

- Understand semantic segmentation
- Build a custom PyTorch `Dataset`
- Create `DataLoader`s
- Implement U-Net from scratch
- Train with BCE + Dice Loss
- Evaluate using Dice Score, IoU, and Pixel Accuracy
- Visualize predictions
- Save and load trained models

## Tech Stack

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- OpenCV
- Pillow

## Repository Structure

```text
RoadNet-U-Net-PyTorch/
│
├── RoadNet.ipynb
├── README.md
├── requirements.txt
└── dataset/
```

## Dataset

This project is designed to work with a road segmentation dataset such as:

- DeepGlobe Road Extraction
- Massachusetts Roads Dataset

The dataset should contain paired road images and segmentation masks.

## Results

The notebook will include:

- Training and validation loss curves
- Dice Score
- IoU
- Pixel Accuracy
- Prediction visualizations

## Future Improvements

- U-Net++
- Attention U-Net
- Data Augmentation
- Mixed Precision Training
- Early Stopping

## Author

**Yashpalsinh Thakor**
