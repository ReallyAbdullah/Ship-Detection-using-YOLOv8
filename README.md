# Ship Detection with YOLOv8

This Python notebook demonstrates how to train a YOLOv8 model to detect ships in top-view drone imagery. YOLOv8 (You Only Look Once version 8) is a state-of-the-art object detection model known for its speed and accuracy.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Data Preparation](#data-preparation)
- [Training](#training)
- [Inference](#inference)
- [Results](#results)
- [License](#license)

## Introduction

Ship detection in top-view drone imagery has various applications, including maritime surveillance, environmental monitoring, and search and rescue operations. This notebook aims to provide a step-by-step guide on training a YOLOv8 model for ship detection.

In this notebook, we will cover the following:

1. Data preparation: Organizing the dataset and annotation files.
2. Model configuration: Configuring YOLOv8 for ship detection.
3. Model training: Training the YOLOv8 model on the dataset.
4. Inference: Using the trained model for ship detection on new images.

## Requirements

To run this notebook, you will need the following Python libraries and tools:

- `PyTorch`: YOLOv8 is implemented in PyTorch.
- `OpenCV`: For image manipulation and visualization.
- `matplotlib`: For result visualization.
- `numpy`: For numerical operations.
- GPU support (recommended) for faster training.

You can install these dependencies using `pip`:

```bash
pip install torch torchvision opencv-python matplotlib numpy
```
