# Crop Disease Prediction System

## Overview

The Crop Disease Prediction System is a deep learning-based application designed to identify diseases in crop leaves from images. The system leverages transfer learning with MobileNetV2 to classify plant diseases accurately and provide rapid predictions that can assist farmers, researchers, and agricultural professionals.

The primary objective of this project is to automate disease detection and reduce the dependency on manual inspection, enabling early intervention and improved crop management.

---

## Problem Statement

Plant diseases significantly impact agricultural productivity and food security. Traditional disease identification methods require expert knowledge and can be time-consuming.

This project aims to develop an automated image-based disease classification system capable of identifying crop diseases from leaf images using deep learning techniques.

---

## Methodology

### 1. Data Collection

A labeled dataset containing healthy and diseased crop leaf images was collected and organized into disease-specific categories.

### 2. Image Preprocessing

The images were preprocessed before training:

* Image resizing
* Pixel normalization
* Data augmentation
* Conversion into model-compatible format

Data augmentation techniques such as rotation, flipping, zooming, and shifting were used to improve model generalization.

### 3. Transfer Learning using MobileNetV2

The project utilizes MobileNetV2 as the backbone architecture because of its:

* Lightweight design
* Fast inference speed
* High accuracy
* Suitability for deployment on resource-constrained devices

The pre-trained MobileNetV2 model was fine-tuned on the crop disease dataset to learn disease-specific features.

### 4. Model Training

The network was trained using:

* Transfer Learning
* Fine-Tuning
* Cross-Entropy Loss
* Adam Optimizer

Performance was monitored using validation accuracy and loss metrics.

### 5. Disease Prediction

For a given leaf image:

1. The image is preprocessed.
2. MobileNetV2 extracts visual features.
3. The trained classifier predicts the disease category.
4. The disease name and confidence score are displayed.

---

## Features

* Automated crop disease detection
* Deep learning-based image classification
* MobileNetV2 transfer learning model
* Fast prediction pipeline
* Support for multiple disease categories
* Confidence score generation
* User-friendly prediction interface

---

## System Workflow

1. Upload crop leaf image
2. Image preprocessing
3. Feature extraction using MobileNetV2
4. Disease classification
5. Display prediction results

---

## Results

The developed system successfully:

* Identifies diseases from crop leaf images
* Performs accurate classification across multiple disease classes
* Generates predictions in real time
* Supports scalable deployment for agricultural applications

---

## Applications

* Smart Agriculture
* Precision Farming
* Disease Monitoring
* Agricultural Research
* Farmer Assistance Systems
* Crop Health Management

---

## Technologies Used

* Python
* PyTorch
* MobileNetV2
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## Future Improvements

* Mobile application deployment
* Multi-crop support
* Real-time field disease detection
* Explainable AI visualizations (Grad-CAM)
* Cloud-based prediction service
* Disease severity estimation

---

## Author

**Darshan Niphade**

Computer Engineering Student | AI/ML Enthusiast | Research Intern

LinkedIn: linkedin.com/in/darshan-niphade

---

## Conclusion

The Crop Disease Prediction System demonstrates the effectiveness of transfer learning for agricultural image analysis. By utilizing MobileNetV2 and deep learning techniques, the system provides an efficient and scalable solution for early crop disease detection, helping improve agricultural productivity and decision-making.
