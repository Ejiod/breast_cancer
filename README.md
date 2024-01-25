# Vision Transformer Comparative Analysis
# Overview

This project aims to perform a comparative analysis of different Vision Transformer models on a specific image classification task. The models compared include Swin Transformer, Vision Transformer (ViT), and Data-efficient Image Transformer (DeiT). The analysis focuses on training each model on the same dataset and comparing their performance based on validation accuracy.
Models Used

    Swin Transformer (swin_t): An advanced transformer model known for its effectiveness in various vision tasks.
    Vision Transformer (vit_b_16): The original Vision Transformer model by Google, applying the transformer architecture to image classification.
    Data-efficient Image Transformer (deit_base_patch16_224): A transformer model designed for effective training on smaller datasets.

# Setup

To run this project, ensure you have the following prerequisites installed:

    Python 3.8 or later
    PyTorch
    torchvision
    timm (for accessing various transformer models)

**You can install the required libraries using pip:*
pip install torch torchvision timm

# Dataset

The code is designed to work with datasets organized in a directory structure where each subdirectory represents a class. Update the path_to_train_directory and path_to_val_directory in the script with the path to your training and validation datasets.
Running the Code

To start the comparative analysis, simply run the provided Python script. The script will:

    Load and preprocess the data.
    Initialize each model and modify its classifier head for binary classification.
    Train and validate each model for a set number of epochs.
    Record and compare the best validation accuracy achieved by each model.
