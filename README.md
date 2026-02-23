# 3D U-Net for Brain Tumor Segmentation Using T1-Weighted MRI

This project implements a 3D U-Net architecture for automatic brain tumor segmentation using T1-weighted MRI volumes from the BraTS 2020 dataset. The model processes full volumetric MRI data using 3D convolutional layers to preserve spatial continuity across slices and perform voxel-wise tumor segmentation.

The dataset is preprocessed through normalization and fixed-size cropping to ensure compatibility with the 3D U-Net architecture. The network is trained using Dice loss to address class imbalance between tumor and background regions. Training results demonstrate stable convergence and effective tumor localization, validated through inference visualizations and Grad-CAM analysis.

This repository includes:

Custom PyTorch Dataset loader for 3D MRI volumes

3D U-Net encoder–decoder architecture with skip connections

Dice loss implementation

Training and validation pipeline

Inference visualization and model saving

The project demonstrates how volumetric deep learning models can be effectively applied to medical image segmentation tasks using a single MRI modality.

