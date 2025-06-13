# Roboflow Dataset Results

This folder contains training results, sample images, and model files related to the Roboflow Encyclopedic MRI Brain Tumor Dataset.

## Dataset Details
- Source: Roboflow Public Dataset
- Total Images: 1003 MRI images
- Format: YOLOv8 (640x640), with preprocessing using Roboflow tools
- Dataset Link: https://app.roboflow.com/computer-vision-by-mehedi/brain-tumour-detection-mri/models/brain-tumour-detection-mri/1

## Model & Training
- Model: YOLOv10 + MobileNet Backbone
- Training Epochs: 100
- Achieved Accuracy: **97.2% mAP@50**

## Contents
- `train_results/`: Training logs and loss graphs
- `images/`: Sample input and output MRI scans
- `model/`: Trained `.pt` model files
- `metrics.txt`: Summary of training performance
