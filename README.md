# Deepfake Detection using VGG16

## Overview
This project implements a deep learning solution for detecting deepfake images using a pre-trained VGG16 neural network. This was developed as part of a [Kaggle competition](https://www.kaggle.com/competitions/wec-intelligence-sig-2024-recruitment-task-cv). The model achieved an impressive **98.25% accuracy**, ranking 6th in the competition.

## Key Features
- Binary classification of real vs. fake images
- Advanced data augmentation techniques
- Transfer learning with VGG16
- Robust model training and validation

## Technical Stack
- Python
- PyTorch
- scikit-learn
- torchvision
- pandas

## Model Architecture
- Base Model: VGG16 (pre-trained)
- Modified final layer for binary classification
- Training with Adam optimizer
- Cross-Entropy Loss function

## Dataset Preprocessing
- Image resizing to 224x224
- Data augmentation:
  - Random horizontal flips
  - Random rotation
  - Color jittering
- Normalization using ImageNet statistics

## Performance Metrics
- Validation F1 Score: Tracked during training
- Best Model: Saved based on highest F1 Score

## Acknowledgments
- Kaggle Competition: [DeepFake Detection Task](https://www.kaggle.com/competitions/wec-intelligence-sig-2024-recruitment-task-cv/)
