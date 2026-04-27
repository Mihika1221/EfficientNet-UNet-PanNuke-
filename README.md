# Histopathology Image Segmentation using EfficientNet-U-Net

This project implements a deep learning pipeline for nucleus segmentation in histopathology images using the PanNuke dataset.

 Model
- U-Net architecture with EfficientNet-B4 encoder
- Implemented using segmentation_models_pytorch

 Features
- Data preprocessing and augmentation using Albumentations
- 3-fold cross-validation
- Custom loss function (Dice + BCE)
- Evaluation using Dice Score and IoU
- Visualization of predictions

 Dataset
- PanNuke dataset (multi-organ nuclear segmentation dataset)

 Tech Stack
- PyTorch
- Albumentations
- segmentation_models_pytorch

 Results
- Achieved Dice Score of ~0.77

 How to Run
```bash
pip install -r requirements.txt
