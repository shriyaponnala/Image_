# Skin Lesion Segmentation and Classification

## Introduction
This project uses advanced AI to analyze skin lesion images, segmenting the marks from the background and classifying them to help in early detection.

## Objective
Create a model for skin lesion image segmentation and classification based on ISIC 2018 Task 1.

## Approach
1. **Multi-Task Learning:** The model learns shared features for both segmentation and classification tasks.
2. **Feature Representation:** A CNN, resembling VGG-16, is trained and used as an encoder in the U-Net architecture for segmentation tasks.
3. **Image Size and Training:** Images are resized to (112, 112, 3) to manage computing resources, and training is done in stages.

## Results
- **Classification Accuracy:** 90.04%
- **Segmentation Jaccard Index:** 0.7628

## Technologies Used
- **Languages:** Python
- **Frameworks/Libraries:** TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib
