# deep-learning-project
A Python-based deep learning research project that develops a hybrid 3D U-Net architecture integrated with Residual Network and InceptionV3 for binary lung nodule segmentation from 3D CT scan images.

# Project Overview
This project is based on my undergraduate thesis:
"Pengembangan Arsitektur 3D U-Net dengan Residual Network dan InceptionV3 untuk Segmentasi Kanker Paru pada Citra CT Scan 3D"
📑 Full Thesis: https://repository.unsri.ac.id/194404/

# Research Objective
The main objective of this research is to develop and evaluate a hybrid deep learning architecture consisting of:
- 3D U-Net as the main segmentation framework.
- Residual Network to improve feature propagation and feature representation.
- InceptionV3 to capture multi-scale features.
The proposed architecture is designed for binary segmentation of lung nodules from 3D CT scan images.

# Segmentation Task
This project performs binary segmentation of lung nodules.
Each voxel in the 3D CT scan is classified into two classes:
Class| Description
"0"| Background / Non-nodule
"1"| Lung Nodule
The output of the model is a 3D binary segmentation mask representing the predicted lung nodule region.

# Dataset
This research uses the Lung Task06 dataset from the Medical Segmentation Decathlon (MDS).
 
# Programming Language
This project is developed using Python.
Python is used to implement.
- 3D CT scan preprocessing.
- Dataset preparation.
- 3D model architecture.
- Residual connections.
- InceptionV3-based feature extraction.
- Model training.
- Model validation and testing.
- Binary segmentation.
- Evaluation metrics.
- Segmentation visualization.

# Technologies
- Programming Language: Python
- Task: Binary Lung Nodule Segmentation
- Input: 3D CT Scan Images
- Target: Lung Nodule
- Architecture: 3D U-Net + Residual Network + InceptionV3
- Model Type: 3D Deep Learning Segmentation
- Domain: Medical Image Processing
- Task Type: Binary Segmentation
Depending on the implementation, supporting Python libraries may include:
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

# Academic Context
This project was developed as part of an undergraduate thesis focusing on the development of a deep learning architecture for lung nodule segmentation. The research explores the combination of 3D U-Net, Residual Network, and InceptionV3 for binary segmentation of lung nodules from 3D CT scan images. The project demonstrates the application of deep learning, computer vision, and medical image processing techniques to volumetric CT scan analysis.

# Disclaimer
This project is intended for academic and research purposes. The segmentation results produced by the model should not be considered a medical diagnosis and should not be used as a substitute for assessment by qualified medical professionals.

# Author
Devinka Intan Sagita
